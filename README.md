
# Marcov Tree Generator

This Python script generates a Marcov tree based on initial values using Vieta's formulas for transformations. It leverages the `anytree` library to create and visualize the tree structure and `graphviz` for exporting the tree structure as a PNG image. The script is designed to demonstrate the application of mathematical transformations in a tree structure up to a specified level of depth.

## Getting Started

These instructions will guide you through setting up the project on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:
- Python 3
- `anytree`
- `graphviz`
- `numpy`
- `PyQt4`
- `lxml`
- `six`

You can install the required Python packages using pip and the system package manager for `PyQt4`:

```bash
pip install anytree graphviz
apt-get install python-numpy python-qt4 python-lxml python-six
```

### Installation

Clone this repository to your local machine to get started with the script:

```bash
git clone https://github.com/your_username/your_project.git
cd your_project
```

No further installation is required.

## Usage

To use this script, simply run it with Python. Ensure you are in the directory containing the script and execute:

```bash
python marc_tree_generator.py
```

This will generate a Marcov tree based on the predefined initial values and output the tree structure to the console. Additionally, it will create a PNG image named `tree.png` representing the tree visually.

### Customizing Tree Generation

You can modify the initial values and the depth of the tree by editing the following lines in the script:

```python
tr = (1, 5, 2)  # Initial values
nmarcov = 8     # Depth of the tree
```

Adjust these values to generate different trees based on your requirements.

## Contributing

Contributions to improve the script or extend its functionalities are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-sourced under the MIT License. See the [LICENSE](LICENSE.md) file for more details.
