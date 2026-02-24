# SDSS DR18: Exploratory data analysis
### Analyzing 100,000 astronomical objects with Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Complete-success" />
</p>

---

## About the project

Exploratory analysis of the **Sloan Digital Sky Survey Data Release 18**, a dataset containing spectroscopic and photometric data from 100,000 astronomical objects.

**Goal:** Identify spectral patterns that distinguish between galaxies, stars, and quasars using statistical analysis and data visualization.

---

## Key findings

| Object type | Population | UV outliers (%) | Interpretation |
|------------|------------|-----------------|----------------|
| **Galaxies** | 52,207 (52.2%) | 0.20% | Stable spectral signatures due to averaging effect |
| **Stars** | 37,192 (37.2%) | 7.47% | High variability from nuclear fusion processes |
| **Quasars** | 10,414 (10.4%) | 6.51% | Extreme energetic events from supermassive black holes |

**Main conclusion:** The UV signature (u-g color index) works as an excellent discriminator for classifying astronomical objects. Stars show 37× more outliers than galaxies.

---

## Tech stack
```python
Python 3.13
├── pandas        # Data manipulation
├── numpy         # Numerical computing
├── matplotlib    # Static visualizations
└── seaborn       # Statistical plots
```

**Dataset:** SDSS DR18 (100,000 objects × 43 features)  
**Analysis type:** EDA  
**Techniques:** Outlier detection, correlation analysis, distribution fitting

---

## How to run it
```bash
# Clone repository
git clone https://github.com/mramoscoding/EDA-Sloan-Digital-Sky-Survey-DR18.git
cd EDA-Sloan-Digital-Sky-Survey-DR18

# Install dependencies
pip install -r requirements.txt

# Download dataset
# Place SDSS_DR18.csv in the project root

# Run notebook
jupyter notebook SDSS_dr18.ipynb
```

---

## Project structure
```
EDA-Sloan-Digital-Sky-Survey-DR18/
├── SDSS_dr18.ipynb       # Main analysis notebook
├── requirements.txt       # Python dependencies
├── README.md             # This file
└── .gitignore            # Git rules
```

---

## What I analyzed

### General data
- 100,000 astronomical objects across 3 classes
- 43 features including spectral magnitudes, coordinates, and redshift
- Zero missing values, some "9999" treated as NAs

### Main variables
- **Photometric filters:** u, g, r, i, z (ultraviolet to near-infrared)
- **Color indices:** u-g (UV signature), g-r, r-i
- **Redshift:** Cosmological distance indicator
- **Petrosian metrics:** Galaxy morphology parameters

### Statistical methods
- Correlation analysis between spectral bands
- Outlier detection using IQR method
- Distribution analysis by object class
- Comparative statistics across populations

---

## What I learned

- **Physics:** Deepened my understanding of spectroscopy, redshift, and cosmic object classification
- **Statistics:** Analytical, logical and mathematical methods for outlier detection and correlation analysis on astronomical data
- **Communication:** Translated complex astrophysics concepts into clear insights
- **Python:** Advanced use of Pandas and Seaborn for large dataset analysis
- **Interdisciplinarity:** Combined physics knowledge with data science techniques

---

## Why this project stands out

- Combines physics knowledge with data science techniques
- 100K+ observations analyzed with robust statistical methods
- Interpretations grounded in the physics of the objects, not just charts
- Clear documentation accessible to non-astronomers
- Applies statistical rigor learned in master's program

---

## Dataset

Analysis based on the **SDSS DR18** dataset.

**Source:** [Sloan Digital Sky Survey DR18 (Kaggle)](https://www.kaggle.com/datasets/diraf0/sloan-digital-sky-survey-dr18)

**Note:** The dataset is not included in this repository due to its size. Download it directly from SDSS and place `SDSS_DR18.csv` in the project root.

---

## About me

**Manuel Ramos Alascio**  
Data Science & Business Analytics student 

- Master's in Data Science @ IMF Smart School (Madrid)
- Professional Services intern @ Celonis
- Background: Business Administration (Universidad de Granada)
- Passionate about applying data science to understand the human world and the universe

**Connect with me:**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manuel-ramos-alascio-7b52a8188/)

---

## Acknowledgments

- **Dataset:** Sloan Digital Sky Survey (SDSS) Collaboration
- **Academic program:** IMF Smart School - Data Science & Business Analytics
- **Motivation:** Combining my passion for physics with data science

---

<p align="center">
  <i>If you found this interesting, consider giving it a ⭐</i>
</p>


