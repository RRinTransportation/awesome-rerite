# awesome-rerite
A curated list of awesome open datasets and benchmarks in transportation research.

## How to Contribute?
If you have a dataset or benchmark to contribute, you can:
1. Open an [issue](https://github.com/RRinTransportation/awesome-rerite/issues)
2. Submit a pull request  
3. Contact me via [email](junyi.ji@vanderbilt.edu)

Star this repository if you find it useful!
## Contents

- [Transportation Networks](#transportation-networks)
- [Discrete Choice Modeling](#discrete-choice-modeling)
- [Traffic Dynamics and Control](#traffic-dynamics-and-control)
    - [Vehicle trajectory data](#vehicle-trajectory-data)
    - [Freeway traffic control](#freeway-traffic-control)
    - [Urban traffic control](#urban-traffic-control)
- [Spatio-Temporal Data and Modeling](#spatio-temporal-data-and-modeling)
- [Road Safety](#road-safety)
- [Optimization](#optimization)
- [Miscellaneous](#miscellaneous)


## Transportation Networks
- [Transportation Networks](https://github.com/bstabler/TransportationNetworks) by Ben Stabler
    - Fundamental city network data for transportation network modeling.
- [DTALite](https://github.com/asu-trans-ai-lab/DTALite) developed by ASU Transportation AI Lab
    - DTALite is an open-source Analysis, Modeling, and Simulation (AMS) library for efficiently macroscopic and mesoscopic traffic assignment based on General Modeling Network Specification (GMNS) format.
- [MATSim Scenarios](https://github.com/matsim-scenarios)
- [WardropNet](https://github.com/tumBAIS/ML-CO-pipeline-TrafficPrediction)
    - [WardropNet: Traffic Flow Predictions via Equilibrium-Augmented Learning](https://openreview.net/forum?id=7FHSPd3SRE), ICLR 2025.
- [LargeOD](https://github.com/tsinghua-fib-lab/CommutingODGen-Dataset)
    - [A Large-scale Dataset and Benchmark for Commuting Origin-Destination Flow Generation](https://openreview.net/forum?id=WeJEidTzff), ICLR 2025.

## Discrete Choice Modeling
- [Choice-Learn](https://github.com/artefactory/choice-learn)
    - Discrete choice modeling in Python with large datasets and models

## Traffic Dynamics and Control
### Vehicle trajectory data
- [pNEUMA](https://open-traffic.epfl.ch/)
- Songdo dataset
    - [Songdo Traffic Dataset](https://doi.org/10.5281/zenodo.13828384)
    - [Songdo Vision Dataset](https://doi.org/10.5281/zenodo.13828408)
- [Waymo Open Dataset](https://waymo.com/open/)
- [I-24 MOTION](i24motion.org/data)
- [TGSIM I-294](https://data.transportation.gov/Automobiles/Third-Generation-Simulation-Data-TGSIM-I-294-L1-Tr/7zjf-a4zf/about_data)
- [Zen Traffic Data](https://zen-traffic-data.net/english/)
- [OpenACC](https://data.jrc.ec.europa.eu/dataset/9702c950-c80f-4d2f-982f-44d06ea0009f)
- [microSIM-ACC](https://github.com/microSIM-ACC)

### Freeway traffic control
- [Flow-Lite](https://github.com/mit-wu-lab/automatic_vehicular_control)
    - Lite version of [Flow](https://flow-project.github.io) with its [project repo here](http://github.com/flow-project/flow).
    - Flow-lite is more lightweighted and better suited for research purposes, as it does not include RLlib integration.

### Urban traffic control
- [Intersection Zoo](https://github.com/mit-wu-lab/IntersectionZoo)
    - [IntersectionZoo: Eco-driving for Benchmarking Multi-Agent Contextual Reinforcement Learning](https://openreview.net/forum?id=XoulHHQGFi), ICLR 2025.

## Traffic Simulation
Note: It can be challenging to clearly distinguish between traffic simulation and modeling approaches like DTA. This section focuses on general-purpose traffic simulators, so there may be some overlap with items listed earlier.
- [UXSim](https://github.com/toruseo/UXsim) developed by [Toru Seo](https://toruseo.jp/)
- [DTALite](https://github.com/asu-trans-ai-lab/DTALite) developed by ASU Transportation AI Lab
    - DTALite is an open-source Analysis, Modeling, and Simulation (AMS) library for efficiently macroscopic and mesoscopic traffic assignment based on General Modeling Network Specification (GMNS) format.

## Spatio-Temporal Data and Modeling
- [Spatiotemporal Data](https://spatiotemporal-data.github.io/)

## Road Safety
- [Surrogate Safety Measures](https://github.com/Yiru-Jiao/SSMsOnPlane), contributed by [Yiru Jiao](https://github.com/Yiru-Jiao)

## Optimization
- [RL4CO](https://rl4co.readthedocs.io/en/latest/docs/content/intro/environments/)

## Miscellaneous
This section highlights useful tools and resources that can assist in advancing daily research efforts:
- [Optuna](https://optuna.org/)
    - Optuna is an automatic hyperparameter optimization python framework, particularly designed for machine learning. 
    - Note: This is a tool suggested by [Alex Richardson](https://scholar.google.com/citations?user=BB-pmW0AAAAJ&hl=en) at Vanderbilt University. Thank you, Alex!

---
Maintained by [Junyi Ji](https://www.jijunyi.com/), Views are my own.
Last updated: April 9, 2025