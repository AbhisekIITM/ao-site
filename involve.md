---
layout: single
title: "Contact Us"
---

<!-- Plain Text Title Block (Centered) -->
<div class="container" style="padding-top: 20px; padding-bottom: 20px; text-align: center;">
  <h1 style="color: #1a365d; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 3rem; margin-bottom: 0;">
    Contact Us
  </h1>
  <hr style="border-top: 2px solid #1a365d; margin: 15px auto 0 auto; width: 50%;">
</div>

<!-- CSS Styling for Contact Layout -->
<style>
  .contact-container {
    max-width: 900px;
    margin: 0 auto;
    padding: 20px 0;
    font-family: 'Calibri', sans-serif;
  }

  .contact-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 40px;
    margin-bottom: 30px;
  }

  .contact-column {
    flex: 1;
    min-width: 300px;
  }

  .contact-card {
    background: #f8fafc; /* Sleek light mode background panel card */
    border: 1px solid #e2e8f0;
    border-left: 4px solid #1a365d; /* Dark blue brand accent border stripe */
    border-radius: 8px;
    padding: 25px;
    margin-bottom: 25px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.02);
  }

  .card-title {
    color: #1a365d;
    font-size: 1.4rem;
    font-weight: bold;
    margin-top: 0;
    margin-bottom: 15px;
  }

  .contact-details {
    color: #334155;
    font-size: 16px;
    line-height: 1.6;
    margin: 0;
  }

  .contact-item {
    margin-bottom: 12px;
    display: flex;
    align-items: flex-start;
  }

  .contact-item i {
    color: #1a365d;
    font-size: 1.2rem;
    margin-right: 12px;
    margin-top: 4px;
    width: 20px;
    text-align: center;
  }

  .contact-item a {
    color: #0077b5;
    text-decoration: none;
    font-weight: bold;
  }

  .contact-item a:hover {
    color: #38bdf8;
    text-decoration: underline;
  }

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

  .errata-text {
    flex: 1;
    min-width: 260px;
    color: #991b1b;
    font-size: 15px;
    line-height: 1.5;
  }

  .errata-form-btn {
    background-color: #ef4444;
    color: #ffffff !important;
    font-weight: bold;
    text-decoration: none !important;
    padding: 10px 20px;
    border-radius: 6px;
    font-size: 14px;
    transition: all 0.2s ease;
    box-shadow: 0 2px 6px rgba(239, 68, 68, 0.2);
  }

  .errata-form-btn:hover {
    background-color: #b91c1c;
    transform: translateY(-1px);
  }

  /* Map Container responsive styling */
  .map-wrapper {
    border: 1px solid #e2e8f0;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.02);
    height: 350px;
    width: 100%;
  }
</style>

<div class="container">
  <div class="contact-container">

    <div class="contact-grid">

      <!-- LEFT COLUMN: ADDRESS & LAB LOCATION -->
      <div class="contact-column">

        <!-- Department & Lab Card -->
        <div class="contact-card">
          <h3 class="card-title">Laboratory Location</h3>
          <div class="contact-details">
            <div class="contact-item">
              <i class="fa fa-university"></i>
              <span>
                <strong>Applied Optics Group</strong><br>
                Department of Electrical Engineering<br>
                Indian Institute of Technology Madras (IITM)<br>
                Chennai, Tamil Nadu - 600036, India
              </span>
            </div>
            <div class="contact-item">
              <i class="fa fa-building"></i>
              <span>Room No: ESB:  335-B</span>
            </div>
          </div>
        </div>

      </div>

      <!-- RIGHT COLUMN: ADVISOR CONTACT DETAILS -->
      <div class="contact-column">

        <!-- Group Advisor Card -->
        <div class="contact-card">
          <h3 class="card-title">Group Advisor</h3>
          <div class="contact-details">
            <p style="font-weight: bold; font-size: 1.1rem; margin-top: 0; margin-bottom: 5px; color: #1a365d;">
              Dr. Shanti Bhattacharya
            </p>
            <p style="color: #64748b; margin-top: 0; margin-bottom: 15px; font-size: 14px;">
              Head of the department, Department of Electrical Engineering
            </p>

            <div class="contact-item">
              <i class="fa fa-envelope"></i>
              <span>Email: <a href="mailto:shanti@ee.iitm.ac.in">shanthib@ee.iitm.ac.in</a></span>
            </div>
            <div class="contact-item">
              <i class="fa fa-linkedin-square"></i>
              <span>LinkedIn: <a href="https://www.linkedin.com/in/dr-shanti-bhattacharya-069210209/" target="_blank">View Profile</a></span>
            </div>
          </div>
        </div>

      </div>

    </div>

    <!-- ================================================================= -->
    <!-- NEW: GOOGLE FORM SUBMISSION ALERT BOX SECTION -->
    <!-- ================================================================= -->

    <!-- ================================================================= -->

    <!-- MAP SECTION ROW -->
    <h2 style="color: #1a365d; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 1.6rem; border-bottom: 2px solid #1a365d; padding-bottom: 8px; margin-bottom: 20px;">
      Find Us on Campus
    </h2>

    <div class="map-wrapper">
      <iframe
        src="https://maps.app.goo.gl/GiTU9be4koVhDRbi9"
        width="100%"
        height="100%"
        style="border:0;"
        allowfullscreen=""
        loading="lazy">
      </iframe>
    </div>

    <div style="text-align: center; margin-top: 15px;">
      <a href="https://maps.app.goo.gl/GiTU9be4koVhDRbi9" target="_blank" style="color: #0077b5; font-weight: bold; text-decoration: none; font-size: 15px;">
        <i class="fa fa-map-marker" style="margin-right: 5px;"></i> Can't see the map? Open directly in Google Maps &raquo;
      </a>
    </div>

  </div>
</div>
