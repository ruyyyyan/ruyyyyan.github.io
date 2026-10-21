---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: center; justify-content: space-between; margin-bottom: 1.5em;">
  <div style="flex: 1 1 360px; min-width: 280px;">
    <p style="margin-top: 0;">I am currently a Ph.D. student majoring in <b>Theoretical Physics</b> at <a href="https://eng.suda.edu.cn/" target="_blank"><b>Soochow University</b></a>.</p>
    <p style="margin-bottom: 0;">My research focuses on computational condensed matter and theoretical physics. During my master's studies, I primarily worked on <b>strongly correlated electron systems</b> and <b>superconductivity physics</b>. For my doctoral research, I focus on <b>ferroelectric physics</b>, employing <b>first-principles (ab initio) calculations</b> and <b>effective Hamiltonian methods</b>. Recently, I have developed a keen interest in exploring <b>chaotic and nonlinear dynamical behaviors in two-dimensional (2D) sliding ferroelectrics</b>.</p>
  </div>
  <div style="flex: 0 1 320px; max-width: 400px; width: 100%; display: flex; flex-direction: column; align-items: center; justify-content: center; margin: 0 auto;">
    <div style="font-size: 0.78em; font-weight: 700; letter-spacing: 0.08em; color: var(--global-text-color-light); text-transform: uppercase; margin-bottom: 8px; text-align: center;">GLOBAL VISITORS</div>
    <script src="https://revolvermaps2.com/embed.js" data-site="pthdsyars8tc" data-size="400" data-theme="blue" data-color="ffb23f" async></script>
  </div>
</div>

---

## Research Interests

- **Ferroelectric Physics & 2D Materials**: Sliding ferroelectricity, polarization switching, inter-layer couplings, and topological / domain wall structures.
- **Nonlinear Dynamics & Chaos**: Chaotic dynamics and nonlinear response in low-dimensional ferroelectric and multistable systems.
- **First-Principles Calculations & Effective Hamiltonian**: Density functional theory (DFT), constructing effective Hamiltonian models, and large-scale atomistic simulations.
- **Strongly Correlated Electron Systems & Superconductivity**: Many-body physics, electronic correlations, and mechanism of unconventional superconductivity.

---

## Featured Research

<div id="featured-research-card" tabindex="0" style="outline: none; margin: 1.5em 0; padding: 1.4em; border: 1px solid var(--global-border-color); border-radius: 12px; background: rgba(0, 0, 0, 0.015); box-shadow: 0 4px 20px rgba(0, 0, 0, 0.04);">
  <div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start;">
    
    <!-- Left: Compact 4-Image Interactive Carousel -->
    <div style="flex: 0 1 310px; width: 100%; max-width: 320px; margin: 0 auto;">
      <!-- Image Viewing Box -->
      <div style="position: relative; width: 100%; height: 215px; display: flex; align-items: center; justify-content: center; background: #ffffff; border-radius: 8px; border: 1px solid rgba(0,0,0,0.08); overflow: hidden; box-shadow: inset 0 0 4px rgba(0,0,0,0.03);">
        
        <div id="feat-slide-0" style="display: block; width: 100%; height: 100%; text-align: center;">
          <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" title="Click to view paper (Fig. 1a)" style="display: flex; width: 100%; height: 100%; align-items: center; justify-content: center;">
            <img src="{{ '/images/featured-fig1a-checkerboard.png' | relative_url }}" alt="Fig. 1a: Checkerboard ZRS Configuration" style="max-height: 205px; max-width: 95%; object-fit: contain; display: block; margin: auto;">
          </a>
        </div>

        <div id="feat-slide-1" style="display: none; width: 100%; height: 100%; text-align: center;">
          <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" title="Click to view paper (Fig. 3e,f)" style="display: flex; width: 100%; height: 100%; align-items: center; justify-content: center;">
            <img src="{{ '/images/featured-fig3ef-zrs-splitting.png' | relative_url }}" alt="Fig. 3e,f: Experimental ZRS Splitting" style="max-height: 205px; max-width: 95%; object-fit: contain; display: block; margin: auto;">
          </a>
        </div>

        <div id="feat-slide-2" style="display: none; width: 100%; height: 100%; text-align: center;">
          <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" title="Click to view paper (Fig. 2e)" style="display: flex; width: 100%; height: 100%; align-items: center; justify-content: center;">
            <img src="{{ '/images/featured-fig2e-xas-peak-a.png' | relative_url }}" alt="Fig. 2e: Emergence of Peak A* in XAS" style="max-height: 205px; max-width: 95%; object-fit: contain; display: block; margin: auto;">
          </a>
        </div>

        <div id="feat-slide-3" style="display: none; width: 100%; height: 100%; text-align: center;">
          <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" title="Click to view paper (Fig. 4b)" style="display: flex; width: 100%; height: 100%; align-items: center; justify-content: center;">
            <img src="{{ '/images/featured-fig4b-dqmc-dos.png' | relative_url }}" alt="Fig. 4b: DQMC Simulated Density of States" style="max-height: 205px; max-width: 95%; object-fit: contain; display: block; margin: auto;">
          </a>
        </div>

        <!-- Navigation Buttons -->
        <button type="button" onclick="changeFeaturedSlide(-1)" aria-label="Previous slide" style="position: absolute; left: 6px; top: 50%; transform: translateY(-50%); width: 28px; height: 28px; border-radius: 50%; border: none; background: rgba(0,0,0,0.45); color: #ffffff; font-size: 14px; font-weight: bold; cursor: pointer; display: flex; align-items: center; justify-content: center; z-index: 2; line-height: 1; transition: background 0.2s;">&#10094;</button>
        <button type="button" onclick="changeFeaturedSlide(1)" aria-label="Next slide" style="position: absolute; right: 6px; top: 50%; transform: translateY(-50%); width: 28px; height: 28px; border-radius: 50%; border: none; background: rgba(0,0,0,0.45); color: #ffffff; font-size: 14px; font-weight: bold; cursor: pointer; display: flex; align-items: center; justify-content: center; z-index: 2; line-height: 1; transition: background 0.2s;">&#10095;</button>

        <!-- Slide Index Counter Badge -->
        <span id="feat-counter" style="position: absolute; top: 6px; right: 6px; background: rgba(0,0,0,0.6); color: #ffffff; font-size: 0.7em; padding: 2px 7px; border-radius: 10px; font-weight: 600; z-index: 2;">1 / 4</span>
      </div>

      <!-- Dot Indicators -->
      <div style="display: flex; justify-content: center; align-items: center; gap: 8px; margin-top: 10px;">
        <button type="button" class="feat-dot" onclick="setFeaturedSlide(0)" title="Fig. 1a: ZRS Configuration" style="width: 9px; height: 9px; border-radius: 50%; border: none; background: #2b547e; cursor: pointer; padding: 0; transform: scale(1.25); transition: all 0.2s;"></button>
        <button type="button" class="feat-dot" onclick="setFeaturedSlide(1)" title="Fig. 3e,f: ZRS Splitting" style="width: 9px; height: 9px; border-radius: 50%; border: none; background: #cccccc; cursor: pointer; padding: 0; transform: scale(1); transition: all 0.2s;"></button>
        <button type="button" class="feat-dot" onclick="setFeaturedSlide(2)" title="Fig. 2e: XAS Peak A*" style="width: 9px; height: 9px; border-radius: 50%; border: none; background: #cccccc; cursor: pointer; padding: 0; transform: scale(1); transition: all 0.2s;"></button>
        <button type="button" class="feat-dot" onclick="setFeaturedSlide(3)" title="Fig. 4b: DQMC DOS" style="width: 9px; height: 9px; border-radius: 50%; border: none; background: #cccccc; cursor: pointer; padding: 0; transform: scale(1); transition: all 0.2s;"></button>
      </div>

      <!-- Dynamic Caption Box -->
      <div style="margin-top: 10px; padding: 8px 12px; background: rgba(0,0,0,0.025); border: 1px solid rgba(0,0,0,0.04); border-radius: 8px; text-align: center; min-height: 68px;">
        <div id="feat-caption-tag" style="font-size: 0.72em; font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; color: #2b547e; margin-bottom: 2px;">
          Theoretical Model
        </div>
        <div id="feat-caption-title" style="font-size: 0.82em; font-weight: 700; color: var(--global-text-color); margin-bottom: 3px;">
          Fig. 1a: Proposed Checkerboard ZRS Configuration
        </div>
        <div id="feat-caption-desc" style="font-size: 0.76em; color: var(--global-text-color-light); line-height: 1.35;">
          Real-space schematic of checkerboard-type Zhang–Rice singlet states within the CuO<sub>2</sub> plane in overdoped LSCO.
        </div>
      </div>
    </div>

    <!-- Right: Paper Information & Interactive Highlights -->
    <div style="flex: 1 1 340px; min-width: 280px;">
      <!-- Badges -->
      <div style="display: flex; gap: 8px; flex-wrap: wrap; align-items: center; margin-bottom: 0.7em;">
        <span style="font-size: 0.76em; font-weight: 700; background: #c0392b; color: #ffffff; padding: 3px 10px; border-radius: 4px; letter-spacing: 0.03em;">Nature Communications</span>
        <span style="font-size: 0.76em; font-weight: 600; background: rgba(0, 122, 255, 0.12); color: #007aff; padding: 3px 9px; border-radius: 4px;">2026</span>
        <span style="font-size: 0.76em; font-weight: 600; background: rgba(52, 199, 89, 0.12); color: #2e7d32; padding: 3px 9px; border-radius: 4px;">Open Access</span>
      </div>

      <!-- Paper Title -->
      <h3 style="margin-top: 0; margin-bottom: 0.4em; font-size: 1.18em; line-height: 1.35;">
        <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" style="color: inherit; text-decoration: none;">Checkerboard-type Zhang-Rice states in overdoped cuprate superconductors</a>
      </h3>

      <!-- Complete 16-Author Citation -->
      <p style="font-size: 0.88em; margin-bottom: 0.75em; color: var(--global-text-color); line-height: 1.45;">
        X. Liu, K. Han, <b>Y. Peng</b>, Y. Ning, J. Wu, Z. Luo, D. Zhou, Z. Zeng, Q. He, C. Cai, M. B. H. Breese, A. Ariando, C. S. Tang, G. A. Sawatzky, M. Jiang, and X. Yin.<br>
        <i>Nature Communications</i>, 2026. DOI: <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank">10.1038/s41467-026-77985-0</a>
      </p>

      <!-- Interactive Key Findings -->
      <div style="margin-bottom: 0.9em;">
        <div id="feat-item-0" onclick="setFeaturedSlide(0)" style="cursor: pointer; padding: 6px 10px; margin-bottom: 5px; border-radius: 6px; border-left: 3px solid #2b547e; background: rgba(43,84,126,0.08); transition: all 0.2s;">
          <div style="font-size: 0.84em; line-height: 1.4; color: var(--global-text-color);">
            <b>Proposed ZRS Configuration (Fig. 1a):</b> Theoretical hypothesis proposing a spontaneous checkerboard-type Zhang–Rice singlet spatial distribution within the CuO<sub>2</sub> plane in heavily overdoped cuprates.
          </div>
        </div>

        <div id="feat-item-1" onclick="setFeaturedSlide(1)" style="cursor: pointer; padding: 6px 10px; margin-bottom: 5px; border-radius: 6px; border-left: 3px solid transparent; background: transparent; transition: all 0.2s;">
          <div style="font-size: 0.84em; line-height: 1.4; color: var(--global-text-color);">
            <b>Experimental ZRS Splitting (Fig. 3e,f):</b> High-resolution spectroscopic evidence demonstrating the breakdown and splitting of the single ZRS band into ZR1 (near <i>E</i><sub>F</sub>) and ZR2 (higher energy) for <i>x</i> &gt; 0.2.
          </div>
        </div>

        <div id="feat-item-2" onclick="setFeaturedSlide(2)" style="cursor: pointer; padding: 6px 10px; margin-bottom: 5px; border-radius: 6px; border-left: 3px solid transparent; background: transparent; transition: all 0.2s;">
          <div style="font-size: 0.84em; line-height: 1.4; color: var(--global-text-color);">
            <b>Emergent Peak A* in XAS (Fig. 2e):</b> Spectral fitting of in-plane O <i>K</i>-edge XAS providing unambiguous evidence for the distinct emergent peak A* (~527.8 eV) alongside peak A.
          </div>
        </div>

        <div id="feat-item-3" onclick="setFeaturedSlide(3)" style="cursor: pointer; padding: 6px 10px; margin-bottom: 6px; border-radius: 6px; border-left: 3px solid transparent; background: transparent; transition: all 0.2s;">
          <div style="font-size: 0.84em; line-height: 1.4; color: var(--global-text-color);">
            <b>DQMC Simulation Agreement (Fig. 4b):</b> Determinant Quantum Monte Carlo calculations on the three-orbital Emery model exhibiting consistent splitting of the ZRS peak in simulated density of states (DOS) across <i>p</i><sub>h</sub> = 0.1–0.6.
          </div>
        </div>
      </div>

      <!-- Tags & Action Buttons -->
      <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 10px; padding-top: 0.8em; border-top: 1px dashed var(--global-border-color);">
        <div style="display: flex; gap: 6px; flex-wrap: wrap;">
          <span style="font-size: 0.72em; background: rgba(0,0,0,0.04); color: var(--global-text-color-light); padding: 2px 7px; border-radius: 4px;">#Cuprates</span>
          <span style="font-size: 0.72em; background: rgba(0,0,0,0.04); color: var(--global-text-color-light); padding: 2px 7px; border-radius: 4px;">#Superconductivity</span>
          <span style="font-size: 0.72em; background: rgba(0,0,0,0.04); color: var(--global-text-color-light); padding: 2px 7px; border-radius: 4px;">#Zhang-Rice Singlet</span>
          <span style="font-size: 0.72em; background: rgba(0,0,0,0.04); color: var(--global-text-color-light); padding: 2px 7px; border-radius: 4px;">#DQMC</span>
        </div>
        <div style="display: flex; gap: 8px; flex-wrap: wrap;">
          <a href="https://doi.org/10.1038/s41467-026-77985-0" target="_blank" style="display: inline-flex; align-items: center; gap: 5px; padding: 5px 12px; font-size: 0.82em; font-weight: 600; color: #ffffff; background: #2b547e; border-radius: 5px; text-decoration: none;">
            <span>Read Paper (DOI)</span>
            <svg width="11" height="11" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"></path><polyline points="15 3 21 3 21 9"></polyline><line x1="10" y1="14" x2="21" y2="3"></line></svg>
          </a>
          <a href="https://arxiv.org/abs/2512.09547" target="_blank" style="display: inline-flex; align-items: center; gap: 5px; padding: 5px 12px; font-size: 0.82em; font-weight: 600; color: #b31b1b; background: rgba(179,27,27,0.1); border-radius: 5px; text-decoration: none;">
            <span>arXiv:2512.09547</span>
          </a>
        </div>
      </div>

    </div>

  </div>
</div>

<script>
(function() {
  var slides = [
    {
      imgId: 'feat-slide-0',
      tag: 'Theoretical Model',
      title: 'Fig. 1a: Proposed Checkerboard ZRS Configuration',
      desc: 'Real-space schematic of checkerboard-type Zhang–Rice singlet states within the CuO<sub>2</sub> plane in overdoped LSCO.'
    },
    {
      imgId: 'feat-slide-1',
      tag: 'Experimental Observation',
      title: 'Fig. 3e,f: Experimental ZRS Splitting',
      desc: 'Spectroscopic evidence showing the breakdown and splitting of the single ZRS band into ZR1 and ZR2 states for <i>x</i> &gt; 0.2.'
    },
    {
      imgId: 'feat-slide-2',
      tag: 'X-ray Spectroscopy',
      title: 'Fig. 2e: Emergence of Distinct New Peak A* in XAS',
      desc: 'Spectral fitting of in-plane O <i>K</i>-edge XAS definitively demonstrating the emergence and rapid growth of new peak A*.'
    },
    {
      imgId: 'feat-slide-3',
      tag: 'DQMC Simulation',
      title: 'Fig. 4b: DQMC Simulated Density of States (DOS)',
      desc: 'Determinant Quantum Monte Carlo simulations on the three-orbital Emery model reproducing the ZRS splitting trend across <i>p</i><sub>h</sub> = 0.1–0.6.'
    }
  ];

  var currentIndex = 0;

  function updateCarousel(index) {
    if (index < 0) index = slides.length - 1;
    if (index >= slides.length) index = 0;
    currentIndex = index;

    for (var i = 0; i < slides.length; i++) {
      var slideEl = document.getElementById(slides[i].imgId);
      if (slideEl) {
        slideEl.style.display = (i === currentIndex) ? 'block' : 'none';
      }
    }

    var counterEl = document.getElementById('feat-counter');
    if (counterEl) counterEl.textContent = (currentIndex + 1) + ' / ' + slides.length;

    var tagEl = document.getElementById('feat-caption-tag');
    var titleEl = document.getElementById('feat-caption-title');
    var descEl = document.getElementById('feat-caption-desc');
    if (tagEl) tagEl.textContent = slides[currentIndex].tag;
    if (titleEl) titleEl.innerHTML = slides[currentIndex].title;
    if (descEl) descEl.innerHTML = slides[currentIndex].desc;

    var dots = document.querySelectorAll('.feat-dot');
    for (var d = 0; d < dots.length; d++) {
      dots[d].style.background = (d === currentIndex) ? '#2b547e' : '#cccccc';
      dots[d].style.transform = (d === currentIndex) ? 'scale(1.25)' : 'scale(1)';
    }

    for (var k = 0; k < slides.length; k++) {
      var itemEl = document.getElementById('feat-item-' + k);
      if (itemEl) {
        if (k === currentIndex) {
          itemEl.style.borderLeft = '3px solid #2b547e';
          itemEl.style.background = 'rgba(43, 84, 126, 0.08)';
        } else {
          itemEl.style.borderLeft = '3px solid transparent';
          itemEl.style.background = 'transparent';
        }
      }
    }
  }

  window.setFeaturedSlide = function(index) {
    updateCarousel(index);
  };

  window.changeFeaturedSlide = function(step) {
    updateCarousel(currentIndex + step);
  };

  var card = document.getElementById('featured-research-card');
  if (card) {
    card.addEventListener('keydown', function(e) {
      if (e.key === 'ArrowLeft') {
        updateCarousel(currentIndex - 1);
      } else if (e.key === 'ArrowRight') {
        updateCarousel(currentIndex + 1);
      }
    });
  }
})();
</script>

---

## Education & Research Experience

- **Ph.D. in Theoretical Physics** | Soochow University, *2026 – Present*
  - *Advisor*: [Prof. Bin Xu](https://web.suda.edu.cn/binxu19/index.html)
  - *Research Focus*: Ferroelectric physics, first-principles calculations, effective Hamiltonian methods, and nonlinear / chaotic dynamics in 2D sliding ferroelectrics.
- **M.S. in Theoretical Physics** | Soochow University, *2024 – 2026*
  - *Advisor*: [Prof. Mi Jiang](https://web.suda.edu.cn/jm/)
  - *Research Focus*: Strongly correlated electron systems and superconductivity physics.
- **B.S. in Physics** | Soochow University, *2020 – 2024*
- *(Academic genealogy: [Academic Tree](https://academictree.org/physics/tree.php?pid=980247&fontsize=1&pnodecount=4&cnodecount=2))*

---

## Honors & Awards

- **National Scholarship for Graduate Students**, Ministry of Education of China, 2025

---

## Teaching Experience

- **Teaching Assistant**, Soochow University
  - *Quantum Mechanics*, Fall semester, 2024 – 2025 (2 sections)
  - *Electrodynamics*, Spring semester, 2024 – 2025 (2 sections)

---

## Professional Memberships

- **Student Member**, [Chinese Physical Society (CPS)](https://www.cps-net.org.cn/home/index/index_en.do)

---

## News & Updates

- **[Recent]** Exploring nonlinear dynamics and chaotic behaviors in 2D sliding ferroelectrics.
- **[2025]** Awarded the **National Scholarship for Graduate Students**, Ministry of Education of China.
