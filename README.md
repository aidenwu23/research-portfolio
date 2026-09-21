# Research Portfolio

A curated synthesis of my research work for undergraduate applications.

Public links below point to ePIC/EIC Indico events, individual contributions, official GitHub repositories, and associated research code.

---

## Presentations

### Biweekly Forward Hadronic Calorimeter Meetings

Selected simulation presentations and research updates delivered at LFHCal/Insert meetings.

**Simulation Update** - LFHCal General Meeting - September 2, 2026  
Event: https://indico.bnl.gov/event/34188/#14-simulation  
Contribution: https://indico.bnl.gov/event/34188/#14-simulation

**Insert Rates** - LFHCal General Meeting - August 12, 2026  
Event: https://indico.bnl.gov/event/33832/#14-simulation  
Contribution: https://indico.bnl.gov/event/33832/contributions/127815/attachments/72030/123342/insert_updates_20260812.pdf

**LFHCal response** - LFHCal General Meeting - July 29, 2026  
Event: https://indico.bnl.gov/event/33601/#14-simulation  
Contribution: https://indico.bnl.gov/event/33601/contributions/127190/attachments/71725/122937/lfhcal_n_insert.pdf

**LFHCal rates** - Joint LFHCal & Insert Meeting - June 24, 2026  
Event: https://indico.bnl.gov/event/33199/#14-simulation  
Contribution: https://indico.bnl.gov/event/33199/contributions/125610/attachments/70980/121644/LFHCAL%20rates.pdf

### ePIC Technical and Integration Council

**Rates at the LFHCal** - July 6, 2026  
Presented as *Background challenges: LFHCAL* at the ePIC Technical and Integration Council.

Event: https://indico.bnl.gov/event/33375/  
Contribution: https://indico.bnl.gov/event/33375/contributions/126347/attachments/71152/121912/lfhcal_rates.pdf

### Backward HCal DSC

**Neutron efficiency optimization for the nHCal** - June 30, 2026  
Presented as *Machine Learning for nHCal design* at the Backward HCal DSC weekly meeting.

Event: https://indico.bnl.gov/event/33380/  
Contribution: https://indico.bnl.gov/event/33380/contributions/126359/attachments/71043/121733/nHCal%20optimization%20with%20ML.pdf

### LFHCal Testbeam Analysis Workfest at Yale

**Electron/Pion event tagging** - August 17-21, 2026  
Simulation study for electron/pion discrimination in the 2026 LFHCal test-beam configuration.

Event: https://indico.bnl.gov/event/33760/  
Contribution: https://indico.bnl.gov/event/33760/contributions/128665/attachments/72222/123656/8192026_event_tagging.pdf

---

## Technical Note

### LightGBM-Guided Exploration of a Six-Dimensional ePIC nHCal Design Space for Low-Energy Neutron Detection

**Status:** Under review  
**Author:** Aiden Wu  
**Note Number:** epic-TN-TC_2026-005

[View Technical Note (PDF)](epic-TN-TC_2026-005.pdf)

---

## EIC/ePIC Software Contributions

**Insert/LFHCAL geometry update** - `eic/epic` PR #1153 - merged  
Updated Insert geometry based on recent mechanical redesigns and updated LFHCal readout-layer grouping.

https://github.com/eic/epic/pull/1153

**Support updated Insert geometry** - `eic/EICrecon` PR #2890 - merged  
Updated Insert reconstruction to support the revised detector geometry.

https://github.com/eic/EICrecon/pull/2890

**Updated LFHCal test-beam geometry** - `eic/epic` PR #1160 - merged  
Updated the 2026 LFHCal test-beam geometry for electron/pion simulation studies.

https://github.com/eic/epic/pull/1160

**LFHCal test-beam trigger scintillator geometry** - `eic/epic` PR #1164 - merged  
Added trigger scintillators to the LFHCal test-beam geometry.

https://github.com/eic/epic/pull/1164

**Fix runaway theta-resolution fits in `insert_neutron`** - `eic/detector_benchmarks` PR #343  
Updated Insert neutron angular-resolution fitting using iterative Gaussian fits.

https://github.com/eic/detector_benchmarks/pull/343

**LFHCal SiPM/CALOROC digitization** - work in progress  
Development in the official `eic/EICrecon` repository.

https://github.com/eic/EICrecon/tree/pr/lfhcal-sipm-caloroc-digitization

---

## Research Code

### HCAL Optimizer

HCAL geometry optimization with DD4hep/DDsim and a LightGBM surrogate model.

https://github.com/aidenwu23/hcal_optimizer

### Rate Analysis for the Forward HCals

Analysis software for LFHCal and forward-Insert occupancy, background composition, channel/chip rates, and readout-rate studies.

https://github.com/aidenwu23/fhcal-rates

### Centauro

Quantitative comparison of lab-frame anti-kT and Breit-frame Centauro jet definitions for ePIC DIS TMD measurements.

https://github.com/aidenwu23/centauro

---

## Additional Collaboration Contributions

**Background-event reuse in simulated background samples**  
Issue identified during LFHCal background-rate studies and documented in the official `eic/HEPMC_Merger` repository.

https://github.com/eic/HEPMC_Merger/issues/24
