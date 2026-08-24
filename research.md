---
layout: single
title: "Key Research Areas"
---

<!-- Plain Text Title Block (Centered) -->
<div class="container" style="padding-top: 20px; padding-bottom: 20px; text-align: center;">
  <h1 style="color: #1a365d; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 3rem; margin-bottom: 0;">
    Research Interests
  </h1>
  <hr style="border-top: 2px solid #1a365d; margin: 15px auto 0 auto; width: 50%;">
  <p style="color: #475569; font-family: 'Calibri', sans-serif; font-size: 1.2rem; margin-top: 15px; margin-bottom: 0;">
    Advancing the fundamental principles and applications of micro-optics and biophotonics systems.
  </p>
</div>

<!-- CSS Styling for Research Content Grid -->
<style>
  .research-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 0;
    font-family: 'Calibri', sans-serif;
  }

  .topic-card {
    background: #f8fafc; /* Sleek light mode panel card */
    border: 1px solid #e2e8f0;
    border-left: 5px solid #1a365d; /* Dark blue brand accent border stripe */
    border-radius: 8px;
    padding: 30px;
    margin-bottom: 35px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.02);
    display: flex;
    gap: 25px;
    align-items: flex-start;
    flex-wrap: wrap; /* Safe stacking on mobile screens */
  }

  .topic-icon-box {
    background-color: #1a365d;
    color: #ffffff;
    width: 60px;
    height: 60px;
    border-radius: 8px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    flex-shrink: 0;
    box-shadow: 0 4px 10px rgba(26, 54, 147, 0.15);
  }

  .topic-content {
    flex: 1;
    min-width: 280px;
  }

  .topic-title {
    color: #1a365d;
    font-size: 1.6rem;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 12px;
  }

  .topic-text {
    color: #334155;
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 15px;
  }

  /* Sub-bullet points inside research cards */
  .focus-list {
    list-style: none;
    padding-left: 0;
    margin: 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 10px;
  }

  .focus-item {
    font-size: 14px;
    color: #475569;
    font-weight: 500;
    display: flex;
    align-items: center;
  }

  .focus-item i {
    color: #38bdf8; /* Cyan bullet indicator */
    margin-right: 8px;
    font-size: 0.8rem;
  }
</style>

<div class="container">
  <div class="research-container">

    <!-- TOPIC 1: OPTICAL COHERENCE TOMOGRAPHY (OCT) -->
    <div class="topic-card">
      <div class="topic-icon-box">
        <i class="fa fa-search"></i>
      </div>
      <div class="topic-content">
        <h2 class="topic-title">Optical Coherence Tomography (OCT)</h2>
        <p class="topic-text">
          Our group focuses on signal processing optimization and microstructural imaging using Spectral Domain OCT (SD-OCT). We develop innovative methods utilizing Wigner-Ville techniques and signal distributions to enhance spatial resolution thresholds. Our applied fields span across non-destructive post-harvest agricultural testing and advanced biophotonics diagnostics.
        </p>
        <ul class="focus-list">
          <li class="focus-item"><i class="fa fa-circle"></i> SD-OCT Signal Processing</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Wigner-Ville Distribution</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Agricultural Sub-peel Imaging</li>
          <li class="focus-item"><i class="fa fa-circle"></i> High-Resolution A-Scans</li>
        </ul>
      </div>
    </div>

    <!-- TOPIC 2: DIFFRACTIVE OPTICS -->
    <div class="topic-card">
      <div class="topic-icon-box">
        <i class="fa fa-flask"></i>
      </div>
      <div class="topic-content">
        <h2 class="topic-title">Diffractive Optics</h2>
        <p class="topic-text">
          We specialize in the design, numerical simulation, and fabrication of advanced diffractive optical elements (DOEs). This research involves beam shaping setups, structural illumination profiles, and engineering sidelobe-suppressed modified Bessel beams. These custom optics components directly drive breakthroughs in light-sheet microscopy platforms.
        </p>
        <ul class="focus-list">
          <li class="focus-item"><i class="fa fa-circle"></i> Beam Shaping Optic Design</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Modified Bessel Beams</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Light-Sheet Microscopy</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Diffractive Element Masking</li>
        </ul>
      </div>
    </div>

    <!-- TOPIC 3: METAOPTICS -->
    <div class="topic-card">
      <div class="topic-icon-box">
        <i class="fa fa-th"></i>
      </div>
      <div class="topic-content">
        <h2 class="topic-title">Metaoptics</h2>
        <p class="topic-text">
          Our metaoptics vertical explores flat, ultra-compact dielectric metasurfaces engineered using sub-wavelength Silicon Nitride structures. We leverage electron-beam lithography (EBL) techniques to fabricate planar elements tailored for aberration corrections in highly portable medical devices, such as scanning fiber fluorescence microendoscopes.
        </p>
        <ul class="focus-list">
          <li class="focus-item"><i class="fa fa-circle"></i> Dielectric Metasurfaces</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Silicon Nitride Nanofabrication</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Microendoscopy Endoscopy</li>
          <li class="focus-item"><i class="fa fa-circle"></i> Wavefront Aberration Fixes</li>
        </ul>
      </div>
    </div>

  </div>
</div>
