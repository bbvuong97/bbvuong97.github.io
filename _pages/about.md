---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD Candidate in Mechanical Engineering at Stanford University, advised by Allison Okamura in the Collaborative Haptics and Robotics in Medicine (CHARM) Lab. I am a recipient of the NSF Graduate Research Fellowship Program (GRFP) fellowship and Stanford Graduate Fellowship (SGF) in Science & Engineering. I received my BS in Biomedical Engineering at Brown University. Prior to starting my doctorol studies, I spent two years in medical research in the Department of Orthopaedic Surgery, Stanford University, where I spearheaded biomechanics and engineering collaboration projects. My doctoral disseration research focuses on design of haptic devices and haptic augmentation for teleoperation of the da Vinci Surgical System. My research interests span medical robotics, soft robotics, haptics, and assistive technology.

# 📝 Research

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE-RAL (in preparation)</div><img src='images/palpation1.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Relocated Haptic Feedback for Surgical Robot Teleoperation**

**Brian Vuong**, Sangheui Cheon, Josie Davidson, Kyujin Cho, Allison Okamura

- Designed wrist-worn haptic device consisting of a pneumatically actuated, 3D-printed soft haptic voxel display (Hoxel) combined with a novel automatic-fitting anchor with tendon transmission. Integrated tactile force feedback system for teleoperation of the da Vinci Research Kit (dVRK).
- Completed user study exploring the effects of haptic feedback on performance and force accuracy of a palpation task with the dVRK.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RoboSoft 2024</div><img src='images/charm24spring.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Concentric Tube Robot and Robotic System for Neurosurgery**

Tian-Ao Ren, Zhongchun Yu, **Brian Vuong**, Antonio Meola, and Allison M. Okamura

- Developed concentric agonist-antagonist robot (CAAR) end-effector with cable-driven gripper for surgical tasks.
- Mentored masters students and undergrad on mechatronic design of 4-DoF serial manipulator arm for positioning of the flexible end-effector.
- Work on CAAR presented at RoboSoft2024: Soft Robotics Inspired Biology Workshop 2024, [Best submission for lightning talks](https://www.colorado.edu/lab/jayaram/RoboSoft2024), [Poster](https://drive.google.com/file/d/1_OrWDOYpiKpdDFcmk0fL9glgCR9Nf2Y1/view?usp=sharing)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE WHC</div><img src='images/sensory_substitution_device.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Wearable Sensory Substitution for Proprioception via Deep Pressure](https://arxiv.org/pdf/2306.04034)**

Sreela Kodali, **Brian Vuong**, Thomas Bulea, Alexander Chesler, Carsten Bönnemann, and Allison Okamura

- Improved design of device to communicate proprioceptive information via deep pressure stimulation to individuals affected by PIEZO2 loss of function. Explored alternative designs with soft pneumatic actuators and integration with flexible sensor for arm angle measurement.
- Work presented at the [2023 IEEE World Haptics Conference](https://ieeexplore.ieee.org/document/10224435)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JNER</div><img src='images/exoskeleton_HILO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**[Optimization of Exoskeleton Assistance](https://jneuroengrehab.biomedcentral.com/articles/10.1186/s12984-023-01287-5)**

Ava Lakmazaheri, Seungmoon Song, **Brian Vuong**, Blake Biskner, Deborah M. Kado, Steven H. Collins

- Human-in-the-loop optimization of torque patterns for ankle exeloskeleton use among older adults.
- Results of study published in [Journal of NeuroEngineering and Rehabilitation](https://jneuroengrehab.biomedcentral.com/articles/10.1186/s12984-023-01287-5)
</div>
</div>

# 🛠 Design Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CS 225A Spring 2023</div><img src='images/CS225A_demo_clip.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hierarchical Control of Panda Robot in SAI2**

- [Full demo video](https://youtu.be/Uc5Fe3OJMho)


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ME 223 Fall 2022</div><img src='images/ME223_demo_clip.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**5-DoF Serial Manipulator for Liquid Handling**

- [Full demo video](https://youtu.be/XHy-WnZNWOY)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ME 218C Spring 2022</div><img src='images/ME218C_PicMan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Dual-Prop Boat with Teleoperation Controller and Radio UART Communication**

- [Project website](https://picman.webflow.io/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ME 218B Winter 2022</div><img src='images/ME218C_nessie.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Mobile Robot with Sensing for Path-Following Locomotion and PID Speed Control**

- [Project website](https://lilnessie-me218b.weebly.com)
- [Video demo](https://www.youtube.com/watch?v=JPx1zgaApNk)

</div>
</div>


# 🎖 Honors and Awards
- *2021.09* NSF Graduate Research Fellowship (GRFP)
- *2021.09* Stanford Graduate Fellowship (SGF) in Science & Engineering
- *2018.06* Karen T. Romer Undergraduate Teaching and Research Award (UTRA), Brown University

# 📖 Education
- *2021.09 - (now)*, PhD in Mechanical Engineering, Stanford University
- *2015.09 - 2019.05*, ScB (magna cum laude) in Biomedical Engineering, Brown University

# 💻 Internships
- *2017.06 - 2017.08*, Research Intern, NASA Ames Research Center