# Compression Ratio and Injector Opening Pressure Effects on Performance, Emissions and Vibration in a Hydrogen-Enriched Biodiesel–Diesel Dual-Fuel Compression-Ignition Engine

A Cross-Validated Machine-Learning and Desirability Optimization Study

## Overview

This repository holds the experimental dataset supporting a manuscript submitted to *Energy Conversion and Management* (Elsevier). The study reports two designed experimental sweeps on a variable compression ratio, direct-injection compression-ignition (CI) engine fuelled with diesel and biodiesel blends (B10-B40) enriched with hydrogen (0-15 L/min):

- **Compression ratio (CR) sweep** - CR = 15, 16, 17, 18
- **Injector opening pressure (IOP) sweep** - 190, 200, 210, 220 bar

Across both sweeps, 80 operating points were recorded per sweep, covering brake-specific fuel consumption (BSFC), brake thermal efficiency (BTE), mechanical and volumetric efficiency, engine block vibration amplitude, and regulated emissions (CO, CO2, HC, NOx) together with smoke opacity.

Three regression methods - an artificial neural network (ANN), response surface methodology (RSM), and random forest (RF) regression - were benchmarked against this data using 5-fold and repeated 5-fold cross-validation, and a multi-response desirability analysis was used to identify balanced operating points.

## Repository contents

| File | Description |
|---|---|
| `CR-Performances-Data-Set.xlsx` | Engine performance measurements (BSFC, BTE, mechanical/volumetric efficiency, vibration) across the compression ratio sweep |
| `CR-Emissions-Smoke-Data-Set.xlsx` | Emissions (CO, CO2, HC, NOx) and smoke opacity measurements across the compression ratio sweep |
| `IOP-Emissions-Smoke-Data-Set.xlsx` | Emissions and smoke opacity measurements across the injector opening pressure sweep |

All data are original experimental measurements collected by the authors on a test-bed engine; no reference/third-party data is included.

## Authors

- Udaya Sri K (corresponding author) - Department of Mechanical Engineering, KG Reddy College of Engineering and Technology, Hyderabad, Telangana, India
- Dafik Dafik - Department of Mathematics, Faculty of Mathematics and Natural Sciences, University of Jember, Jember, Indonesia
- Siva Shankar Subramanian - Department of Computer Science and Engineering, KG Reddy College of Engineering and Technology, Hyderabad, Telangana, India
- Sunder R - School of Computer Science and Engineering, Galgotias University, Greater Noida, India
- Ika Hesti Agustin - Department of Mathematics, Faculty of Mathematics and Natural Sciences, University of Jember, Jember, Indonesia

## Status

Manuscript under review at *Energy Conversion and Management* (Elsevier).

## License

Released under the MIT License (see `LICENSE`).
