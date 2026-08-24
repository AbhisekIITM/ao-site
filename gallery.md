---
layout: single
title: "Lab Gallery - Maintenance"
---

<div class="maintenance-container">
  <div class="maintenance-card">
    <!-- Animated Media Icons using your active Font Awesome package -->
    <div class="icon-wrapper">
      <i class="fa fa-picture-o mechanical-gear"></i>
      <i class="fa fa-cog fa-spin sub-tool-icon"></i>
    </div>

    <h1 class="maintenance-title">Gallery Under Maintenance</h1>

    <div class="accent-bar"></div>

    <p class="maintenance-message">
      We are currently updating our visual archives of the <strong>Applied Optics Group</strong>.
    </p>

    <p class="sub-message">
      Our laboratory photo modules will be fully accessible shortly.
    </p>

    <!-- Action Button to return seamlessly back to the main landing Home Page -->
    <div style="margin-top: 35px;">
      <a href="{{ '/' | relative_url }}" class="return-home-btn">
        <i class="fa fa-home" style="margin-right: 8px;"></i>Return to Home Page
      </a>
    </div>
  </div>
</div>

<!-- Embedded Clean CSS Layout for the Maintenance Screen -->
<style>
  .maintenance-container {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 60vh;
    padding: 20px;
    background-color: #ffffff; /* Seamlessly matches your default white site background */
  }

  .maintenance-card {
    text-align: center;
    max-width: 550px;
    background: #f8fafc; /* Subtle light gray card layout */
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    padding: 40px 30px;
    box-shadow: 0 10px 25px rgba(26, 54, 147, 0.04);
  }

  .icon-wrapper {
    position: relative;
    display: inline-block;
    margin-bottom: 25px;
  }

  .mechanical-gear {
    font-size: 4.5rem;
    color: #1a365d; /* Dark brand blue color rule */
  }

  .sub-tool-icon {
    position: absolute;
    bottom: -5px;
    right: -5px;
    font-size: 1.8rem;
    color: #38bdf8; /* Vibrant cyan accent pop */
    background: #f8fafc;
    padding: 2px;
    border-radius: 50%;
  }

  .maintenance-title {
    color: #1a365d;
    font-family: 'Calibri', sans-serif;
    font-weight: bold;
    font-size: 2.2rem;
    margin-bottom: 0;
  }

  .accent-bar {
    width: 60px;
    height: 3px;
    background-color: #38bdf8; /* Cyan divider accent */
    margin: 15px auto 20px auto;
    border-radius: 2px;
  }

  .maintenance-message {
    color: #334155;
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 10px;
  }

  .sub-message {
    color: #64748b;
    font-size: 14px;
    font-style: italic;
    margin-bottom: 0;
  }

  .return-home-btn {
    display: inline-block;
    background-color: #1a365d;
    color: #ffffff !important;
    font-family: 'Calibri', sans-serif;
    font-weight: bold;
    font-size: 15px;
    padding: 10px 24px;
    border-radius: 30px;
    text-decoration: none !important;
    transition: all 0.3s ease;
    box-shadow: 0 4px 10px rgba(26, 54, 147, 0.15);
  }

  .return-home-btn:hover {
    background-color: #38bdf8;
    color: #1a365d !important;
    transform: translateY(-2px);
  }
</style>
