# ECE 105 Lab 3: Sensor Data Visualization

A Python script that generates synthetic temperature sensor data and produces publication-quality scatter, histogram, and box plot visualizations using matplotlib.

## Installation

Activate the ece105 conda environment and install the required dependencies:

```bash
conda activate ece105
conda install numpy matplotlib
```

## Usage

Run the script from the project root:

```bash
python generate_plots.py
```

## Example Output

The script produces `sensor_analysis.png`, a 1×3 figure containing:

1. **Sensor Readings Over Time** — a scatter plot showing temperature readings from Sensor A (blue) and Sensor B (orange) across a 10-second window.
2. **Temperature Distributions** — overlapping histograms of both sensors, with dashed vertical lines marking each sensor's mean temperature.
3. **Distribution Comparison** — side-by-side box plots of both sensors, with a red dashed line indicating the overall mean temperature across both sensors.

## AI Tools Used and Disclosure

This project was developed with assistance from Claude (Anthropic) as part of ECE 105's AI-assisted development exercises. Claude was used to help structure the NumPy-style docstrings, debug a matplotlib deprecation warning (`labels` → `tick_labels`), and guide the Git/GitHub workflow including repository setup, authentication, and commit practices. All code was reviewed and tested by the author before committing.