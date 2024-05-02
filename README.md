# EM-wave-propogation-through-tissues
In this project, I analysed the passing of electromagnetic (EM) waves through body tissue, which can provide valuable insights and applications in the biomedical field. This area of study, often referred to as bioelectromagnetics, has led to various advances and potential benefits for healthcare and medical research.

This repository contains code and resources for simulating electromagnetic wave propagation in a 3D tissue grid using the Finite Difference Time Domain (FDTD) method. The simulation models the interaction between electromagnetic fields and tissue properties such as conductivity and permittivity.

## Table of Contents

- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The code simulates electromagnetic wave propagation through a 3D grid representing tissue with specific properties such as conductivity and permittivity. The FDTD method is used to update the electric and magnetic fields over time.

Key features of the simulation:
- **Tissue Modeling**: The 3D grid represents a tissue medium with properties such as conductivity (`sigma`) and relative permittivity (`epsilon_r`).
- **Source of Waves**: A Gaussian pulse source is used to initiate the electromagnetic waves at the center of the tissue grid.
- **Field Propagation**: The simulation updates the electric and magnetic fields over time based on Maxwell's equations and tissue properties.
- **Visualization**: The electric field (`Ex`) is visualized at the center slice of the tissue grid.

## Dependencies

- Python 3.x
- NumPy
- Matplotlib

## Usage

To run the simulation:

1. Clone the repository:

    ```shell
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. Install the required Python packages if not already installed:

    ```shell
    pip install numpy matplotlib
    ```

3. Run the simulation script:

    ```shell
    python simulation.py
    ```

This will execute the simulation and display the resulting electric field (`Ex`) at the center slice of the tissue grid.

## Results

The simulation outputs a plot of the electric field (`Ex`) in the tissue at the center slice of the 3D grid. The plot uses a color map to represent the intensity of the electric field and provides insight into the wave propagation through the tissue.

## Contributing

Contributions to this project are welcome. If you have any ideas for improvements, bug fixes, or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE.md).

Thank you for your interest in this project!
