# Ingolstadt Scenario

Adapted from [Multimodal Traffic simulation of Ingolstadt in SUMO](https://github.com/TUM-VT/sumo_ingolstadt) for analyzing robustness of ATCS-RL systems.

## Network File
The `simulation/reduced_net.net.xml` network file represents the Ingolstadt 4x4 scenario in SUMO for running the tests. It is a reduced version of the main network of `simulation/ingolstadt_24h.net.xml.gz` consisting of 59 traffic lights. The traffic flow file is also a reduced version of `simulation/motorized_routes_2020-09-16_24h.rou.xml.gz` and `simulation/bicycle_routes_24h.rou.xml.gz` files. 

## Case Files
Using the Ingolstadt 4x4 network as a base, there are numerous config files representing different traffic conditions. The cases are described in the paper in detail. The configuration files used for cases are described below:

| Cases  | Configuration File Used in the Case |
| ------------- | ------------- |
| Training Case  | `ingo_train.sumocfg`  |
| Case 1 and Case 4  | `ingo_morning.sumocfg`  |
| Case 2  | `ingo_noon.sumocfg`  |
| Case 3  | `ingo_evening.sumocfg`  |
| Case 5 and Case 6  | `ingo_combined.sumocfg`  |

## Notes
If you need furthur details about the experiments, refer to the paper first. If there are still questions left, feel free to ask. I will try my best to answer them.


