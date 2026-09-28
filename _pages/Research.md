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
</style>

## Browse My Research

Click a project below to jump to its full description.

<div class="research-grid">

  <a href="#wound-care" class="research-card">
    <img src="http://zkarachi.github.io/files/WoundCareEndEffector.jpg" alt="Wound Care Robotics End Effector">
    <div class="card-title">Wound Care Robotics</div>
  </a>

  <a href="#haptics" class="research-card">
    <img src="http://zkarachi.github.io/files/VD.png" alt="Haptic Feedback System">
    <div class="card-title">Haptics for Surgical Robotics</div>
  </a>

  <a href="#fbg-sensor" class="research-card">
    <img src="http://zkarachi.github.io/images/500x300.png" alt="FBG Tactile Sensing for Robotic Gripping">
    <div class="card-title">FBG Tactile Sensing for Robotic Gripping</div>
  </a>

  <a href="#dynaring" class="research-card">
    <img src="http://zkarachi.github.io/images/500x300.png" alt="DynaRing Mitral Annuloplasty Ring">
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

The integration of robotics into wound care offers a promising solution to the growing patient demand amid a global nursing shortage. Formative work understanding the design requirements for wound care robotics to support clinical tasks remains an unmet need. Wound care is a very hands-on and collaborative domain, so understanding its manipulation demands is necessary for developing robotic systems that align with clinical needs.

In this work, we observed nurses performing wound care (n=86 wounds) across a teaching hospital and an assisted living facility to inform the manipulation design requirements for robotics in this domain. Through a thematic analysis of our observational notes, we grouped nurse manipulation approaches into six areas: **grasping strategies, contact regions, bimanual manipulation, mobile manipulation, common motions, and workspace**. For each area, we identified dominant techniques and the clinical context driving their use, described how techniques vary across care tasks and subjects of interaction, and demonstrated how these findings inform robotic design decisions through the design and fabrication of a novel end effector for wound dressing.

This work builds directly on our earlier observational study, ["Towards the Development of Wound Care Robots"](/Publications/) (HRI 2024, Aging in Place Workshop), extending it into a full manipulation taxonomy and a working robotic design case study.

<div style="text-align: center;">
  <img src="http://zkarachi.github.io/files/WoundCareEndEffectorDiagram.png" alt="Wound dressing end effector design and fabrication" style="max-width:95%; height:auto;">
  <p><em>(a) CAD design of the roller-based end effector; (b) the 3D-printed bristle sheets used for wound dressing manipulation; (c) the fabricated end effector mounted on a robot arm during dressing placement.</em></p>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="haptics" class="research-section" markdown="1">

## Haptics and Sensors Projects

### Towards a ROS-based Modular Multi-Modality Haptic Feedback System for Robotic Minimally Invasive Surgery Training Assessments

I helped create a bimanual haptic feedback device to assist novice surgeons on the Intuitive Surgical da Vinci surgical robot. I developed Python code to collect and process force and acceleration data from sensors on the robot, and I remapped these signals to control wrist-squeezing and vibrotactile motors on the haptic feedback device. Furthermore, I ran user studies to test the effectiveness of these modalities with novice users.

<div>
  <img src="http://zkarachi.github.io/files/VD.png" alt="Image 1" style="float:left; width:50%;">
  <img src="http://zkarachi.github.io/files/WSD.png" alt="Image 2" style="float:right; width:50%;">
</div>

<br>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="fbg-sensor" class="research-section" markdown="1">

### Multi-Axis FBG-Based Tactile Sensor for Gripping in Space

I developed a fiber Bragg grating (FBG) sensor to improve grasping and alignment capabilities of teleoperated free-flying robots at the International Space Station (ISS). FBGs measure strain fiber-optically and, in the grasping task, inform the robot's controller of the forces exerted on the object or environment. I used finite element analysis to analyze the current strain applied to the optical fibers of the sensor design previously developed at BDML. From these results, I iterated upon the design until I successfully increased the strain on the optic fibers, resulting in improved sensitivity (without damaging the structure) and enhanced grasping abilities of the robot. My final design was successfully incorporated in the Astrobee Free Flyer (AFF) robot at the ISS; the AFF currently assists astronauts with time-consuming or dangerous tasks in and on the station.

<div style="text-align: center;">
  <video width="640" height="360" controls>
    <source src="http://zkarachi.github.io/files/presentation2 (1).mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="dynaring" class="research-section" markdown="1">

## Medical Device Development

### DynaRing: A Patient-Specific Mitral Annuloplasty Ring With Selective Stiffness Segments

I developed a system to test the durability of a new mitral valve ring design that lasts significantly longer than currently available rings; this work was especially meaningful to me because a longer-lasting ring meant that patients did not have to replace their ring as often, thus offering a more affordable and accessible intervention.

<div style="display:flex;">
  <video src="http://zkarachi.github.io/files/Ringtestvideo.mp4" controls width="400" height="300"></video>
  <video src="http://zkarachi.github.io/files/motor_setup_video.mp4" controls width="400" height="300"></video>
</div>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="accessibility" class="research-section" markdown="1">

## Work on Accessible Technology

### "I'm ok because I'm alive": understanding socio-cultural accessibility barriers for refugees with disabilities in the US

I wanted to understand the perspectives of refugees with disabilities on social-cultural barriers that effect their access to medical care. With this goal, I interviewed community leaders that worked directly with refugees to gain insight on these barrier. I conducted thematic analysis to extract themes on barriers that prevent refugees from accessing the care they need.

### Structural accessibility barriers and service gaps facing refugees with disabilities in the United States

I wanted to understand the perspectives of refugees with disabilities on service-gaps (especially between refugees and healthcare providers) that effect their access to medical care. With this goal, I interviewed community leaders that worked directly with refugees to gain insight on these barrier. I conducted thematic analysis to extract themes on barriers that prevent refugees from accessing the care they need.

### "Fear is Grounded in Reality": The Impact of the COVID-19 Pandemic on Refugees' Access to Health and Accessibility Resources in the United States

With the hardships that hit the US with COVID-19, I wanted to understand the perspectives of refugees with disabilities on the effects of COVID-19 on their access to medical care. With this goal, I interviewed community leaders that worked directly with refugees to gain insight on these barrier. I conducted thematic analysis to extract themes on barriers that prevent refugees from accessing the care they need during COVID-19.

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="spermathecae-3d" class="research-section" markdown="1">

## 3D Modeling

### Three-dimensional Visualization of Harvestman Spermathecae using Confocal Microscopy

I used confocal microscopy to develop a non-invasive imaging and 3D-reconstruction method for the sperm storage organ of female arachnids; I developed the first-ever noninvasive imaging method for arachnids and created the first 3D images of their sperm storage organs.

![Image Description](http://zkarachi.github.io/files/spermathecae.png) | <video src="http://zkarachi.github.io/files/Spermatheca_25_leftside.mp4" controls width="400" height="300"></video>

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>

---

<div id="biology" class="research-section" markdown="1">

## Biology

### Spermathecal Variation By Mating System in Temperate Harvestmen

<a href="#top" class="back-to-top">&uarr; Back to top</a>

</div>
