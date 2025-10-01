# Distribution Network Modeling Framework and Dataset

## Overview
This repository contains a comprehensive framework for modeling and analyzing distribution networks. The framework provides tools and templates for creating realistic low voltage (LV) and medium voltage (MV) distribution system models suitable for various research applications.

## Features and Scope
- **Modular Network Architecture**: Multiple disitribution network models
- **Advanced Cable Modeling**: Multiple cable types with detailed electrical parameters
- **Extensible Framework**: Easy to expand and modify for specific research needs

## Current Implementation
The current model includes:
- **Base Network**: MV/LV transformer with multiple feeders
<!-- - **Feeder Types**: Various configurations demonstrating different network topologies -->
- **Load Profiles**: Residential load modeling with asymmetric three-phase representation
- **Cable Systems**: Standard LV distribution cable specifications

## Usage

For the usage please follow the Readme file within each model folder.

### Extending the Framework
The modular design allows for easy expansion:
- Add new feeder configurations by extending the bus creation patterns
- Implement additional load types and profiles
- Integrate new components (storage, DER, smart devices)
- Customize cable parameters for specific applications
- Develop specialized analysis functions

## Requirements
- Python 3.7+
- PandaPower
- Pandas
- NumPy
- Matplotlib
- SciPy

## Installation
```bash
pip install pandapower pandas numpy matplotlib scipy
```

## Citation
If you use these models in your research, please cite:

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17232114.svg)](https://doi.org/10.5281/zenodo.17232114)

S. Panagi, "Cyprus Distribution Network Models Dataset," Zenodo, 2025. [Online]. Available: https://doi.org/10.5281/zenodo.17232114

## Future Development
This framework is designed to evolve and expand. Planned enhancements include:
- Additional network topologies and configurations
- Advanced load modeling capabilities

## Contributing
Contributions are welcome! Areas for contribution include:
- New network configurations and topologies
- Advanced load and component models
- Analysis and visualization tools
- Documentation and examples
- Testing and validation procedures

## License
This project is provided for research and educational purposes. All location-specific information has been anonymized.

## Contact
For questions, collaboration opportunities, or suggestions for future development, please refer to the author directly or open an issue in this repository.
