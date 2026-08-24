---
layout: home

feature_row:
  - icon: fa fa-flask
    title: Research
    excerpt: Explore our core domains spanning across Optical Coherence Tomography (OCT), Diffractive Optics, and sub-wavelength Metaoptics elements.
    url: /research.html
    btn_label: View details &raquo;
    btn_class: mt-4
    badge:
      - OCT
      - Metaoptics
      - DOEs
    color: primary
    icon_color: default
    badge_color: default
  - icon: fa fa-book
    title: Publications
    excerpt: Read through our latest peer-reviewed journal articles, international conference proceedings, and collaborative textbook outputs.
    url: /publications.html
    btn_label: View details &raquo;
    btn_class: mt-4
    badge:
      - Journals
      - SPIE
      - Optica
    color: primary
    icon_color: default
    badge_color: default
  - icon: fa fa-picture-o
    title: Gallery
    excerpt: Peek inside our specialized experimental laboratory facilities at IIT Madras featuring pneumatically isolated laser setup benches.
    url: /gallery.html
    btn_label: View details &raquo;
    btn_class: mt-4
    badge:
      - Lab Snapshots
      - Setup Media
    color: primary
    icon_color: default
    badge_color: default
---

<!-- Plain Text Title Block (Updated to match dark navy theme color) -->
<div class="container" style="padding-top: 0px; padding-bottom: 20px; margin-top: -300px;">
  <h1 style="color: #1a365d; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 3rem; margin-bottom: 0; text-align : center;">
    Applied Optics Group
  </h1>
  <hr style="border-top: 2px solid #1a365d; margin-top: 0px;">
</div>


<!-- Front Page Showcase Image Slideshow Section (Maximized Width Alignment) -->
<section class="section pt-4 pb-4">
  <div class="container text-center" style="max-width: 100%;">
    <div class="row justify-content-center">
      <!-- UPDATED: Expanded grid columns from col-lg-10 to col-lg-12 for true wide presentation -->
      <div class="col-lg-8.5" style="position: relative;">

        <!-- Slideshow Container Box (Reset max-width to 100% for proper margin calculations) -->
        <div class="slideshow-container" style="position: relative; max-width: 100%; width: 100%; height: 450px; overflow: hidden; border-radius: 8px; box-shadow: 0 4px 15px rgba(0,0,0,0.03);">

          <!-- Slide 1 -->
          <div class="lab-slide fade-anim" style="display: block;">
            <img src="{{ '/assets/img/header-background/home.jpg' | relative_url }}" alt="Applied Optics Lab Showcase 1" style="width: 100%; height: 450px; object-fit: cover;">
          </div>

          <!-- Slide 2 -->
          <div class="lab-slide fade-anim" style="display: none;">
            <img src="{{ '/assets/img/header-background/home_1.png' | relative_url }}" alt="Applied Optics Lab Showcase 2" style="width: 100%; height: 450px; object-fit: cover;">
          </div>

          <!-- Slide 3 -->
          <div class="lab-slide fade-anim" style="display: none;">
            <img src="{{ '/assets/img/header-background/home_2.jpg' | relative_url }}" alt="Applied Optics Lab Showcase 3" style="width: 100%; height: 450px; object-fit: cover;">
          </div>

        </div>

        <!-- Navigation Dots -->
        <div style="text-align:center; margin-top: 15px;">
          <span class="slide-dot active-dot" onclick="currentSlide(1)"></span>
          <span class="slide-dot" onclick="currentSlide(2)"></span>
          <span class="slide-dot" onclick="currentSlide(3)"></span>
        </div>

      </div>
    </div>
  </div>
</section>


<!-- CSS ABSOLUTE OVERRIDE FOR THE VIEW DETAILS BUTTONS AND SLIDESHOW AMINATIONS -->
<style>
  /* --- Slideshow Interactivity Layout Style CSS --- */
  .slide-dot {
    cursor: pointer;
    height: 12px;
    width: 12px;
    margin: 0 5px;
    background-color: #cbd5e1;
    border-radius: 50%;
    display: inline-block;
    transition: background-color 0.3s ease;
  }

  .active-dot, .slide-dot:hover {
    background-color: #1a365d; /* Dark navy focus dot color matches theme */
  }

  /* Crossfade Transition Animation */
  .fade-anim {
    animation-name: slideFade;
    animation-duration: 1s;
  }

  @keyframes slideFade {
    from { opacity: 0.4; }
    to { opacity: 1; }
  }

  /* --- View Details Button CSS --- */
  .container .btn,
  .container .btn--primary,
  .container .mt-4 {
    background-color: #1a365d !important;
    color: #ffffff !important;
    border: 1px solid #1a365d !important;
    border-radius: 20px !important;
    padding: 8px 22px !important;
    font-weight: bold !important;
    text-decoration: none !important;
    display: inline-block !important;
    transition: all 0.2s ease !important;
  }

  .container .btn:hover,
  .container .btn--primary:hover,
  .container .mt-4:hover {
    background-color: #38bdf8 !important;
    color: #1a365d !important;
    border-color: #38bdf8 !important;
    transform: translateY(-1px) !important;
  }

  /* --- Research Focus Option Graphics Grid Styles --- */
  .focus-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    margin-top: 30px;
  }

  .focus-card {
    flex: 1;
    min-width: 260px;
    max-width: 320px;
    background: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.02);
    text-align: left;
    transition: transform 0.3s ease;
  }

  .focus-card:hover {
    transform: translateY(-5px);
  }

  .focus-img-container {
    width: 100%;
    height: 180px;
    overflow: hidden;
  }

  .focus-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }

  .focus-card:hover .focus-img {
    transform: scale(1.08);
  }

  .focus-body {
    padding: 20px;
  }

  .focus-title {
    color: #1a365d;
    font-family: 'Calibri', sans-serif;
    font-weight: bold;
    font-size: 1.3rem;
    margin: 0 0 10px 0;
  }

  .focus-text {
    color: #334155;
    font-size: 14px;
    line-height: 1.5;
    margin: 0;
  }
</style>

<!-- Simple Automated Slideshow Controller JavaScript -->
<script>
  let slideIndex = 0;
  let autoSlideTimeout;
  showSlides();

  // Automated slider rotational cycle
  function showSlides() {
    let i;
    let slides = document.getElementsByClassName("lab-slide");
    let dots = document.getElementsByClassName("slide-dot");

    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) { slideIndex = 1 }    

    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active-dot", "");
    }

    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active-dot";

    // Switch slides every 4 seconds
    autoSlideTimeout = setTimeout(showSlides, 4000);
  }

  // Interactivity click trigger function when dots are tapped manually
  function currentSlide(n) {
    clearTimeout(autoSlideTimeout);
    let i;
    let slides = document.getElementsByClassName("lab-slide");
    let dots = document.getElementsByClassName("slide-dot");

    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active-dot", "");
    }

    slideIndex = n;
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active-dot";

    // Resume cycle rotation rules after interactions
    autoSlideTimeout = setTimeout(showSlides, 4000);
  }
</script>

<!-- Feature Row Section -->
<div class="container" style="margin-top: 220px;">
  {% include feature_row.html %}
</div>

<!-- NEW ADDITION: Research Focus Options with Graphics -->
<section class="section pt-5 pb-5" style="background-color: #081c38; border-top: 0px solid #f1f5f9;">
  <div class="container" style="max-width: 1050px; margin: 0 auto; font-family: 'Calibri', sans-serif;">
    <h2 style="color: #0077b5; font-weight: bold; text-align: center; margin-bottom: 10px; font-size: 2rem;">Research Focus</h2>
    <p style="color: #64748b; text-align: center; max-width: 600px; margin: 0 auto 35px auto; font-size: 16px;">Investigating high-precision optical wave phenomena and structural nanophotonics applications.</p>

    <div class="focus-grid">
      <!-- Focus Card 1 -->
      <div class="focus-card">
        <div class="focus-img-container">
          <img src="{{ '/assets/img/oct_focus.jpg' | relative_url }}" alt="OCT Research" class="focus-img">
        </div>
        <div class="focus-body">
          <h3 class="focus-title">Optical Coherence Tomography</h3>
          <p class="focus-text">Optimizing sub-surface non-invasive diagnostic scanning resolution inside biophotonics structures and cash-crop agricultural cell tissues using advanced SD-OCT signal processing routines.</p>
        </div>
      </div>

      <!-- Focus Card 2 -->
      <div class="focus-card">
        <div class="focus-img-container">
          <img src="{{ '/assets/img/diffractive_focus.jpg' | relative_url }}" alt="Diffractive Optics" class="focus-img">
        </div>
        <div class="focus-body">
          <h3 class="focus-title">Diffractive Optics</h3>
          <p class="focus-text">Modeling, simulation, and micro-mask fabrication of customized diffractive optical elements (DOEs) for custom beam shaping setups and high-contrast light-sheet microscopy engines.</p>
        </div>
      </div>

      <!-- Focus Card 3 -->
      <div class="focus-card">
        <div class="focus-img-container">
          <img src="{{ '/assets/img/metaoptics_focus.jpg' | relative_url }}" alt="Metaoptics" class="focus-img">
        </div>
        <div class="focus-body">
          <h3 class="focus-title">Metaoptics</h3>
          <p class="focus-text">Engineering planar, sub-wavelength flat dielectric metasurface structures utilizing Silicon Nitride resists to produce aberration corrections for compact microendoscopes.</p>
        </div>
      </div>
    </div>
  </div>
</section>
