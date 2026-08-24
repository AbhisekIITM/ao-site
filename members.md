---
layout: single
title: "Group Members"

# --- DEFINITIONS FOR ALL MEMBERS GROUPED BY CATEGORY ---
group_head:
  name: "Dr. Shanti Bhattacharya"
  designation: "Principal Investigator & Group Head"
  image: "/assets/img/members/shanthi.jpg"
  linkedin: "https://www.linkedin.com/in/dr-shanti-bhattacharya-069210209/"
  description: "Dr. Shanti Bhattacharya is a Professor in the Department of Electrical Engineering at IIT Madras, who holds a Ph.D. from IIT Madras (1997), a prestigious Alexander von Humboldt Fellowship (1998), and diverse international industry-academic experience across Germany and the USA focusing on optical MEMS, diffractive beam shaping, and complex light generation."

phd_students:
  - name: "Naveen Kumar Pothapakula"
    image: "/assets/img/members/Naveen.jpg"
    linkedin: "https://www.linkedin.com/in/naveen-kumar-pothapakula-82695612b/"
  - name: "Susan Thomas"
    image: "/assets/img/members/Susan.jpg"
    linkedin: "https://www.linkedin.com/in/susan-thomas-351a70a4/"
  - name: "Jerin Geogy George"
    image: "/assets/img/members/Jerin.png"
    linkedin: "https://www.linkedin.com/in/jerin-george-2541806a/"
  - name: "Sruthy Sebastian"
    image: "/assets/img/members/Sruthy.jpg"
    linkedin: "https://in.linkedin.com/in/sruthy-sebastian-1523b4195"
  - name: "Abhisek Roy"
    image: "/assets/img/members/Abhisek.jpg"
    linkedin: "https://in.linkedin.com/in/abhisek-roy-515476191"

project_associates:
  - name: "Nandan Satish Bhat"
    image: "/assets/img/members/Nandan.jpg"
    linkedin: "https://www.linkedin.com/in/nandan-bhat-05a44828b?utm_source=share_via&utm_content=profile&utm_medium=member_androidm"
  - name: "Ananthakrishnan V"
    image: "/assets/img/members/Anantha.jpg"
    linkedin: "https://in.linkedin.com/in/ananthakrishnan-v"
  - name: "Hira Nayak"
    image: "/assets/img/members/Hira.jpg"
    linkedin: "https://www.linkedin.com/in/hiranayak"

---

<!-- Plain Text Title Block (Centered) -->
<div class="container" style="padding-top: 0px; padding-bottom: 40px; margin-top: 0px; text-align: center;">
  <h1 style="color: #000000; font-family: 'Calibri', sans-serif; font-weight: bold; font-size: 3rem; margin-bottom: 0;">
    Group Members
  </h1>
  <hr style="border-top: 2px solid #1a365d; margin: 15px auto 0 auto; width: 50%;">
</div>

<!-- CSS Styling for Team Grid Architecture -->
<style>

/* Navigation Link Button Style */
  .past-members-btn {
    display: inline-block;
    background-color: #1a365d;
    color: #ffffff !important;
    font-family: 'Calibri', sans-serif;
    font-weight: bold;
    font-size: 16px;
    padding: 10px 24px;
    border-radius: 30px;
    text-decoration: none !important;
    transition: all 0.3s ease;
    box-shadow: 0 4px 10px rgba(26, 54, 147, 0.2);
  }
  .past-members-btn:hover {
    background-color: #38bdf8;
    color: #1a365d !important;
    transform: translateY(-2px);
  }
  .section-header-row {
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 2px solid #1a365d;
      margin-top: 40px;
      margin-bottom: 25px;
      padding-bottom: 8px;
    }
  .section-title {
    color: #000000;
    font-family: 'Calibri', sans-serif;
    font-weight: bold;
    border-bottom: 1px solid #1a365d;
    padding-bottom: 8px;
    margin-top: 40px;
    margin-bottom: 25px;
  }

  /* Grid settings for student profiles */
  .members-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    margin-bottom: 40px;
  }

  /* Single student profile item block box */
  .member-card {
    flex: 1;
    min-width: 220px;
    max-width: 260px;
    background: #111111;
    border: 1px solid #222222;
    border-radius: 8px;
    padding: 20px;
    text-align: center;
    box-shadow: 0 4px 15px rgba(255, 255, 255, 0.02);
  }

  .member-img {
    width: 140px;
    height: 140px;
    border-radius: 50%; /* Perfect circle style layout */
    object-fit: cover;
    margin-bottom: 15px;
    border: 2px solid #1a365d;
  }

  .linkedin-icon {
    color: #0077b5; /* Official LinkedIn Blue color code */
    font-size: 1.4rem;
    text-decoration: none;
    transition: color 0.2s ease;
  }
  .linkedin-icon:hover {
    color: #38bdf8; /* Swaps to cyan on mouse hover profile links */
  }
</style>

<div class="container">

  <!-- ROW 1: THE GROUP HEAD SECTION -->
  <h2 class="section-title">Group Head</h2>
  <div style="display: flex; flex-wrap: wrap; gap: 30px; background: #111111; border: 1px solid #222222; border-radius: 8px; padding: 30px; align-items: center; margin-bottom: 50px;">
    <div style="text-align: center; min-width: 180px;">
      <img src="{{ page.group_head.image | relative_url }}" alt="{{ page.group_head.name }}" style="width: 160px; height: 160px; border-radius: 50%; object-fit: cover; border: 3px solid #1a365d;">
      <h3 style="color: #ffffff; margin-top: 15px; margin-bottom: 5px;">{{ page.group_head.name }}</h3>
      <p style="color: #a0aec0; font-size: 14px; margin-bottom: 10px;">{{ page.group_head.designation }}</p>
      <a href="{{ page.group_head.linkedin }}" target="_blank" class="linkedin-icon"><i class="fa fa-linkedin-square"></i></a>
    </div>
    <div style="flex: 1; min-width: 280px;">
      <p style="color: #cbd5e0; font-size: 16px; line-height: 1.6; margin-bottom: 0;">{{ page.group_head.description }}</p>
    </div>
  </div>

  <!-- ROW 2: CURRENT PHD STUDENTS -->
  <h2 class="section-title">Ph.D. Students</h2>
  <div class="members-grid">
    {% for member in page.phd_students %}
      <div class="member-card">
        <img src="{{ member.image | relative_url }}" alt="{{ member.name }}" class="member-img">
        <h3 style="color: #ffffff; font-size: 1.2rem; margin-bottom: 10px;">{{ member.name }}</h3>
        <a href="{{ member.linkedin }}" target="_blank" class="linkedin-icon"><i class="fa fa-linkedin-square"></i></a>
      </div>
    {% endfor %}
  </div>

  <!-- ROW 3: PROJECT ASSOCIATES -->
  <h2 class="section-title">Project Associates</h2>
  <div class="members-grid">
    {% for member in page.project_associates %}
      <div class="member-card">
        <img src="{{ member.image | relative_url }}" alt="{{ member.name }}" class="member-img">
        <h3 style="color: #ffffff; font-size: 1.2rem; margin-bottom: 10px;">{{ member.name }}</h3>
        <a href="{{ member.linkedin }}" target="_blank" class="linkedin-icon"><i class="fa fa-linkedin-square"></i></a>
      </div>
    {% endfor %}
  </div>

  <!-- ROW 4: INTERNS -->
  <h2 class="section-title">Research Interns</h2>
  <div class="members-grid">
    {% for member in page.interns %}
      <div class="member-card">
        <img src="{{ member.image | relative_url }}" alt="{{ member.name }}" class="member-img">
        <h3 style="color: #ffffff; font-size: 1.2rem; margin-bottom: 10px;">{{ member.name }}</h3>
        <a href="{{ member.linkedin }}" target="_blank" class="linkedin-icon"><i class="fa fa-linkedin-square"></i></a>
      </div>
    {% endfor %}
  </div>

</div>

<!-- Past Members Subpage Shortcut Link Button -->
  <div style="margin-top: 20px;">
    <a href="{{ '/past_members.html' | relative_url }}" class="past-members-btn">
      <i class="fa fa-history" style="margin-right: 8px;"></i>View Past Members &raquo;
    </a>
  </div>
