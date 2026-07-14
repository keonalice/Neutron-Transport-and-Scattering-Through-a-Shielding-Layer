# Neutron Transport and Scattering Through a Shielding Layer

A Jupyter Notebook project that models neutron transport through a shielding material, examining how neutron attenuation and scattering influence particle transmission. The notebook demonstrates the underlying physics of neutron interactions with matter using computational methods and data visualisation.

## Overview

Neutron shielding is an important aspect of nuclear engineering, radiation protection, and reactor design. Unlike charged particles, neutrons interact primarily through nuclear collisions, making their behaviour highly dependent on the properties of the shielding material.

This project investigates:

- Neutron attenuation through a shielding layer
- Scattering and transmission probabilities
- The effect of shielding thickness on neutron flux
- Visualisation of neutron transport behaviour

The implementation is provided as an interactive Jupyter Notebook, allowing users to explore calculations, modify parameters, and reproduce the results.

## Features

- Physics-based neutron transport calculations
- Configurable shielding parameters
- Interactive plots and visualisations
- Well-documented computational workflow
- Suitable for teaching and research demonstrations

## Repository Structure

```
.
├── notebook.ipynb      # Main Jupyter Notebook
└── README.md           # Project documentation
```

## Requirements

The notebook requires Python 3 and the following packages:

- numpy
- matplotlib
- scipy (if used)

Install the dependencies with:

```bash
pip install numpy matplotlib scipy jupyter
```

## Running the Notebook

1. Clone the repository

```bash
git clone https://github.com/keonalice/Neutron-Transport-and-Scattering-Through-a-Shielding-Layer.git
```

2. Navigate to the project directory

```bash
cd Neutron-Transport-and-Scattering-Through-a-Shielding-Layer
```

3. Launch Jupyter Notebook

```bash
jupyter notebook
```

4. Open `notebook.ipynb` and run the cells sequentially.

## Scientific Background

Neutron transport describes the movement and interaction of neutrons as they travel through matter. Depending on the material, neutrons may:

- Pass through without interaction
- Scatter elastically or inelastically
- Be absorbed by nuclei

Understanding these interactions is fundamental in:

- Nuclear reactor design
- Radiation shielding
- Medical physics
- Particle transport simulations

## Results

The notebook generates figures illustrating how neutron intensity changes as a function of shielding parameters. These visualisations help demonstrate the relationship between material properties, scattering behaviour, and neutron attenuation.

## Future Improvements

Potential extensions include:

- Multi-layer shielding materials
- Energy-dependent neutron cross sections
- Monte Carlo neutron transport simulations
- Comparison with analytical transport models
- Validation against experimental or benchmark data

## References

- Duderstadt, J. J., & Hamilton, L. J. *Nuclear Reactor Analysis.*
- Lewis, E. E., & Miller, W. F. *Computational Methods of Neutron Transport.*
- Bell, G. I., & Glasstone, S. *Nuclear Reactor Theory.*

## Author

**Keon Alice**

GitHub: https://github.com/keonalice

## License

This project is intended for educational and research purposes.
