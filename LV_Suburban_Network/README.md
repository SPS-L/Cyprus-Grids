# Suburban LV Networks

## Network 1 

Network 1 is a low voltage (LV) suburban distribution network with the following characteristics:

- **Transformer Capacity**: 315 kVA
- **Configuration**: Three feeders
- **Analysis Type**: Unbalanced network requiring full three-phase analysis
- **Network Type**: Low voltage distribution network

The unbalanced nature of this network means that all three phases must be considered separately during power flow analysis, as the loads and network configuration are not symmetric across the three phases.

### Basic Usage
1. Open the `Network.ipynb` notebook
2. Run all cells to create the base network model
3. Use PandaPower functions for power flow analysis:
   ```python
   pp.runpp(net)
   ```

### Implementations and Publications

If you are interested in seeing analyses conducted using this network, please refer to the following open-access papers:

[1] S. Panagi, P. Therapontos, C. Spanias, P. Aristidou., "Optimal Operation of Electric Vehicles to Enhance the Flexibility Provision in Active Distribution Grids," *PowerTech Kiel*, 2025. [Online]. Available: https://sps.cut.ac.cy/publication/2025cpanagi/2025CPanagi.pdf

[2] S. Panagi, P. Therapontos, C. Spanias, P. Aristidou., "Impact of Uncontrolled Electric Vehicle Charging on Unbalanced Suburban Low-Voltage Networks," *ISGT Malta*, 2025. [Online]. Available: https://sps.cut.ac.cy/publication/2025cpanagib/2025CPanagiB.pdf