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
- [Transportation and AI](#transportation-and-ai)
- [Miscellaneous](#miscellaneous)

## Transportation Demand and Network Modeling
- [Travel Forecasting, Explained
](https://tfresource.org/), a big shoutout to [Greg Macfarlane, Ph.D.](https://gregmacfarlane.github.io/)
- [Transportation Networks](https://github.com/bstabler/TransportationNetworks) by Ben Stabler
    - Fundamental city network data for transportation network modeling.
- [OSMnx](https://osmnx.readthedocs.io/en/stable/), developed by [Geoff Boeing](https://geoffboeing.com/)
    - Zephyr Foundation’s 2025 Exceptional Technical Achievement Award!
- [osm2gmns](https://pypi.org/project/osm2gmns/1.0.0rc1/)
    - Developed by Jiawei Lu, Xuesong (Simon) Zhou.
    - A Python package for converting OpenStreetMap (OSM) data to Generalized Modeling Network Specification (GMNS) format.
- [DTALite](https://github.com/asu-trans-ai-lab/DTALite) developed by ASU Transportation AI Lab
    - DTALite is an open-source Analysis, Modeling, and Simulation (AMS) library for efficiently macroscopic and mesoscopic traffic assignment based on General Modeling Network Specification (GMNS) format.
- [MATSim Scenarios](https://github.com/matsim-scenarios)
- [DTA](https://github.com/DrKeHan/DTA) developed by Dr. Ke Han.
    - Han, K, Eve, G, Friesz, TL, 2019. Computing dynamic user equilibria on large-scale networks with software implementation. Networks and Spatial Economics, Volume 19, Issue 3, pp 869–902.
- [UniTA](https://github.com/xuxiaotong/A_unified_and_validated_traffic_dataset_for_20_U.S._cities)
    - A unified dataset for the city-scale traffic assignment model in 20 U.S. cities.
    - Note: I give it a short name "UniTA" for easy reference. If the authors see this and have a better name, please let me know!
- [WardropNet](https://github.com/tumBAIS/ML-CO-pipeline-TrafficPrediction)
    - [WardropNet: Traffic Flow Predictions via Equilibrium-Augmented Learning](https://openreview.net/forum?id=7FHSPd3SRE), ICLR 2025.
- [LargeOD](https://github.com/tsinghua-fib-lab/CommutingODGen-Dataset)
    - [A Large-scale Dataset and Benchmark for Commuting Origin-Destination Flow Generation](https://openreview.net/forum?id=WeJEidTzff), ICLR 2025.
- [OSRM](https://project-osrm.org/)
    - Open Source Routing Machine (OSRM) is a high-performance routing engine written in C++14.
## Discrete Choice Modeling

### Benchmarks
- [Choice-Learn](https://github.com/artefactory/choice-learn)
    - Discrete choice modeling in Python with large datasets and models
- [DNN for choice modeling](https://github.com/siqi-feng/DNN-behavioral-regularity)
    - Ascoicated with TR-C paper [Deep neural networks for choice analysis: Enhancing behavioral regularity with gradient regularization](https://arxiv.org/abs/2404.14701)
- [Apollo](https://www.apollochoicemodelling.com/examples.html)
    - Hess, S. & Palma, D. (2019), Apollo: a flexible, powerful and customisable freeware package for choice model estimation and application, Journal of Choice Modelling, Volume 32, September 2019, 100170. Link to the homepage: [Apollo](https://www.apollochoicemodelling.com/code.html).
    - Choice modeling in general, suggested by [Siqi Feng](https://daziano.cee.cornell.edu/members/). Thank you, Siqi!

### Datasets
- [Swissmetro](https://transp-or.epfl.ch/pythonbiogeme/examples_swissmetro.html), suggested by [Siqi Feng](https://daziano.cee.cornell.edu/members/). Thank you, Siqi!

## Traffic Dynamics and Control
### Vehicle trajectory data
- [pNEUMA](https://open-traffic.epfl.ch/)
- Songdo dataset
    - [Songdo Traffic Dataset](https://doi.org/10.5281/zenodo.13828384)
    - [Songdo Vision Dataset](https://doi.org/10.5281/zenodo.13828408)
- [Waymo Open Dataset](https://waymo.com/open/)
- [I-24 MOTION](https://i24motion.org/data)
- [TGSIM I-294](https://data.transportation.gov/Automobiles/Third-Generation-Simulation-Data-TGSIM-I-294-L1-Tr/7zjf-a4zf/about_data)
- [Zen Traffic Data](https://zen-traffic-data.net/english/)
- [OpenACC](https://data.jrc.ec.europa.eu/dataset/9702c950-c80f-4d2f-982f-44d06ea0009f)
- [microSIM-ACC](https://github.com/microSIM-ACC)

### [The Lord of the Rings](https://dl.acm.org/doi/10.1145/3494577)
- [The Nagoya Traffic Jam Experiment](https://github.com/mathematical-society-of-traffic-flow/mathematical-society-of-traffic-flow.github.io/raw/refs/heads/main/assets/data/data.zip)
- [The Dome Traffic Jam Experiment](https://github.com/mathematical-society-of-traffic-flow/mathematical-society-of-traffic-flow.github.io/raw/refs/heads/main/assets/data/trajectory.zip)
- [The Arizona Ring Experiments Dataset (ARED)](https://ir.vanderbilt.edu/items/2e6f1c05-0174-4abd-b71c-e7e40eae0ce3)

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

## Mobility Services
- [FleetPy](https://github.com/TUM-VT/FleetPy)
    - Open-Source Fleet Simulation Framework
    - Note: I'm not an expert in this direction but from the README it enables 7 projects! Feel free to comment if you have any suggestions!

## Optimization
- [RL4CO](https://rl4co.readthedocs.io/en/latest/docs/content/intro/environments/)

## Transportation and AI

- [DGMinTransportation](https://github.com/UMN-Choi-Lab/DGMinTransportation) by [UMN-Choi-Lab](https://choi-seongjin.github.io/index.html)
    - Asscociated with paper [A Gentle Introduction and Tutorial on Deep Generative Models in Transportation Research](https://arxiv.org/abs/2410.07066).

### Traffic Prediction via Deep Learning
It is a hot topic in the last decade! There're few lists curated by the community already.

#### Existing lists
- [Deep learning models for traffic prediction](https://github.com/aptx1231/Traffic-Prediction-Open-Code-Summary) by [Jiawei Jiang](https://github.com/aptx1231)

#### Open Benchmarks
- [LibCity](https://libcity.ai/)

## Data Standards in Transportation
- [GTFS and more](https://github.com/MobilityData/awesome-transit)


# Notable Figures in Transportation
- [Dietrich Braess](https://homepage.ruhr-uni-bochum.de/dietrich.braess/#paradox)
    - Braess's Paradox: Adding a road to a network can increase travel time for all users.

## Miscellaneous
This section highlights useful tools and resources that can assist in advancing daily research efforts:
- [Optuna](https://optuna.org/)
    - Optuna is an automatic hyperparameter optimization python framework, particularly designed for machine learning. 
    - Note: This is a tool suggested by [Alex Richardson](https://scholar.google.com/citations?user=BB-pmW0AAAAJ&hl=en) at Vanderbilt University. Thank you, Alex!
- Want to visuliaze how you move in your city? [Here we go!](https://github.com/mikhailsirenko/osmnx-matplotlib-animation)
- Super cool visualization of regional flow data: [Edge-bundling tool for regional mobility flow data](https://zenodo.org/records/14532548).
---
Maintained by [Junyi Ji](https://www.jijunyi.com/), Views are my own.
Last updated: May 2, 2025