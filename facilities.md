---
layout: single
---

<!-- Plain Text Title Block -->
<div class="container" style="padding-top: 0px; padding-bottom: 20px; margin-top: -100px; text-align: center;">
  <h1 style="color: #36454f; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 3rem; margin-bottom: 0;">
    Facilities
  </h1>
  <hr style="border-top: 2px solid #1a365d; margin: 15px auto 0 auto; width: 50%;">
</div>

<!-- CSS Styles for Hover Overlay Effects & Added Elements -->
<style>
  .instruments-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px; /* Reduced gap slightly for smaller cards */
    padding: 20px 0;
  }

  .instrument-card {
    position: relative;
    flex: 1;
    min-width: 180px; /* Reduced from 280px to make icons much smaller */
    max-width: 210px; /* Reduced from 350px to make icons much smaller */
    height: 160px;    /* Reduced from 250px to make icons much smaller */
    border-radius: 6px;
    overflow: hidden;
    background-color: #ffffff;
    border: 1px solid #222222;
    box-shadow: 0 4px 15px rgba(255, 255, 255, 0.05);
  }

  /* The Instrument Image */
  .instrument-img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }

  /* Zoom effect on image during hover */
  .instrument-card:hover .instrument-img {
    transform: scale(1.1);
  }

  /* Hidden Overlay Box Container */
  .instrument-overlay {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: rgba(26, 54, 93, 0.95); /* Deep navy blue transparency matching your brand */
    overflow: hidden;
    width: 100%;
    height: 0; /* Hidden by default */
    transition: height 0.4s ease;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 0 15px;
    text-align: center;
    box-sizing: border-box;
  }

  /* Reveal Overlay on Card Hover */
  .instrument-card:hover .instrument-overlay {
    height: 100%; /* Expands to cover full card area */
  }

  .overlay-title {
    color: #ffffff;
    font-family: 'Calibri', sans-serif;
    font-size: 1.1rem; /* Slightly reduced to match smaller text limits */
    font-weight: bold;
    margin-bottom: 6px;
  }

  .overlay-description {
    color: #e2e8f0;
    font-size: 12px; /* Balanced text visibility sizing */
    line-height: 1.3;
  }

  /* Fallback Label for Static Displays (Before Hover) */
  .instrument-label {
    position: absolute;
    bottom: 8px;
    left: 8px;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 4px 8px;
    border-radius: 4px;
    font-family: 'Calibri', sans-serif;
    font-size: 12px;
    transition: opacity 0.3s ease;
  }
  .instrument-card:hover .instrument-label {
    opacity: 0; /* Hides label when description pops up */
  }

  /* CSS Styles for the Downloads Section */
  .downloads-section {
    max-width: 800px;
    margin: 50px auto 20px auto;
    padding: 0 20px;
    font-family: 'Calibri', sans-serif;
  }

  .downloads-heading {
    color: #36454f;
    font-weight: bold;
    font-size: 2rem;
    text-align: center;
    margin-bottom: 25px;
  }

  .downloads-list {
    list-style: none;
    padding: 0;
    margin: 0;
  }

  .download-item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 20px;
    margin-bottom: 12px;
    background-color: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 6px;
    transition: background-color 0.2s ease;
  }

  .download-item:hover {
    background-color: #f1f5f9;
  }

  .download-info-title {
    color: #1a365d;
    font-weight: bold;
    font-size: 1.1rem;
    margin-bottom: 2px;
  }

  .download-info-meta {
    color: #64748b;
    font-size: 13px;
  }

  .download-btn {
    display: inline-block;
    background-color: #1a365d;
    color: #ffffff !important;
    text-decoration: none !important;
    padding: 8px 16px;
    border-radius: 4px;
    font-size: 14px;
    font-weight: bold;
    transition: background-color 0.2s ease;
  }

  .download-btn:hover {
    background-color: #2c5282;
  }

  /* Typographical Error Section Styling */
  .typo-section {
    margin-top: 30px;
    padding: 20px;
    background-color: #fef2f2;
    border: 1px dashed #f87171;
    border-radius: 6px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 15px;
  }

  .typo-text {
    color: #991b1b;
    font-size: 14px;
    margin: 0;
    line-height: 1.5;
  }

  .typo-btn {
    display: inline-block;
    background-color: #dc2626;
    color: #ffffff !important;
    text-decoration: none !important;
    padding: 8px 16px;
    border-radius: 4px;
    font-size: 14px;
    font-weight: bold;
    white-space: nowrap;
    transition: background-color 0.2s ease;
  }

  .typo-btn:hover {
    background-color: #b91c1c;
  }
</style>

<!-- Instruments Grid Display Container -->
<div class="container">
  <div class="instruments-grid">

    <!-- Instrument 1 -->
    <div class="instrument-card">
      <img src="{{ '/assets/img/instruments/CF.jpg' | relative_url }}" alt="Confocal Microscope" class="instrument-img">
      <div class="instrument-label">Confocal Microscope</div>
      <div class="instrument-overlay">
        <div class="overlay-title">Confocal Microscope</div>
        <div class="overlay-description">Confocal Microscope.</div>
      </div>
    </div>

    <!-- Instrument 2 -->
    <div class="instrument-card">
      <img src="{{ '/assets/img/instruments/Oxford Plasmalab RIE.png' | relative_url }}" alt="Oxford Plasmalab RIE" class="instrument-img">
      <div class="instrument-label">Oxford Plasmalab RIE</div>
      <div class="instrument-overlay">
        <div class="overlay-title">Oxford Plasmalab RIE</div>
        <div class="overlay-description">Reactive Ion Etching.</div>
      </div>
    </div>

    <!-- Instrument 3 -->
    <div class="instrument-card">
      <img src="{{ '/assets/img/instruments/UV lithography.jpg' | relative_url }}" alt="Isolation Optical Bench" class="instrument-img">
      <div class="instrument-label">UV lithography</div>
      <div class="instrument-overlay">
        <div class="overlay-title">UV lithography</div>
        <div class="overlay-description">Mask aligner for UV lithography.</div>
      </div>
    </div>

    <!-- Instrument 4 -->
    <div class="instrument-card">
      <img src="{{ '/assets/img/instruments/Raith EBL.png' | relative_url }}" alt="Raith EBL" class="instrument-img">
      <div class="instrument-label">Electron Beam Lithography</div>
      <div class="instrument-overlay">
        <div class="overlay-title">Electron Beam Lithography</div>
        <div class="overlay-description">Raith EBL.</div>
      </div>
    </div>

  </div>
</div>


<!-- Downloads Section Container -->
<div class="downloads-section">
  <h2 class="downloads-heading">Resources</h2>

  <ul class="downloads-list">
    <!-- Download Item 1 -->
    <li class="download-item">
      <div>
        <div class="download-info-title">MetaOptics</div>
        <div class="download-info-meta">windows software</div>
      </div>
      <a href="https://drive.google.com/drive/folders/13JNNMIpgqMMrghrcYjTmmgdcdY4fLALg?usp=sharing" class="download-btn" target="_blank" rel="noopener noreferrer">Download</a>
    </li>

    <!-- Added CNNP Website Reference Link Item -->
    <li class="download-item">
      <div>
        <div class="download-info-title">Centre for NEMS and Nanophotonics (CNNP)</div>
        <div class="download-info-meta">Official IITM Fabrication Facility site</div>
      </div>
      <a href="http://www.ee.iitm.ac.in/cnnp/" class="download-btn" target="_blank" rel="noopener noreferrer">Visit Website</a>
    </li>
  </ul>

  <!-- Added Typographical Error Reporting Block -->
  <div class="typo-section">
    <p class="typo-text">
      <strong>Noticed a mistake?</strong> If you find any typographical errors or inconsistencies in our published books or literature, please let us know so we can update them.
    </p>
    <a href="https://google.com" class="typo-btn" target="_blank" rel="noopener noreferrer">Report Typo</a>
  </div>
</div>
