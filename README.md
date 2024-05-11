# Tool to evaluate and visualize energy consumption

## Installation

It's recommend to set up a virtual python environment.

MacOS
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies
```bash
pip install -r requriements.txt
```

## Usage
Obtain usage csv files and store them in the `./data` directory.
Expected file structure for `./data`:
```
./data
├── 2023_11
│   ├── gasverbrauch.csv
│   └── stromverbrauch.csv
├── 2023_12
│   ├── gasverbrauch.csv
│   └── stromverbrauch.csv
├── 2024_01
│   ├── gasverbrauch.csv
│   └── stromverbrauch.csv
```

Open `evaluation.ipynb` with a python notebook tool like Jupyter or VSCode and select the environment with the previously installed dependencies as kernel.

Run notebook. To evalute the power consumption, make sure to run the power consumption data loading block (Block 2) and skip running the gas consompution data loading block (Block 3) and vice versa.