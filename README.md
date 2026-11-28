# M482B Monitor Module · Monitoring

Ward-Beck Systems M482B, 1979|12. Wiki page: [M482B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M482B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 28 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 106 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 9 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 24 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [7 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1982 - M482B - Monitor Module.pdf](MANUALS/1982%20-%20M482B%20-%20Monitor%20Module.pdf) page 2 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** |  |
| &nbsp;&nbsp;Monitor solo | 10 dB +/ -0.5 dB (bridging gain) 10 dB +/ = 0.5 dB (bridging gain) |
| **Frequency response** | +/ -0.5dB from 30 Hz to 15 kHz |
| **Noise** | 80 dB below +18 dBm output level (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0.35% ThD from 30 Hz to 15 kHz at +18 dBm outpul Or&quot; Less. Less than 0.19 at kHz at +18 dBm output |
| **Source impedances** |  |
| &nbsp;&nbsp;Monitor solo | 600 ohms maximum; balanced 600 ohms MaximUm, balanced. |
| **Input impedances** |  |
| &nbsp;&nbsp;Monitor | Solo: 10,000 ohms, balanced. 30 000 ohms, balanced |
| &nbsp;&nbsp;Input levels |  |
| &nbsp;&nbsp;Monitor | Solo: +8 dBm nominal +2L dBm maximum. -2 dBm nominal +14 dBmi maximum; |
| **Output impedances** |  |
| &nbsp;&nbsp;Meter output | Output #I: Output #2: 600 ohms, balanced 600 ohms, balanced 600 ohms, balanced |
| **Load impedances** |  |
| &nbsp;&nbsp;Meter output | Output #I: Output #2: Bridging, balanced (5000 ohms minimum) 600 ohms, balanced. 600 ohms, balanced |
| &nbsp;&nbsp;Output level | +8 dBm nominal, +22 dBm Maximum. |
| **Phasing** | Low numbered terminals are in phase. |

## Circuit description

From [1982 - M482B - Monitor Module.pdf](MANUALS/1982%20-%20M482B%20-%20Monitor%20Module.pdf) pages 4-6 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M4828 Monitor Module permits the monitoring of the main console outputs, the ine selector inputs and three external Sources SOLO input i5 also provided The rrodule outputs are actively balanced operating at Level f +8 dBm. nominal Input Selector Input selections are made with seperate interlock ing pushbutton switch assemblies. Switches Swi to SW10 select the LINE inputs, the CUE input and three external utiliTY inputs. The output of this interlock switch assembly is routed through switch SWiS (SEL) of the second interlocking pushbutton switch assembly. This switch assembly (Sw11 to SWIS) also selects the main console outputs Mi M2 and AUX. An OFF function is also provided (Swi). Preamplifier uI and u2 with their associated components form isolation amplifier which provides balanced bridging inpul to the source selected via the pushbutton input selectors. The output ot this isolation amplifier Needs the monitor Icvel control R30. Solo Input u3 and its associated components form an invertering/isolation amplifier for une side of the balanced SOLO input. The signal is then summed together via R18, R26 and R29, The resultant unbalanced signal is routed to solid state switch u4 Normally U4 passes the signal coming from the input selectors. It thc SOLO control (pin 25 of [he module connector) is activated external Iy, 44 Passes the SOLO signal and turns off the signal from the input selectors. The external SOLO control also activates thc module L0 indicate the SOLO mode. LED on the front panel of Qutput_Amplifier Thc signal is coupled through C18 from the solid state switch uL to the output ampl lifier, made up of U6, 03, 04, u5, 01 and 02 with their associated components. The actively balanced output of this amplifier is coupled through C22 and C23 to the output isolation networks

Module_Outputs_ The M82B Monitor Module provides three seperale outputs_ Theme tering output appearing at pins 57 &amp; 58 is used to feed standard vu meler The direct output appears at Pins 59 8 60, while muted output i5 made available at pins 55 56 of the module connector Muting relay KI can be controlled externally by grounding pin 26, AII outputs have nominal level of +8 dBm. Power_Supply The t/ -25 volt supply voltage is coupled through pol, arily reversal diodes CRI and CR2 to the decoupling network, consisting of Rio, RII and C1 to C4. This network drops the supply voltage to nominal +/ -16 vol [5 Lo operate the module circuitry and isolate il from the main supply rails,

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbTc5dTBDelJTVVE/view?resourcekey=0-dSq_MeDWuPT-lr4a1x_mjQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbTc5dTBDelJTVVE&resourcekey=0-dSq_MeDWuPT-lr4a1x_mjQ" width="240" alt="1982 - M482B - 482-04-001 - MONITOR MODULE FRONT PANEL.jpg"></a><br><sub>1982|15 · 482-04-001 - MONITOR MODULE FRONT PANEL · <a href="MECHANICAL/1982%20-%20M482B%20-%20482-04-001%20-%20MONITOR%20MODULE%20FRONT%20PANEL%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M482B.stl`](MECHANICAL/M482B.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M482B)

- **Size:** 60.45 × 304.63 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 19 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M482B - front panel.svg`)
- the drawn panel is 0.15 wide to high, the size 0.20: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M482B.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT21idDBXdzd3Z1k/view?resourcekey=0-EfWZdG4nITaWmFM9AwvkMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT21idDBXdzd3Z1k&resourcekey=0-EfWZdG4nITaWmFM9AwvkMw" width="240" alt="1982 - M482B - 482-01-001 - MUTE CONTROL OFF SOLO CONTROL SOLO INPUT.jpg"></a><br><sub>1982|15 · 482-01-001 - MUTE CONTROL OFF SOLO CONTROL SOLO INPUT · <a href="SCHEMATICS/1982%20-%20M482B%20-%20482-01-001%20-%20MUTE%20CONTROL%20OFF%20SOLO%20CONTROL%20SOLO%20INPUT%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRlRJcUJCYXlveDg/view?resourcekey=0-aspQsBK0X9P5atwcSbq7fQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRlRJcUJCYXlveDg&resourcekey=0-aspQsBK0X9P5atwcSbq7fQ" width="240" alt="1982 - M482B - 482-02-003 - MONITOR MODULE SCHEMATIC.jpg"></a><br><sub>1982|15 · 482-02-003 - MONITOR MODULE SCHEMATIC · <a href="SCHEMATICS/1982%20-%20M482B%20-%20482-02-003%20-%20MONITOR%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOF90WlNZSVFGY2c/view?resourcekey=0-h1w3bSTfVYvsz2a7qN_wHQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOF90WlNZSVFGY2c&resourcekey=0-h1w3bSTfVYvsz2a7qN_wHQ" width="240" alt="1982 - M482B - 482-06-002 - MONITOR MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1982|15 · 482-06-002 - MONITOR MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1982%20-%20M482B%20-%20482-06-002%20-%20MONITOR%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW9DVDFJUjhHNDA/view?resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW9DVDFJUjhHNDA&resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" width="240" alt="19xx - M482B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.jpg"></a><br><sub>19xx - M482B - DOC - 1202-02-017 - POSTS CHASSIS GROUND · <a href="SCHEMATICS/19xx%20-%20M482B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

59 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 25 | INPUT SELECTORS | in |  | medium |
| 59 | DIRECT OUTPUT | out |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVDFHSlc1V2pXbEE/view?resourcekey=0-RWEtMVHRIRmhrIVp6FPr8A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVDFHSlc1V2pXbEE&resourcekey=0-RWEtMVHRIRmhrIVp6FPr8A" width="240" alt="1982 - M482B - Monitor Module (2).pdf"></a><br><sub>1982|15 · Monitor Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcTNNWGdaSkFYWkE/view?resourcekey=0-3T-gTV0v_xoRiLHF6g-isQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcTNNWGdaSkFYWkE&resourcekey=0-3T-gTV0v_xoRiLHF6g-isQ" width="240" alt="1982 - M482B - Monitor Module.pdf"></a><br><sub>1982|15 · Monitor Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdl8wRHNIZ3c3Rlk/view?resourcekey=0-hPKhffYXTQTN3pU8Zl8IFQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdl8wRHNIZ3c3Rlk&resourcekey=0-hPKhffYXTQTN3pU8Zl8IFQ" width="240" alt="1982 - M482B - P01 - TOC.jpg"></a><br><sub>1982|15 · P01 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUG13ZTB5U19KSGs/view?resourcekey=0-9zUQ1jYQuOHRdourW2o7xQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUG13ZTB5U19KSGs&resourcekey=0-9zUQ1jYQuOHRdourW2o7xQ" width="240" alt="1982 - M482B - P02 - 1-1.jpg"></a><br><sub>1982|15 · P02 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmpSYkZLSnlLQXc/view?resourcekey=0-HKjbf7nwiHLXnzazwkn-PA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmpSYkZLSnlLQXc&resourcekey=0-HKjbf7nwiHLXnzazwkn-PA" width="240" alt="1982 - M482B - P03 - 1-2.jpg"></a><br><sub>1982|15 · P03 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV1B5dkoxWTR0aVk/view?resourcekey=0-h2h6ycZvbRVVW8EaG2Vjtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV1B5dkoxWTR0aVk&resourcekey=0-h2h6ycZvbRVVW8EaG2Vjtw" width="240" alt="1982 - M482B - P04 - 2-1.jpg"></a><br><sub>1982|15 · P04 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLWFadHFTVnYzTHc/view?resourcekey=0-9qCsQiZA-8JCSz2M-BdjHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLWFadHFTVnYzTHc&resourcekey=0-9qCsQiZA-8JCSz2M-BdjHw" width="240" alt="1982 - M482B - P05 - 2-2.jpg"></a><br><sub>1982|15 · P05 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmI1VDE0V1Vpa2s/view?resourcekey=0-XtMgTdHrUiXdEvCusRf1yQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmI1VDE0V1Vpa2s&resourcekey=0-XtMgTdHrUiXdEvCusRf1yQ" width="240" alt="1982 - M482B - P06 - 3-1.jpg"></a><br><sub>1982|15 · P06 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHZqOG82THNPbWM/view?resourcekey=0-jnj2HYf0F5CSqQrWCEV1QQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHZqOG82THNPbWM&resourcekey=0-jnj2HYf0F5CSqQrWCEV1QQ" width="240" alt="1982 - M482B - P07 - 3-2.jpg"></a><br><sub>1982|15 · P07 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR0JBb25FWWxiQlk/view?resourcekey=0-m-d0LhNw4eXTn46CHAhlAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR0JBb25FWWxiQlk&resourcekey=0-m-d0LhNw4eXTn46CHAhlAA" width="240" alt="1982 - M482B - P08 - 3-3.jpg"></a><br><sub>1982|15 · P08 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYkdSN1BRMVFrZDg/view?resourcekey=0-FhAPLGExfnzT0Pzv3NFNGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYkdSN1BRMVFrZDg&resourcekey=0-FhAPLGExfnzT0Pzv3NFNGg" width="240" alt="1982 - M482B - P09 - 3-4.jpg"></a><br><sub>1982|15 · P09 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMEhhX01NdU5CWUU/view?resourcekey=0-Udel10-hs7YOEKu0CcylQQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMEhhX01NdU5CWUU&resourcekey=0-Udel10-hs7YOEKu0CcylQQ" width="240" alt="1982 - M482B - P10 - 4-1.jpg"></a><br><sub>1982|15 · P10 - 4-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzZjWFBUb2lmOXc/view?resourcekey=0-lx3UtibxgGng6zB_e69HWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzZjWFBUb2lmOXc&resourcekey=0-lx3UtibxgGng6zB_e69HWg" width="240" alt="1982 - M482B - P11 - 5-1.jpg"></a><br><sub>1982|15 · P11 - 5-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKem5nZ1pUZkVwNVk/view?resourcekey=0-xjiax86LOvodGR8P0DzKPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKem5nZ1pUZkVwNVk&resourcekey=0-xjiax86LOvodGR8P0DzKPA" width="240" alt="19xx - M482B - DOC - L1202A - P20 - 111-2.jpg"></a><br><sub>19xx - M482B - DOC - L1202A - P20 - 111-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjZmVXh3NmI3bk0/view?resourcekey=0-MwxTHhnMo-hjQ3fuoo5DHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjZmVXh3NmI3bk0&resourcekey=0-MwxTHhnMo-hjQ3fuoo5DHA" width="240" alt="19xx - M482B - DOC - L1202A - P21 - 111-3.jpg"></a><br><sub>19xx - M482B - DOC - L1202A - P21 - 111-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSU1GVElVaEpFRnM/view?resourcekey=0-uDfNpm8pY_aQnjDK71iSbg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSU1GVElVaEpFRnM&resourcekey=0-uDfNpm8pY_aQnjDK71iSbg" width="240" alt="19xx - M482B - DOC - L1202A - P23 - 111-5.jpg"></a><br><sub>19xx - M482B - DOC - L1202A - P23 - 111-5</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1979 - 482-01-001 - MONITOR MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG MRW - ISS 1.kicad_sch](KICAD/1979%20-%20482-01-001%20-%20MONITOR%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1982 - M482B - 482-01-001 - MUTE CONTROL OFF SOLO CONTROL SOLO INPUT.kicad_sch](KICAD/1982%20-%20M482B%20-%20482-01-001%20-%20MUTE%20CONTROL%20OFF%20SOLO%20CONTROL%20SOLO%20INPUT.kicad_sch)
- [1982 - M482B - 482-02-003 - MONITOR MODULE SCHEMATIC.kicad_sch](KICAD/1982%20-%20M482B%20-%20482-02-003%20-%20MONITOR%20MODULE%20SCHEMATIC.kicad_sch)
- [1982 - M482B - Monitor Module (2) p13.kicad_sch](KICAD/1982%20-%20M482B%20-%20Monitor%20Module%20(2)%20p13.kicad_sch)
- [1982 - M482B - Monitor Module p13.kicad_sch](KICAD/1982%20-%20M482B%20-%20Monitor%20Module%20p13.kicad_sch)
- [1982 - M482B - Monitor Module p14.kicad_sch](KICAD/1982%20-%20M482B%20-%20Monitor%20Module%20p14.kicad_sch)
- [19xx - M482B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.kicad_sch](KICAD/19xx%20-%20M482B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND.kicad_sch)
- [M482B - P13 - Functional Diagram.kicad_sch](KICAD/M482B%20-%20P13%20-%20Functional%20Diagram.kicad_sch)
- [M482B.kicad_sym](KICAD/M482B.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
