---
layout: archive
title: "Research"
permalink: /Research/
author_profile: true
---

<style>
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.5rem;
  margin: 1.5rem 0 3rem 0;
}
.research-card {
  display: block;
  text-decoration: none;
  color: inherit;
  border: 1px solid #ddd;
  border-radius: 8px;
  overflow: hidden;
  transition: transform 0.15s ease, box-shadow 0.15s ease;
  background: #fff;
}
.research-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 16px rgba(0,0,0,0.15);
  text-decoration: none;
}
.research-card img {
  width: 100%;
  height: 160px;
  object-fit: cover;
  display: block;
  background: #f2f2f2;
}
.research-card .card-title {
  padding: 0.75rem;
  font-weight: 600;
  font-size: 0.95rem;
  line-height: 1.3;
}
.research-section {
  scroll-margin-top: 80px;
  padding-top: 1rem;
}
.back-to-top {
  display: inline-block;
  margin-top: 1rem;
  font-size: 0.85rem;
}
.grid-heading {
  margin-top: 2rem;
}
.related-paper {
  font-style: italic;
  color: #555;
  border: none;
  background: none;
  padding: 0;
  margin: 0.5rem 0 1rem 0;
}
.related-paper a {
  margin-right: 0.75rem;
}
.media-center {
  text-align: center;
  margin: 1.5rem 0;
}
.media-center img,
.media-center video {
  max-width: 95%;
  height: auto;
  margin: 0 0.5rem;
}
</style>

## Browse My Research

Click a project below to jump to its full description.

### Ongoing Projects

<div class="research-grid">

  <a href="#wound-care" class="research-card">
    <img src="http://zkarachi.github.io/files/WoundCareEndEffector.jpg" alt="Wound Care Robotics End Effector">
    <div class="card-title">Wound Care Robotics</div>
  </a>

  <a href="#tui-symptom" class="research-card">
    <img src="http://zkarachi.github.io/images/500x300.png" alt="Tangible Interactions for Symptom Expression">
    <div class="card-title">Tangible Interactions for Symptom Expression</div>
  </a>

</div>

### Completed Projects

<div class="research-grid">

  <a href="#haptics" class="research-card">
    <img src="http://zkarachi.github.io/files/VD.png" alt="Haptic Feedback System">
    <div class="card-title">Haptics for Surgical Robotics</div>
  </a>

  <a href="#fbg-sensor" class="research-card">
    <img src="http://zkarachi.github.io/files/FBGGripper.jpg" alt="FBG Tactile Sensing for Robotic Gripping">
    <div class="card-title">FBG Tactile Sensing for Robotic Gripping</div>
  </a>

  <a href="#dynaring" class="research-card">
    <img src="http://zkarachi.github.io/files/DynaRingPhoto.jpg" alt="DynaRing Mitral Annuloplasty Ring">
    <div class="card-title">DynaRing: Patient-Specific Mitral Annuloplasty Ring</div>
  </a>

  <a href="#accessibility" class="research-card">
    <img src="http://zkarachi.github.io/images/500x300.png" alt="Refugee Accessibility Research">
    <div class="card-title">Accessibility Barriers for Refugees with Disabilities</div>
  </a>

  <a href="#spermathecae-3d" class="research-card">
    <img src="http://zkarachi.github.io/files/spermathecae.png" alt="Harvestman Spermathecae 3D Visualization">
    <div class="card-title">3D Visualization Using Confocal Microscopy</div>
  </a>

  <a href="#biology" class="research-card">
    <img src="http://zkarachi.github.io/images/500x300.png" alt="Spermathecal Variation Research">
    <div class="card-title">Spermathecal Variation By Mating System</div>
  </a>

</div>

---

<div id="wound-care" class="research-section" markdown="1">

## Robotic Wound Care

### Descriptive Analysis of Manipulation Techniques in Wound Care

Robotics offers a promising way to help meet growing wound care demand amid a global nursing shortage, but understanding the manipulation demands of this hands-on, collaborative domain is a necessary first step.

We contribute a descriptive analysis of manipulation approaches used during care, grouped into six areas: grasping, mobile manipulation, bi-manual manipulation, contact regions, common motions, and work area. For each, we describe the emergent strategies observed, the clinical context driving their use, and how strategies are employed for different subjects of manipulation (e.g., patients, the wound, or materials) and care tasks. Finally, we demonstrate how our findings within these manipulation areas can be used to inform robotic design through a case study in which we design and fabricate a wound dressing end effector.

This work builds directly on our earlier observational study, ["Towards the Development of Wound Care Robots"](/Publications/) (HRI 2024, Aging in Place Workshop).

**Related papers:**
- Descriptive Analysis of Manipulation Techniques in Wound Care (RO-MAN 2026) — *coming soon*
- Towards the Development of Wound Care Robots (HRI 2024, Aging in Place Workshop) — [PDF Paper](http://zkarachi.github.io/files/WoundCareRobots.pdf)

<div style="text-align: center;">
  <img src="http://zkarachi.github.io/files/WoundCareEndEffectorDiagram.png" alt="Wound dressing end effector design and fabrication" style="max-width:95%; height:auto;">
  <p><em>The process of developing our wound care robotic end effector: (a) CAD design of the roller mechanism, (b) fabrication of the 3D-printed bristle sheets, and (c) the completed end effector mounted on a Kinova robot arm during dressing pick and place task.</em></p>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="tui-symptom" class="research-section" markdown="1">

## Tangible Interactions for Symptom Expression

### Tangible Interactions for Symptom Expression

I am developing a tangible user interface (TUI) that lets people track and express their symptoms through physical object manipulation rather than typing or selecting from a list. Using a soma design study methodology, participants physically enact the bodily experience of their symptoms, and these embodied interactions inform the design of a symptom-tracking interface that better captures the lived, physical experience of illness than conventional text- or menu-based tracking tools.

*More details and findings to come as this project develops.*

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="haptics" class="research-section" markdown="1">

## Haptics and Sensors Projects

### Towards a ROS-based Modular Multi-Modality Haptic Feedback System for Robotic Minimally Invasive Surgery Training Assessments

Robotic minimally invasive surgery (RMIS) platforms like the da Vinci provide no haptic feedback of tool interactions with the surgical environment, forcing novice surgeons to rely solely on visual cues to sense their physical interactions — a limitation that can make training slow and difficult.

We built a ROS-based, modular multi-modality haptic feedback and data acquisition system that streams force and acceleration data from sensorized surgical tools in real time and renders it as wrist-squeezing or vibrotactile feedback through custom wrist-worn devices. We developed a Python-based signal processing pipeline and ran a user study with novice participants performing a peg-transfer task on a da Vinci robot, comparing wrist-squeezing, vibrotactile, and combined multi-modality feedback conditions. The system demonstrates the ability to run systematic, reproducible comparisons between haptic feedback approaches — addressing a key gap in prior work, which lacked a standardized framework for these comparisons.

<p class="related-paper">Related paper: <a href="https://ieeexplore.ieee.org/abstract/document/9807479">Link to Paper</a> <a href="http://zkarachi.github.io/files/paper3.pdf">PDF Paper</a></p>

<div class="media-center">
  <img src="http://zkarachi.github.io/files/VD.png" alt="Vibrotactile feedback device" style="width:45%;">
  <img src="http://zkarachi.github.io/files/WSD.png" alt="Wrist-squeezing feedback device" style="width:45%;">
  <p><em>The custom wrist-worn haptic feedback devices: the vibrotactile device (left) and the wrist-squeezing device (right).</em></p>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="fbg-sensor" class="research-section" markdown="1">

### A Multi-Axis FBG-Based Tactile Sensor for Gripping in Space

Tactile sensing can improve end-effector control and grasp quality, especially for free-flying robots where target approach and alignment present unique challenges — but many conventional tactile sensing technologies are unsuited to the harsh environment of space.

We developed a multi-axis tactile sensor that measures normal and shear strains in the pads of a robotic gripper using a single optical fiber with Bragg grating (FBG) sensors, which are immune to electromagnetic interference and can sample at over 1 kHz to detect dynamic events. We used finite element analysis to optimize the sensor design, increasing strain sensitivity at the fiber without compromising structural integrity. The final sensor was mounted on a custom two-fingered gripper and calibrated against a commercial multi-axis load cell with 96.2% RMS accuracy, and was demonstrated on tasks motivated by NASA's Astrobee free-flying robots aboard the International Space Station — including detecting misaligned grasps, perceiving shear forces, and improving load sharing across contact areas in pinch grasps.

<p class="related-paper">Related paper: <a href="https://ieeexplore.ieee.org/abstract/document/9635998">Link to Paper</a> <a href="http://zkarachi.github.io/files/FBG.pdf">PDF Paper</a></p>

<div class="media-center">
  <video width="640" height="360" controls>
    <source src="http://zkarachi.github.io/files/presentation2 (1).mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p><em>FEA analysis of sensor design with shear force application.</em></p>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="dynaring" class="research-section" markdown="1">

## Medical Device Development

### DynaRing: A Patient-Specific Mitral Annuloplasty Ring With Selective Stiffness Segments

Annuloplasty ring choice and design are critical to the long-term efficacy of mitral valve repair, but commercially available rings fail to account for the wide variation in annular dynamics across patients.

We developed and evaluated DynaRing, a selectively compliant annuloplasty ring composed of variable-stiffness elastomer segments, a shape-set nitinol core, and a cross-diameter filament that stabilizes a diseased annulus while preserving physiological annular dynamics. We evaluated the ring in porcine valves using an ex-vivo left heart simulator and performed a 150-million-cycle fatigue test to assess long-term durability, and developed a patient-specific design pipeline using finite element model optimization and patient MRI data. Our results show that DynaRing's motion closely matches literature values for healthy annuli and outperforms a commercially available semirigid ring, and that segment stiffness can be tuned via Bayesian optimization to match a wide range of patient-specific annular geometries. This work is especially meaningful because a longer-lasting, better-fitting ring means patients need fewer repeat procedures — offering a more affordable and accessible intervention.

<p class="related-paper">Related paper: <a href="https://doi.org/10.1115/1.4054445">Link to Paper</a> <a href="http://zkarachi.github.io/files/paper1.pdf">PDF Paper</a></p>

<div class="media-center" style="display:flex; justify-content:center; flex-wrap:wrap;">
  <video src="http://zkarachi.github.io/files/Ringtestvideo.mp4" controls width="400" height="300"></video>
  <video src="http://zkarachi.github.io/files/motor_setup_video.mp4" controls width="400" height="300"></video>
</div>
<p style="text-align:center;"><em>Left: DynaRing under cyclic fatigue testing on newly designed testing apparatus. Right: newly developed motorized test setup used to evaluate the ring's variable-stiffness segments.</em></p>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="accessibility" class="research-section" markdown="1">

## Work on Accessible Technology

### "I'm ok because I'm alive": understanding socio-cultural accessibility barriers for refugees with disabilities in the US

The number of refugees worldwide has doubled in the past decade, and many experience disabilities and mental health challenges compounded by violent or inhospitable conditions during displacement.

We interviewed six experts who serve refugees in the US to understand the socio-cultural accessibility barriers refugees with disabilities face — including inadequate language and cultural support systems — and conducted thematic analysis to identify directions for structural change, including improved access to comprehensive insurance coverage, earlier recognition of mental health challenges, and support navigating the host country's complex healthcare system.

<p class="related-paper">Related paper: <a href="https://dl.acm.org/doi/abs/10.1145/3493612.3520446">Link to Paper</a> <a href="http://zkarachi.github.io/files/paper2.pdf">PDF Paper</a></p>

### Structural accessibility barriers and service gaps facing refugees with disabilities in the United States

This scoping study examines structural barriers and service gaps facing refugees with disabilities in the United States, from the perspective of the experts who serve them.

Through semi-structured interviews with six experts who work with refugees, we found that refugees and their families are significantly impacted by disabilities and mental health challenges, and face structural barriers including navigating a complex healthcare system, geographic placements that limit access to employment or care, and difficulty accessing public transit. Our findings point to practical directions for improvement, including stronger structural support for refugees with disabilities and incentivizing healthcare providers to adopt more culturally aware language services.

<p class="related-paper">Related paper: <a href="https://www.emerald.com/insight/content/doi/10.1108/JET-11-2021-0054/full/html?utm_campaign=Emerald_Health_PPV_Dec22_RoN">Link to Paper</a> <a href="http://zkarachi.github.io/files/UnderstandingBarriers.pdf">PDF Paper</a></p>

### "Fear is Grounded in Reality": The Impact of the COVID-19 Pandemic on Refugees' Access to Health and Accessibility Resources in the United States

The COVID-19 pandemic disproportionately affected refugees with disabilities and mental health challenges, an understudied population facing compounding barriers to care.

We conducted interviews with four experts serving refugees in Maryland during the first year of the pandemic to understand its impact on refugees' access to health and accessibility resources. Our findings describe how the co-existence of the pandemic with a turbulent political environment exacerbated existing inequities faced by refugees, and identify strategies for resilience that emerged within the communities these experts serve.

<p class="related-paper">Related paper: <a href="https://dl.acm.org/doi/abs/10.1145/3530190.3534851">Link to Paper</a> <a href="http://zkarachi.github.io/files/FearisGrounded.pdf">PDF Paper</a></p>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="spermathecae-3d" class="research-section" markdown="1">

## 3D Modeling

### Three-dimensional Visualization of Harvestman Spermathecae using Confocal Microscopy

We used confocal microscopy to develop a non-invasive imaging and 3D-reconstruction method for the sperm storage organ of female arachnids; this produced the first-ever noninvasive imaging method for arachnids and the first 3D images of their sperm storage organs.

<div class="media-center" style="display:flex; justify-content:center; align-items:center; flex-wrap:wrap;">
  <img src="http://zkarachi.github.io/files/spermathecae.png" alt="Harvestman spermathecae 3D visualization" style="width:400px; height:auto;">
  <video src="http://zkarachi.github.io/files/Spermatheca_25_leftside.mp4" controls width="400" height="300"></video>
</div>
<p style="text-align:center;"><em>Left: 3D reconstruction of a harvestman spermatheca from confocal microscopy imaging. Right: rotating 3D visualization of the same structure.</em></p>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="biology" class="research-section" markdown="1">

## Biology

### Spermathecal Variation By Mating System in Temperate Harvestmen

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>
