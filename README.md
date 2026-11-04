# Academic Portfolio Website

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-2b547e?style=flat-square&logo=github&logoColor=white)](https://ruyyyyan.github.io/)
[![Built with Jekyll](https://img.shields.io/badge/Built%20with-Jekyll-CC0000?style=flat-square&logo=jekyll&logoColor=white)](https://jekyllrb.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE.md)

This repository contains the source code, assets, and styling for a personal academic portfolio website, hosted on GitHub Pages:

**Live URL**: [https://ruyyyyan.github.io](https://ruyyyyan.github.io/)

---

## Features

- **Jekyll & Liquid Architecture**: Clean, static site generation optimized for academic profiles, publications, and curriculum vitae.
- **Interactive 3D Visitor Globe**: Lightweight HTML5 Canvas 3D globe (`assets/js/visitor-globe.js`) with client-side visitor IP geolocation and visitor traffic counter.
- **Featured Research Showcase**: Responsive multi-panel image carousel for highlighting selected research figures.
- **Modular Publication System**: Markdown-based publication entries supporting DOI links, abstract previews, and citation metadata.
- **Responsive Layout**: Mobile-friendly design with clean typography and custom SCSS styling.

---

## Directory Structure

```text
├── _config.yml               # Site configuration and global settings
├── _pages/                   # Core markdown and HTML pages
│   ├── about.md              # Homepage content
│   ├── cv.md                 # Curriculum vitae
│   └── publications.html     # Publications listing
├── _publications/            # Markdown collection for individual papers
├── assets/
│   ├── css/                  # Custom SCSS / CSS stylesheets
│   └── js/                   # Custom scripts (visitor globe, interactive controls)
├── files/                    # Document downloads and PDFs
└── images/                   # Static images, figures, and icons
```

---

## Local Development

### Prerequisites

- **Ruby** (version 3.0 or higher)
- **Bundler** (`gem install bundler`)
- **Node.js** (for asset pipeline, optional)

### Running Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/ruyyyyan/ruyyyyan.github.io.git
   cd ruyyyyan.github.io
   ```

2. Install Ruby dependencies:
   ```bash
   bundle install
   ```

3. Build and serve the site locally:
   ```bash
   bundle exec jekyll serve -l -H localhost
   ```

4. View the site in your browser at:
   ```
   http://localhost:4000/
   ```

---

## Deployment

The website is automatically built and deployed via GitHub Pages whenever changes are pushed to the `master` branch.

---

## License

This project is licensed under the [MIT License](LICENSE.md). The layout is based on the [Academic Pages](https://academicpages.github.io/) and [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) themes.
