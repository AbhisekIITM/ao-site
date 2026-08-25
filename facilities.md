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

<!-- CSS Styles for Hover Overlay Effects -->
<style>
  .instruments-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    padding: 20px 0;
  }

  .instrument-card {
    position: relative;
    flex: 1;
    min-width: 280px;
    max-width: 350px;
    height: 250px;
    border-radius: 8px;
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
    padding: 0 20px;
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
    font-size: 1.5rem;
    font-weight: bold;
    margin-bottom: 8px;
  }

  .overlay-description {
    color: #e2e8f0;
    font-size: 14px;
    line-height: 1.4;
  }

  /* Fallback Label for Static Displays (Before Hover) */
  .instrument-label {
    position: absolute;
    bottom: 10px;
    left: 10px;
    background: rgba(0, 0, 0, 0.7);
    color: #fff;
    padding: 5px 10px;
    border-radius: 4px;
    font-family: 'Calibri', sans-serif;
    font-size: 14px;
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

/* NEW: Google Form Error Reporting Alert Section CSS */
.errata-box {
  background: #fef2f2; /* Light administrative alert red tint */
  border: 1px solid #fca5a5;
  border-left: 4px solid #ef4444; /* High-visibility red alert stripe */
  border-radius: 8px;
  padding: 20px;
  margin-bottom: 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 20px;
  box-shadow: 0 4px 12px rgba(239, 68, 68, 0.02);
}

<!-- Downloads Section Container -->
<div class="downloads-section">
  <h2 class="downloads-heading">Downloads</h2>

  <ul class="downloads-list">
    <!-- Download Item 1 -->
    <li class="download-item">
      <div>
        <div class="download-info-title">MetaOptics    </div>
        <div class="download-info-meta">windows software</div>
      </div>
      <a href="https://drive.google.com/drive/folders/13JNNMIpgqMMrghrcYjTmmgdcdY4fLALg?usp=sharing" class="download-btn" target="_blank" rel="noopener noreferrer">Download</a>
    </li>


  </ul>
</div>
