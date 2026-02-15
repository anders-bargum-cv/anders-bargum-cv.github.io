---
layout: page
title: projects
permalink: /projects/
description: Portfolio of former and current projects.
nav: true
nav_order: 7
---

<style>
.project-item {
  margin-bottom: 2.5rem;
  padding-bottom: 2rem;
  border-bottom: 1px solid #ddd;
}

.project-item:last-child {
  border-bottom: none;
  margin-bottom: 0;
  padding-bottom: 0;
}

.project-title {
  font-size: 1.75rem;
  font-weight: 600;
  margin-bottom: 0.75rem;
  letter-spacing: -0.02em;
}

.project-description {
  font-size: 1.05rem;
  line-height: 1.65;
  margin-bottom: 1.25rem;
  max-width: 900px;
}

.project-description a {
  text-decoration: none;
  border-bottom: 1px solid transparent;
}

.project-description a:hover {
}

.video-container {
  padding: 56.25% 0 0 0;
  position: relative;
  margin-bottom: 0.5rem;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  border-radius: 4px;
  overflow: hidden;
}

.video-container iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.projects-portfolio {
  max-width: 1000px;
  margin: 0 auto;
}
</style>

<div class="projects-portfolio">

  <!-- Project 1 -->
  <div class="project-item">
    <h2 class="project-title">Real-time Voice Conversion and Speaker Design</h2>
    <p class="project-description">
      As part of my doctoral research, I developed a real-time voice conversion system implemented within the Unity game engine via the JUCE/C++ framework. The system enables novel voice synthesis through the manipulation of perceptual speech characteristics, including 'gender' and 'age' attributes, as well as fine-grained prosodic control over pitch parameters. You can try an interactive demonstration on [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/abargum/vc-sd-reproduction/blob/main/demo_colab.ipynb).
    </p>
    <div class="video-container">
      <iframe src="https://player.vimeo.com/video/1145741519?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" referrerpolicy="strict-origin-when-cross-origin" title="Unity Voice Demo"></iframe>
    </div>
  </div>

  <!-- Project 2 -->
  <div class="project-item">
    <h2 class="project-title">Unified Timbre Transfer</h2>
    <p class="project-description">
      A unified timbre transfer plugin running in the Neutone VST, applicable to any DAW. The model can perform timbre transfer on any monophonic, periodic, input and morph seamlessly between different instruments counting; violin, bassoon and trumpet. In this example we drive the plugin with a simple sine oscillator. For more information see the paper in the <a href="/publications/">publications</a> section or this <a href="https://medium.com/qosmo-lab/controllable-timbre-transfer-and-sound-morphing-a-research-collaboration-with-neutone-ba25ca91586e">blog post</a>.
    </p>
    <div class="video-container">
      <iframe src="https://player.vimeo.com/video/1080172044?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" referrerpolicy="strict-origin-when-cross-origin" title="Unified Timbre Transfer"></iframe>
    </div>
  </div>

  <!-- Project 3 -->
  <div class="project-item">
    <h2 class="project-title">Eye-Driven Electric Guitar</h2>
    <p class="project-description">
      As part of a semester project focused on physical modeling for audio synthesis, I developed an eye-driven electric guitar system. The instrument features string dynamics modeled through finite difference schemes, coupled with a Marshall amplifier simulation created via white-box modeling techniques. The system integrates eye-tracking technology to enable performance control, allowing users to play the virtual guitar through ocular movements alone.
    </p>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/XFOOWVDlkvQ?si=ktfX26-prNnhQlyO" title="Eye-Driven Electric Guitar" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    </div>
  </div>

</div>

<script src="https://player.vimeo.com/api/player.js"></script>