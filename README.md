# Yan Peng — Personal Academic Website

<div align="center">

[![Website](https://img.shields.io/badge/Website-ruyyyyan.github.io-2b547e?style=flat-square&logo=googlechrome&logoColor=white)](https://ruyyyyan.github.io/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com.hk/citations?user=hDbhxQ0AAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--5604--7517-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0008-5604-7517)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Yan%20Peng-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Yan-Peng-43?ev=hdr_xprf)
[![GitHub](https://img.shields.io/badge/GitHub-ruyyyyan-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ruyyyyan)

**Ph.D. Student in Theoretical Physics**  
*School of Physical Science and Technology, Soochow University*  
Advisor: [Prof. Bin Xu](https://web.suda.edu.cn/binxu19/index.html) | Master's Advisor: [Prof. Mi Jiang](https://physics.suda.edu.cn/a8/a7/c32869a567463/page.htm)

</div>

---

## Overview

This repository contains the source code, content, and interactive visual components for the personal academic homepage of **Yan Peng**, hosted via GitHub Pages at:

**[https://ruyyyyan.github.io](https://ruyyyyan.github.io/)**

The website serves as an academic portfolio presenting ongoing doctoral research, published manuscripts, curriculum vitae, and customized tools for scientific outreach.

---

## Research Focus

- **Ferroelectric Physics & Superlattices**: Polarization switching mechanisms, PbTiO<sub>3</sub>/SrTiO<sub>3</sub> (PTO/STO) superlattices, and topological polar textures (vortices, skyrmions, and domain walls).
- **Nonlinear Dynamics & Topological Chaos**: Chaotic behaviors, nonlinear bifurcations, and dynamical response in two-dimensional (2D) sliding ferroelectrics and oxide superlattice heterostructures.
- **First-Principles & Effective Hamiltonian Modeling**: Density Functional Theory (DFT), effective Hamiltonian construction, and multiscale computational modeling.
- **Strongly Correlated Electron Systems**: High-T<sub>c</sub> superconductivity, Hubbard/Emery models, and determinant quantum Monte Carlo (DQMC) simulations.

---

## Key Features

1. **Interactive Research Carousel**:
   - High-resolution showcase of recent published work (e.g., *Nature Communications* 2026 on checkerboard-type Zhang-Rice states) with seamless CSS/JS sliding controls.
2. **Real-Time 3D Visitor Globe**:
   - Custom lightweight HTML5 Canvas 3D globe (`assets/js/visitor-globe.js`) featuring real-time client-side visitor IP geolocation and live analytics via edge workers.
3. **Responsive Academic Portfolio**:
   - Publication list with integrated DOI links, BibTeX citations, and publication assets.
   - Comprehensive academic CV detailing education, awards, teaching assistantships, and conferences.
4. **Standard-Compliant Markdown & Jekyll Architecture**:
   - Built on Jekyll and deployed automatically to GitHub Pages.

---

## Repository Structure

```text
ruyyyyan.github.io/
├── _config.yml               # Site-wide settings, metadata, and sidebar bio
├── _pages/                   # Core site pages
│   ├── about.md              # Homepage content (bio, carousel, visitor globe)
│   ├── cv.md                 # Academic CV (education, honors, talks, teaching)
│   └── publications.html     # Publication listing view
├── _publications/            # Markdown collection for individual papers
│   ├── 2026-09-19-checkerboard-type-zhang-rice.md
│   └── ...
├── assets/
│   ├── css/                  # Custom stylesheet overrides
│   └── js/
│       └── visitor-globe.js  # 3D interactive visitor globe & geolocation
├── files/                    # Academic PDFs, supplementary data, and documents
└── images/                   # Figures, campus photography, and profile assets
```

---

## Local Development

To run and preview the site locally:

### Prerequisites
- **Ruby** (>= 3.0) and **Bundler**
- **Node.js** (for asset pipeline)

### Installation & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ruyyyyan/ruyyyyan.github.io.git
   cd ruyyyyan.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Start the Jekyll local server:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:4000/
   ```

---

## License & Acknowledgments

- The website layout is based on the [Academic Pages](https://academicpages.github.io/) / [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) template under the [MIT License](LICENSE.md).
- Original research content, figures, text, and custom visual components are &copy; 2026 Yan Peng.
