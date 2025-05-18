# Optoacoustic Image Quality Dashboard

This project visualizes metric results and reconstructed images from a master's thesis on photoacoustic imaging. Results include metrics like SSIM, VIF, and BRISQUE across different datasets and sampling levels.

The project is structured to allow easy plotting of results and inclusion of sample images for visual comparison. Results are stored in `.txt` format, and image examples in `.png`.

## Structure

- `data/results/`: Metric result `.txt` files
- `data/images/`: Reconstructed image samples (`.png`)
- `notebooks/dashboard.ipynb`: Dashbaord with text and code 
- `pdf/`: Final report or dashboard as LaTeX-generated PDF

## Installation

### Using Conda (Recommended)
```bash
# Create the environment
conda env create -f environment.yml

# Activate the environment
conda activate optoacoustic-dashboard
```

## Dependencies

The project requires the following Python packages:
- pandas
- numpy
- matplotlib
- seaborn
- jupyter
- pillow