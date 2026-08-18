---
layout: default
title: "Open Challenges in Robot Control – Part II: Towards a Shared Research Agenda"
display_title: "Open Challenges in Robot Control – Part II:<br>Towards a Shared Research Agenda"
description: "IFAC 2026 Workshop - Busan, Republic of Korea"
date: "Sunday, August 23rd 9:00-17:45"
venue: "Room 311, BEXCO"
---

<div id="custom-header-logos" class="custom-header-logos">
  <a href="https://www.ifac2026.org/fairDash.do" target="_blank" rel="noopener noreferrer">
    <img src="assets/logos/ifac_2026_logo.svg" alt="IFAC 2026">
  </a>
  <a href="https://ieee-ras-robot-control.github.io/" target="_blank" rel="noopener noreferrer">
    <img src="assets/logos/robot_control_tc.svg" alt="TC on Robot Control">
  </a>
</div>

<script>
  // This script waits for the page to load, then moves the logos inside the Cayman green header
  document.addEventListener("DOMContentLoaded", function() {
    var pageHeader = document.querySelector('.page-header');
    var logos = document.getElementById('custom-header-logos');
    if (pageHeader && logos) {
      pageHeader.appendChild(logos);
    }
  });
</script>

## Workshop Overview
Robotics poses an increasingly demanding set of challenges to control theory, driven by the emergence of new robotic concepts (such as soft and biohybrid systems) and by the growing need for physical interaction, autonomy, and operation in unstructured environments. At the same time, new opportunities are opening up, including the wider availability of advanced robotic platforms and the successful integration of learning-based components. In this evolving landscape, the theory and practice of robot control play a central role.

Despite this growing relevance, control-theoretic contributions addressing these challenges are often fragmented across paradigms, communities, and venues. This workshop provides a dedicated forum to reconnect these efforts and to collectively reflect on which challenges remain open, how their formulation is evolving, and how they relate to both classical control theory and emerging technologies.

The workshop will combine short perspective talks with extended, structured discussion sessions. Each invited speaker will be asked to articulate one to three open challenges in robot control and to reflect on how these challenges connect to existing theory and current practice. Discussion sessions will focus on contrasting perspectives, clarifying assumptions, and highlighting common structural themes and limitations across different approaches.

This workshop represents a second, complementary step in a broader community effort to strengthen the intellectual foundations of robot control across societies. While Part I (to be held at ECC 2026) focuses on surfacing open challenges and perspectives from invited experts, this workshop provides a forum within the IFAC community to further examine and contextualize these challenges through the lens of automatic control, without presupposing convergence toward a single agenda or set of prescriptions.

<!-- ## Objectives -->

## Target Audience
The workshop targets researchers in control and robotics whose work engages with the modeling, analysis, and control of complex robotic systems, particularly in settings involving physical interaction, uncertainty, hybrid behavior, and learning-enabled components. It is especially relevant for those interested in the foundations of robotics control, the limits of existing frameworks, and the formulation of new problems arising from emerging robotic platforms and technologies.

Relevant research areas include, but are not limited to, on **the control theory and engineering** side:
* nonlinear, geometric, and energy-based control
* hybrid, discrete-event, and supervisory systems
* optimization-based control and model predictive control
* learning-based, data-driven, and adaptive control
* robustness, uncertainty, and safety-critical control
* integration of control with perception, planning, and autonomy

And, from the **robotics** perspective:
* aerial robotics and other floating base systems
* modeling and control of compliant, soft, and underactuated robots
* physical interaction, impedance control, and human–robot interaction
* whole-body, humanoid, and multi-contact control

The intended audience includes faculty members, postdoctoral researchers, and PhD students, as well as advanced practitioners from research-oriented industry who are concerned with principled system design rather than application-specific tuning. The workshop aims to attract participants from both the control and robotics communities and to foster dialogue across methodological and disciplinary boundaries.

## Invited Speakers

<!-- ### Early to Mid Career -->
<div class="profile-grid">
  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/christian.jpg" alt="Christian Ott" class="profile-image">
      <div class="profile-info">
        <h3>Christian Ott</h3>
        <h4>TU Wien, Austria</h4>
        <p class="talk-title">Talk title: Robot control for tasks with fast contact transitions</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>Christian Ott is Full Professor at TU Wien in Austria and is also affiliated with the German Aerospace Center (DLR). He was Project Assistant Professor at the University of Tokyo and head of department at DLR. He has been Associate Editor for the IEEE TRO and Co-Editor-in-Chief for IFAC Mechatronics. He is currently serving as Senior Editor for IJRR and as Editor-In-Chief of ICRA. He is IEEE Fellow and serves as IFAC Council Member for the triennials 2024&ndash;2026 and 2027&ndash;2029. His research interests are in nonlinear control in robotics, whole-body control, and humanoid robotics.</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/jinoh.jpg" alt="Jinoh Lee" class="profile-image">
      <div class="profile-info">
        <h3>Jinoh Lee</h3>
        <h4>German Aerospace Center (DLR), Germany</h4>
        <p class="talk-title">Talk title: A Model-free Model Predictive Control</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>Jinoh Lee is a Research Scientist at the Institute of Robotics and Mechatronics, German Aerospace Center (DLR), where he leads the Humanoid and Legged Robots Team. He is also an Adjunct Professor at KAIST, Korea, and the University of Guelph, Canada. His research focuses on robot control of redundant systems, dual-arm manipulation, and whole-body locomotion of humanoids, and robust control of nonlinear systems. He received his Ph.D. in Mechanical Engineering from KAIST, Korea, in 2012; before joining DLR in 2020, he was a researcher at IIT, Italy, and also partly as a research consultant for Disney Research, US.</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/sehoon.jpg" alt="Sehoon Oh" class="profile-image">
      <div class="profile-info">
        <h3>Sehoon Oh</h3>
        <h4>DGIST, Korea</h4>
        <p class="talk-title">Talk title: TBD</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>TBD</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/cosimo.jpg" alt="Cosimo Della Santina" class="profile-image">
      <div class="profile-info">
        <h3>Cosimo Della Santina</h3>
        <h4>TU Delft, The Netherlands</h4>
        <p class="talk-title">Talk title: TBD</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>TBD</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/woolim.avif" alt="Woolim Hong" class="profile-image">
      <div class="profile-info">
        <h3>Woolim Hong</h3>
        <h4>North Carolina State University, USA</h4>
        <p class="talk-title">Talk title: Toward Human&ndash;Robot Symbiosis in Wearable Robotics: Lessons from Robotic Prostheses</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>Woolim Hong is a postdoctoral fellow in the Neuromuscular Rehabilitation Engineering Laboratory, directed by Dr. He (Helen) Huang, at North Carolina State University and the University of North Carolina at Chapel Hill. His research focuses on intelligent control and personalization of wearable robotic systems, particularly powered lower-limb prostheses, with an emphasis on reinforcement learning, human&ndash;robot interaction, and safety. He received his Ph.D. in Mechanical Engineering from Texas A&amp;M University and is a recipient of the NIDILRR Mary E. Switzer Research Fellowship.</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/li.jpg" alt="Li-Chen Fu" class="profile-image">
      <div class="profile-info">
        <h3>Li-Chen Fu</h3>
        <h4>National Taiwan University, Taiwan</h4>
        <p class="talk-title">Talk title: GenAI-Empowered Social Robots for Human Care</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>Li-Chen Fu received his Ph.D. degree from UC Berkeley in 1987, and joined National Taiwan University (NTU) since then. He currently holds the title of Lifetime National Chair Professor. He previously served as Secretary General of NTU (2005&ndash;2008) and Director of the NTU Center for AI and Advanced Robotics (2017&ndash;2024). He is an IEEE Fellow, IFAC Fellow, and ACA Fellow, and his research interests include robotics, AI, computer vision, and control.</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <div class="profile-image-group">
        <img src="assets/speakers/jin.jpg" alt="H. Jin Kim" class="profile-image">
        <img src="assets/speakers/inkyu.jpg" alt="Inkyu Jang" class="profile-image">
      </div>
      <div class="profile-info">
        <h3>H. Jin Kim &amp; Inkyu Jang</h3>
        <h4>Seoul National University, Korea</h4>
        <p class="talk-title">Talk title: Safety Analysis and Filtering for Real-World Robot Control</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>H. Jin Kim is a Professor in the Department of Aerospace Engineering at Seoul National University (SNU). She received her B.S. degree in Mechanical Engineering from KAIST and her M.S. and Ph.D. degrees in Mechanical Engineering from the University of California, Berkeley. Prior to joining Seoul National University in 2004, she was a postdoctoral researcher and lecturer in Electrical Engineering and Computer Sciences at UC Berkeley. She currently leads the Laboratory for Autonomous Robotics Research (LARR) at SNU and is a visiting researcher at Samsung Electronics. Her research interests include robotics, autonomous systems, intelligent control, motion planning, and navigation, with applications to aerial and ground robotic systems.</p>
        <p>Inkyu Jang is a Ph.D. candidate (degree pending conferral) in Aerospace Engineering at Seoul National University (SNU) and an incoming postdoctoral researcher at the Department of Electrical Engineering and Computer Sciences at UC Berkeley starting September 2026. During his doctoral studies, he was a visiting researcher at UC Berkeley in 2024 and 2025. He received his B.S. degree in Mechanical Engineering from SNU in 2020. His research interests lie at the intersection of control theory and robotics, with a particular focus on learning-based safety-critical control and stochastic safety analysis.</p>
      </div>
    </div>
  </div>

  <div class="profile-card">
    <div class="card-head">
      <img src="assets/speakers/choi_hj.png" alt="Hyunjin Choi" class="profile-image">
      <div class="profile-info">
        <h3>Hyunjin Choi | 최현진</h3>
        <h4>Sangmyung University, Cheonan, Korea</h4>
        <p class="talk-title">Talk title: What Should a Wearable Robot Know About Its User? Open Challenges from Wearable Robotics</p>
      </div>
    </div>
    <button class="toggle" onclick="this.closest('.profile-card').classList.toggle('expanded')">
      <span class="arrow">&#9662;</span> Bio
    </button>
    <div class="details">
      <div class="details-inner">
        <p>Hyunjin Choi is an Assistant Professor in the Department of Human Intelligence and Robot Engineering at Sangmyung University, Korea. She received her Ph.D. in Mechanical Engineering from Sogang University in 2019, where her research focused on assistance and rehabilitation for people with paretic gait using torque-controlled wearable robots. Prior to joining Sangmyung University, she was a founding member and lead engineer at Angel Robotics. Her research interests include wearable robots, human&ndash;robot interaction, gait analysis, and sensing and control technologies for assistive and rehabilitation robotics. She currently serves as Vice Chair of the IFAC Technical Committee on Robotics.</p>
      </div>
    </div>
  </div>
</div>

## Program Schedule

<div class="agenda">
  <div class="row plain"><div class="time">09:00&ndash;09:05</div><div class="who"><span class="name">Opening</span></div></div>

  <div class="session-header s1"><span class="eyebrow">Session I</span><span class="title">Model-based interaction control: rigid, compliant, and soft</span></div>
  <div class="row s1"><div class="time">09:05&ndash;09:40</div><div class="who"><span class="name">Christian Ott</span> <span class="affil">&mdash; TU Wien</span></div></div>
  <div class="row s1"><div class="time">09:40&ndash;10:15</div><div class="who"><span class="name">Jinoh Lee</span> <span class="affil">&mdash; DLR</span></div></div>
  <div class="row break"><div class="time">10:15&ndash;10:45</div><div class="who">Coffee break</div></div>
  <div class="row s1"><div class="time">10:45&ndash;11:20</div><div class="who"><span class="name">Sehoon Oh</span> <span class="affil">&mdash; DGIST</span></div></div>
  <div class="row s1"><div class="time">11:20&ndash;11:55</div><div class="who"><span class="name">Cosimo Della Santina</span> <span class="affil">&mdash; TU Delft</span></div></div>
  <div class="row break"><div class="time">11:55&ndash;13:20</div><div class="who">Lunch break</div></div>

  <div class="session-header s2"><span class="eyebrow">Session II</span><span class="title">Humans in the loop: interaction, autonomy, and learning</span></div>
  <div class="row s2"><div class="time">13:20&ndash;13:55</div><div class="who"><span class="name">Woolim Hong</span> <span class="affil">&mdash; NC State University</span></div></div>
  <div class="row s2"><div class="time">13:55&ndash;14:30</div><div class="who"><span class="name">Li-Chen Fu</span> <span class="affil">&mdash; National Taiwan University</span></div></div>
  <div class="row s2"><div class="time">14:30&ndash;15:05</div><div class="who"><span class="name">H. Jin Kim &amp; Inkyu Jang</span> <span class="affil">&mdash; Seoul National University</span></div></div>
  <div class="row break"><div class="time">15:05&ndash;15:15</div><div class="who">Q&amp;A buffer</div></div>
  <div class="row break"><div class="time">15:15&ndash;15:45</div><div class="who">Coffee break</div></div>
  <div class="row s2"><div class="time">15:45&ndash;16:20</div><div class="who"><span class="name">Hyunjin Choi</span> <span class="affil">&mdash; Sangmyung University</span></div></div>

  <div class="session-header s3"><span class="eyebrow">Closing</span><span class="title">Moderated discussion &amp; closing remarks</span></div>
  <div class="row s3"><div class="time">16:20&ndash;17:30</div><div class="who">Moderated discussion with all speakers</div></div>
  <div class="row s3"><div class="time">17:30&ndash;17:45</div><div class="who">Closing remarks</div></div>
</div>


## Organizers

<div class="profile-grid">
  <div class="profile-card">
    <img src="assets/organizers/cosimo.jpg" alt="Cosimo Della Santina" class="profile-image">
    <div class="profile-info">
      <h3>Cosimo Della Santina</h3>
      <h4>TU Delft, The Netherlands</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/kyoungchul.jpg" alt="Kyoungchul Kong" class="profile-image">
    <div class="profile-info">
      <h3>Kyoungchul Kong</h3>
      <h4>Korea Advanced Institute of Science and Technology (KAIST), Korea</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/kaoru.jpg" alt="Kaoru Yamamoto" class="profile-image">
    <div class="profile-info">
      <h3>Kaoru Yamamoto</h3>
      <h4>Kyushu University, Japan</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/manuel.jpg" alt="Manuel Keppler" class="profile-image">
    <div class="profile-info">
      <h3>Manuel Keppler</h3>
      <h4>German Aerospace Center (DLR), Germany</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/sylvia.jpg" alt="Sylvia Herbert" class="profile-image">
    <div class="profile-info">
      <h3>Sylvia Herbert</h3>
      <h4>University of California San Diego, USA</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/fumiya_matsuzaki.jpg" alt="Fumiya Matsuzaki" class="profile-image">
    <div class="profile-info">
      <h3>Fumiya Matsuzaki</h3>
      <h4>Kyushu University, Japan</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/yuhe_gong.jpg" alt="Yuhe Gong" class="profile-image">
    <div class="profile-info">
      <h3>Yuhe Gong</h3>
      <h4>University of Nottingham, UK</h4>
    </div>
  </div>

  <div class="profile-card">
    <img src="assets/organizers/daniele_caradonna.jpg" alt="Daniele Caradonna" class="profile-image">
    <div class="profile-info">
      <h3>Daniele Caradonna</h3>
      <h4>Scuola Superiore Sant'Anna, Italy</h4>
    </div>
  </div>
</div>

## Expected Outcomes
With this workshop, we aim to strengthen the Robot Control community within IFAC and connect it to researchers active in robotics and related areas. Expected outcomes include:
* a clearer articulation of open challenges in robot control and of how they are perceived across different communities,
* improved mutual understanding of underlying assumptions, limitations, and points of tension between control-theoretic and robotics-oriented approaches,
* material that may inform future discussions, collaborations, or community efforts, without presupposing convergence toward specific solutions or agendas.