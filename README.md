# Petrophysical Analysis from Well Logs ⛽📊

A Python-based toolkit for analyzing well log data (LAS/CSV) to derive petrophysical properties and identify reservoir-quality zones. Includes data preprocessing, curve standardization, and automated calculation of porosity, water saturation, and shale volume.

---

## Features

* Reads and processes LAS/CSV well log files (`lasio`, `pandas`).
* Quality control: missing value handling, outlier clipping, and unit normalization.
* Calculates porosity (density-neutron), water saturation (Archie’s equation), and Vshale.
* Visualizations of log curves, crossplots, and reservoir intervals.
* Generates concise statistical summaries for reservoir evaluation.

---

## Installation

```bash
# clone the repository
git clone https://github.com/your-username/petrophysical-analysis.git
cd petrophysical-analysis

# install dependencies
pip install -r requirements.txt
```

---

## Usage

```bash
# Run the main script on sample LAS file
python main.py --input sample_data/sample.las --output results/
```

Or explore interactive notebooks in the `notebooks/` folder.

---

## Project Structure

```
petrophysical-analysis/
│── data/               # sample LAS/CSV files
│── notebooks/          # Jupyter notebooks for experiments
│── results/            # generated plots and summaries
│── main.py             # main script for processing
│── requirements.txt    # dependencies
│── README.md           # project documentation
```

---

## Dependencies

* Python 3.8+
* pandas, numpy, matplotlib, seaborn
* lasio
* scipy
