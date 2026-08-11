# buck_converter

An analog closed-loop DC-DC Buck Converter designed and simulated in **KiCad** (with **Ngspice** / **LTspice** support). The system regulates output voltage using a high-side PMOS power switch and an operational amplifier-based Proportional-Integral (PI) feedback loop with output filtering and buffering.

---

## 📁 Repository Structure

```text
.
├── buck.kicad_pro    # KiCad project file
├── buck.kicad_sch    # Schematic (Power stage & Op-Amp PI control loop)
├── buck.kicad_pcb    # Printed Circuit Board layout
├── buck.kicad_prl    # Project display settings
├── buck.wbk          # KiCad / Ngspice simulation workbook & saved waveforms
└── README.md         # Project documentation
