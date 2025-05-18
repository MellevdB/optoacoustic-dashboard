# Optoacoustic Image Quality Dashboard

This project visualizes image quality assessment (IQA) results and reconstructed images from a master's thesis on photoacoustic (optoacoustic) imaging. It provides both qualitative and quantitative comparisons of image reconstructions generated under different sensor configurations and sampling levels.

Metrics such as SSIM, VIF, BRISQUE, PSNR, and CLIP-IQA are evaluated across multiple biomedical datasets (e.g., KneeSlice, Phantom, SmallAnimal). The dashboard allows for:
- Line plots showing metric trends across configurations
- Image grids visualizing reconstruction quality (PA1 to PA7)
- Correlation matrices between IQA metrics
- Radar charts summarizing overall performance

---

##  Project Structure

```text
data/
├── results/           # Per-dataset IQA results (.txt)
├── images/            # Reconstructed image snapshots (PA1 to PA7)

notebooks/
└── dashboard.ipynb    # Code + narrative for generating the visualizations

pdf/
└── final_report.pdf   # Exported LaTeX-based PDF with all results and discussion

environment.yml        # Conda environment file
README.md              # This file

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