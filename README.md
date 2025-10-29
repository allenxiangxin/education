# HEP Education: Simulation and Analysis Techniques

A collection of educational Jupyter notebooks demonstrating common simulation and statistical analysis techniques used in High Energy Physics (HEP) experiments.

## 📚 Contents

### Statistical Methods

#### 1. **Chi-Squared (χ²) Fitting** - `basic_chi2_fitting.ipynb`
Introduction to one of the most fundamental statistical methods in experimental physics. Learn how to:
- Quantify goodness-of-fit between data and models
- Perform parameter estimation using maximum likelihood
- Understand χ² distributions and reduced χ²
- Apply fitting to real-world physics problems

#### 2. **Feldman-Cousins Confidence Intervals** - `feldman_cousins_basics.ipynb`
Implementation of the unified approach for setting confidence intervals in counting experiments. Topics include:
- The problem with classical upper limits and central intervals
- Likelihood ratio ordering principle
- Construction of confidence belts
- Applications to small signal searches and limit setting
- Comparison with traditional methods
- **Reference**: [Feldman & Cousins, Phys. Rev. D 57, 3873 (1998)](https://arxiv.org/abs/physics/9711021)

### Detector Instrumentation

#### 3. **PMT Single Photoelectron (SPE) Distribution Simulator** - `pmt_spe_distribution_simulator.ipynb`
Simulation of photomultiplier tube (PMT) response and gain characteristics:
- Photoelectric effect and secondary emission processes
- Dynode multiplication chain simulation
- SPE charge distribution modeling
- Understanding PMT statistics and noise

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/education.git
   cd education
   ```

2. **Install required packages:**
   ```bash
   pip install -r REQUIREMENTS.txt
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

4. **Open any notebook and run the cells!**

## 📦 Dependencies

All notebooks use standard scientific Python packages:
- NumPy - Numerical computations
- Matplotlib - Plotting and visualization
- SciPy - Scientific functions and statistics

See `REQUIREMENTS.txt` for specific version information.

## 🎓 Learning Path

**Suggested order for beginners:**

1. Start with **Chi-Squared Fitting** to understand basic statistical fitting
2. Try **PMT SPE Simulator** to learn about detector physics
3. Advance to **Feldman-Cousins** for sophisticated limit setting

## 🔬 Applications

These techniques are widely used in:
- **Particle Physics**: LHC experiments (ATLAS, CMS), neutrino experiments
- **Astroparticle Physics**: Dark matter searches, cosmic ray detection
- **Detector Development**: PMT characterization, calibration procedures
- **Data Analysis**: Signal extraction, background estimation, limit setting

## 📖 References

Key papers and resources:
- Feldman & Cousins (1998): Unified approach to confidence intervals
- PDG Statistics Review: [https://pdg.lbl.gov/](https://pdg.lbl.gov/)

## 🤝 Contributing

Contributions are welcome! If you'd like to add new notebooks or improve existing ones:
1. Fork the repository
2. Create a feature branch
3. Add your notebook with clear documentation
4. Submit a pull request

## 📝 License

This project is licensed under the terms specified in the LICENSE file.

## ✨ Acknowledgments

These notebooks were created for educational purposes to help students and researchers learn common HEP analysis techniques. The implementations follow standard practices used in modern particle physics experiments.

---

**Note**: These are educational demonstrations. For production analysis, use established frameworks like ROOT, RooFit, or experiment-specific software.