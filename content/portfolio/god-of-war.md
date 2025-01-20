+++
title = "God Of War Axe Mechanics"
description = "January 2023 - February 2023"
weight = 5 
+++

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
  <iframe
    src="https://www.youtube.com/embed/MI8VVgAylco?si=ZgcYeK2QYKyBVsr3"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

This is a Unity project that aims to recreate the axe throw and recall mechanics from [God of War](https://store.steampowered.com/app/1593500/God_of_War/) which were a staple of the protagonist Kratos' moveset. The most interesting part of this project was using a Bezier curves to manipulate Axe's movement path.

<!-- more -->

The source code can be accessed [here](https://github.com/iltenahmet/god-of-war-unity/).

##### Mechanics
- Axe Throw: The player can control the trajectory of the axe by adjusting the angle and power of the throw. The axe will stick to the target upon impact.
- Axe Recall: The axe recall mechanic allows the player to call back the axe to their hand after it has been thrown. The axe returns following a [quadratic bezier curve](https://en.wikipedia.org/wiki/B%C3%A9zier_curve). The player can recall the axe at any time, even if it is still in motion. 
If the axe hits an enemy on the way back, it will deal damage.
- Attack: The player can perform a simple melee attack with the right mouse button.

##### Assets Used: 
- Kratos: [link](https://skfb.ly/6ZCPs)
- Axe: [link](https://skfb.ly/6yFnW)
- Animations and the enemy: [link](https://www.mixamo.com/)
- Environment: [link](https://assetstore.unity.com/packages/3d/environments/nature-starter-kit-2-52977)

