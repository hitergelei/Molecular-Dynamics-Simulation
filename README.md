# Supporting materials for my on-going book ***Molecular dynamics simulation***

## Source code and examples in the book

| Chapter  | Language/software  |  Description | Author | Discussed in the book? |
|:---------------|:---------------|:---------------|:---------------|:-------------|
| 1  Classical Physics | Python | [Demonstrating the velocity-Verlet integrator in terms of 1D harmonic oscillator](chapter-01-classical_physics/python-harmonic-oscillator) |  Ke Xu | Yes |
| 2  Simple molecular dynamics | C++ | [A simple MD code without using neighbor list](chapter-02-simple_md/cpp-simpleMD) | Zheyong  Fan | Yes |
| 3  Simulation box and neighbor list | C++ | [A linear-scaling MD code using neighbor list](chapter-03-linear_md/cpp-linearMD) | Zheyong  Fan| Yes |
| 4  Empirical potentials | C++ | [Implemenation and validation of the Tersoff potential](chapter-04-empirical_potentials/cpp-tersoff-validation) | Zheyong  Fan | Yes |
| | GPUMD | [Cross-validate the Tersoff potential between GPUMD and standalone C++](chapter-04-empirical_potentials/gpumd-tersoff) | Zheyong  Fan | Yes |
| 5  Machine-learned potentials | GPUMD | [Train a NEP model for silicon crystal](chapter-05-machine_learned_potentials/gpumd-nep-training-Si) | Zheyong  Fan | Yes |
| 6  Thermostatting methods | Python | [Implementating the Nose-Hoover thermostat in terms of 1D harmonic oscillator](chapter-06-thermostat/nh) | Shuning Pan | Yes |
| | Python | [Implementating the Nose-Hoover chain thermostat in terms of 1D harmonic oscillator](chapter-06-thermostat/nhc) | Shuning Pan | Yes |
| | Python | [Implementating the Langevin thermostat in terms of 1D harmonic oscillator](chapter-06-thermostat/langevin) | Shuning Pan | Yes |
| | GPUMD | [Comparing the thermostats in GPUMD](chapter-06-thermostat/compare_thermostat_speed) | Zheyong  Fan | Yes |
| 7  Barostatting methods | GPUMD | [Demonstrating the usage of the barostatting methods in GPUMD](chapter-07-barostat/npt_examples) | Zheyong  Fan | Yes |
| | GPUMD | [Comparing the barostats in GPUMD](chapter-07-barostat/compare_barostats) | Zheyong  Fan | Yes |
| 8  Static properties | GPUMD | [Demonstrating statistical error](chapter-08-static_properties/GPUMD_statistical_error) | Zheyong  Fan | Yes |
| | GPUMD | [Demonstrating the study of thermal expansion using GPUMD](chapter-08-static_properties/GPUMD_thermal_expansion) | Zheyong  Fan | Yes |
| | GPUMD | [Demonstrating the calculation of RDF of water in GPUMD](chapter-08-static_properties/GPUMD_Water_RDF) | Zekun Chen | Yes |
| | Python | [Calculating RDF from saved trajectory](chapter-08-static_properties/Python_RDF) | Nan Xu | Yes |
| 9 Transport properties | GPUMD | [Calculating self diffusion coefficient of liquid silicon using GPUMD and NEP](chapter-09-transport_properties/GPUMD_silicon_diffusion) | Zheyong  Fan | Yes |
| | GPUMD | [Calculating viscosity of liquid silicon using GPUMD and NEP](chapter-09-transport_properties/GPUMD_silicon_diffusion) | Zheyong  Fan | Yes |
| | GPUMD | [Calculating thermal transport properties of crystalline silicon using GPUMD and NEP](chapter-09-transport_properties/GPUMD_silicon_kappa) | Zheyong  Fan | Yes |
| | C++ | [Standalone MD code calculating self diffusion coefficient](chapter-09-transport_properties/cpp_diffusion_emd_standalone) | Zheyong  Fan | No |
| | C++ | [Standalone MD code calculating thermal conductivity using EMD](chapter-09-transport_properties/cpp_kappa_emd_standalone) | Zheyong  Fan | No |
| | C++ | [Standalone MD code calculating thermal conductivity using HNEMD](chapter-09-transport_properties/cpp_kappa_hnemd_standalone) | Zheyong  Fan | No |
| 10 Path-integral molecular dynamics | GPUMD | [Calculating the radial distribution function of water  using GPUMD and NEP](chapter-10-pimd/GPUMD_Water_RDF) | Zekun Chen | Yes |
| | Python | [A full PIMD code in terms of 1D harmonic oscillator](chapter-10-pimd/Python_PIMD) | Nan Xu | Yes |


## Discussion group for the book
* QQ group: 778083814



