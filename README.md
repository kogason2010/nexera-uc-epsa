# Exposed: EPSA by supercritical fluid chromatography

**Live site:** https://kogason2010.github.io/nexera-uc-epsa/

A scroll-driven three.js journey through Shimadzu Application News 01-01161-EN,
*Measurement of Experimental Polar Surface Area Using Supercritical Fluid Chromatography*
(Hirota, Ogami, Masuda, April 2026). It follows CO₂ to the supercritical state, folds
cyclosporin A from its TPSA of 278 Å² to its EPSA of 62 Å², races the nine calibration
standards through the column, builds the calibration line, and replays the diclofenac
system suitability test.

> Independent, unofficial project. Not affiliated with, sponsored or endorsed by Shimadzu Corporation.

- **Single file:** `index.html` (three.js r128 and its bloom passes load from cdnjs and jsDelivr).
- **Demo mode:** press *Play demo* or the D key for a guided two-minute scroll.
- Companion sites: https://kogason2010.github.io/nexera-ic/ and https://kogason2010.github.io/nexera-ic-applications/

## Data and accuracy

Taken from the application note: calibration equations (PDA EPSA = 53.991 t<sub>R</sub> + 25.177,
R² 0.9977; MS EPSA = 54.167 t<sub>R</sub> + 23.365, R² 0.9976), the nine standards' EPSA values and ions,
TPSA/EPSA for cyclosporin A (278/62 Å²) and ritonavir (145/75 Å²), ritonavir retention times,
chromatographic conditions, and the SST results (limits 2.100–2.200 min, 2 Feb fail at 2.237 min).

Illustrative: the molecule geometry (an 11-residue ring with 11 N and 12 O, five of them left
exposed when folded, matching 62/278), chromatogram peak heights, and standards' retention times,
which are placed on the published PDA and MS calibration lines. The CO₂ phase diagram uses the
critical point (31.1 °C, 7.38 MPa) and saturation pressures from 10 to 31 °C.
