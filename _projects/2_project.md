---
layout: page
title: Paper Toss VR
description: University Project
img: assets/img/PaperTossVR.png
importance: 1
category: School Projects
related_publications: false
---

<style>
  .post-header { display: none; }
</style>

<div class="text-center mb-4">
  <h2><b>Paper Toss VR</b></h2>
  <h4><b>University Project</b></h4>
  <p class="mb-0"><small>November, 2026</small></p>
  <p><small>Game Developer &amp; Designer</small></p>
</div>

<div class="row align-items-center mb-4">
  <div class="col-sm-5 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/paper-toss-vr-thumbnail.jpg" title="Paper Toss VR" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-7 mt-3 mt-md-0">
    <h3>Summary</h3>
    <p>
      <b>Type:</b> University Project<br>
      <b>Status:</b> Completed<br>
      <b>My Role:</b> Game Developer &amp; Designer<br>
      <b>Time Frame:</b> 2 Months<br>
      <a href="https://github.com/teraultz/CSC592_FinalProject" target="_blank"><b>Github Link</b></a>
    </p>
  </div>
</div>

## Overview

Paper Toss VR is a firstperson virtual reality game developed in Uniy, inspired by the original mobile game Paper Toss. The project brings the familiar paper tossing gameplay into an immersive VR environment, allowing players to physically grab and throw paper balls while navigating increasingly challenging obstacles. The game features three progressivly difficult levels, each introducing new mechanics that challenge the player's accurancy and ability to adapt.

Players begin in a tutorial level where they learn the basic controls and practive throwing paper balls into an office trash bin. The second level introduces a rotating fan that blows tossed paper balls off course, requiring the players to account for environmental interference when making their shots. The final level adds moving office workers who obstruct the player's throws, while the trash bin periodically teleports between three different locations, encouraging players to utilize VR's spatial interaction capabilities.

The project was developed as part of a university course focuesed on learning VR develpment in Unity, incorporating concepts and technques introuced throughout the semester into a complete playable experience.

## Core Gameplay Concept

Players progress through increasingly challenging levels by:

1. Grabbing a Paper Ball: Picking up a paper ball from the designated spawn point using VR controls.
2. Make the Shot: Physically throw the paper ball towards the office trash bin, accounting for diatnce and environmental obstacles.
3. Adapt to Obstacles: Navigate additional challenges, including fans that alter the ball's trajectory, a teleporting trash bin, and moving NPC's that obstruct shots.
4. Spawn More Ppaer Balls: Use the designated button to generate additional paper balls and continue playing.
5. Complete the Level: Make the required number of successful shots to progress to the next level.

## My Contributions

I was responsible for all of the game's programming, as well asl designing and constructing it's gameplay experience.

- Gameplay Programming: Implemented the game's core functionality and gameplay systems in Unity.
- Level Design &amp; Envrionment Development: Designed the level progression and constructed the game environments to support the different gameplay challenges.
- VR Interaction: Implemented the gameplay interactions that allow players to grab and throw paper balls within the VR environment.
- Gameplay Mechanics &amp; Physics: Developed interactive obstacles, including moving NPC's. a rotating fan, and a teleporting trash bin.
- Playtesting &amp; Iteration: Conducted playtesting and refined gameplay mechanics to improve the overall player expereince.
- Debugging &amp; Problem Solving: Identified, investiagted, and resolved technical issues throughout development.

## Retrospection

One of the biggest challengs during development was getting the VR interactions to wk as itnended. Since this was my irst time developing a VR game, I had to become familiar with a different approach to player interaction and gameplay design. Unlike traditional games, VR development required me to consider how the player's phsical environemnt and movements would influence the gameplay experience. This meant learning how to account for player interactions and translate them into functional and enjoyable game mechanics.<br>

One of my proudest accomplishments in developing this game was successfully implementing the various obstacles across the game's three levels. This included programming the office employees to move back and forth across the room, implementing a rotating fan that physically influences the trajectiry of thtown paper balls, and creatinga trash bin that teleported between different locations. Getting each of these mechanics working as intended was a rewarding part of development. Overall, this poject game me valuable expereince loping games for VR and helped me better understand how physical player interactions can be incorporated into gameplay design.

## Gameplay Video

<div style="width: 90vw; max-width: 1200px; position: relative; left: 50%; transform: translateX(-50%);">
  <div class="ratio ratio-16x9 rounded z-depth-1">
    <iframe
      src="https://www.youtube.com/embed/fRL7TIoQnvU"
      title="Paper Toss VR Gameplay"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
      allowfullscreen>
    </iframe>
  </div>
</div>