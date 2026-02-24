# SDSS DR18: Exploratory Data Analysis
### Analyzing 100,000 Cosmic Objects with Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Complete-success" />
  <img src="https://img.shields.io/badge/Objects-100K-orange" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 📖 About This Project

This project explores the **Sloan Digital Sky Survey Data Release 18 (SDSS DR18)**, containing spectroscopic and photometric data from 100,000 astronomical objects.

**Goal:** Identify spectral patterns that distinguish galaxies, stars, and quasars using statistical analysis and data visualization techniques.

**Why it matters:** Understanding cosmic object classification is fundamental for large-scale astronomical surveys and helps reveal the structure and evolution of our universe.

---

## 🎯 Key Findings

| Object Type | Population | UV Outliers (%) | Interpretation |
|------------|------------|-----------------|----------------|
| **Galaxies** | 52,207 (52.2%) | 0.20% | Stable spectral signatures due to statistical averaging |
| **Stars** | 37,192 (37.2%) | 7.47% | High variability from nuclear fusion processes |
| **Quasars** | 10,414 (10.4%) | 6.51% | Extreme energetic events from supermassive black holes |

**Main Insight:** The UV signature (u-g color index) serves as an excellent discriminator for astronomical object classification, with stars showing 37× more outliers than galaxies.

---

## 🔬 Technical Stack
```python
Python 3.13
├── pandas        # Data manipulation and analysis
├── numpy         # Numerical computing
├── matplotlib    # Static visualizations
└── seaborn       # Statistical data visualization
```

**Dataset:** SDSS DR18 (100,000 objects × 43 features)  
**Analysis Type:** Exploratory Data Analysis (EDA)  
**Techniques:** Outlier detection, correlation analysis, distribution fitting

---

## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/YOUR-USERNAME/sdss-eda.git
cd sdss-eda

# Install dependencies
pip install -r requirements.txt

# Download dataset
# Place SDSS_DR18.csv in the project root (not included due to size)

# Run notebook
jupyter notebook SDSS_dr18.ipynb
```

---

## 📁 Project Structure
```
sdss-eda/
├── SDSS_dr18.ipynb       # Main analysis notebook with EDA
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation (this file)
└── .gitignore            # Git ignore rules
```

---

## 📊 Analysis Highlights

### Data Overview
- **100,000 astronomical objects** across three classes
- **43 features** including spectral magnitudes, coordinates, and redshift
- **Zero missing values** - clean, production-ready dataset

### Key Variables Analyzed
- **Photometric filters:** u, g, r, i, z (ultraviolet to near-infrared)
- **Color indices:** u-g (UV signature), g-r, r-i
- **Redshift:** Cosmological distance indicator
- **Petrosian metrics:** Galaxy morphology parameters

### Statistical Methods
- Correlation analysis between spectral bands
- Outlier detection using IQR method
- Distribution analysis by object class
- Comparative statistics across populations

---

## 📚 What I Learned

- **Domain Knowledge:** Deepened understanding of spectroscopy, redshift, and cosmic object classification
- **Statistical Techniques:** Applied robust methods for outlier detection and correlation analysis on astronomical data
- **Data Storytelling:** Translated complex astrophysics concepts into clear, actionable insights
- **Python Libraries:** Advanced usage of Pandas and Seaborn for large-scale dataset analysis
- **Physics + Data Science:** Combined domain expertise in physics with data analysis skills

---

## 🌟 Why This Project Stands Out

- ✨ **Domain Expertise:** Combines physics knowledge with data science techniques
- 📊 **Scale:** 100K+ observations analyzed with robust statistical methods
- 🔍 **Insight-Driven:** Physically-grounded interpretations, not just visualizations
- 📝 **Documentation:** Clear explanations accessible to non-astronomers
- 🎓 **Academic Rigor:** Applied statistical methods learned in Master's program

---

## 📦 Dataset

This analysis uses the **SDSS DR18** dataset.

**Source:** [Sloan Digital Sky Survey](https://www.sdss.org/dr18/)

**Note:** The dataset is not included in this repository due to size constraints. Please download it directly from SDSS and place `SDSS_DR18.csv` in the project root directory.

---

## 👤 About Me

**Manuel Ramos Alascio**  
Data Science & Business Analytics Student | Physics Enthusiast

- 🎓 Master's in Data Science @ IMF Smart School (Madrid)
- 💼 Professional Services Intern @ Celonis
- 🔬 Background: Business Administration (Universidad de Granada)
- 🔭 Passionate about applying data science to understand the physical universe

**Connect with me:**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-PROFILE)

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🙏 Acknowledgments

- **Dataset:** Sloan Digital Sky Survey (SDSS) Collaboration
- **Academic Program:** IMF Smart School - Data Science & Business Analytics
- **Course Module:** Statistics and Data Visualization (Module 3)
- **Inspiration:** Combining my passion for physics with emerging data science skills

---

<p align="center">
  <i>If you found this project interesting, please consider giving it a ⭐</i>
</p>

<p align="center">
  <sub>Created with passion for understanding the cosmos through data | December 2025 - January 2026</sub>
</p>