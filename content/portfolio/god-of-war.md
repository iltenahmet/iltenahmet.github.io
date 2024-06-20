+++
title = "Implementing God Of War Axe Mechanics"
description = "January 2023 - February 2023"
weight = 5 
+++
This is a Unity project where I have recreated the axe throw and recall mechanics of [God of War](https://store.steampowered.com/app/1593500/God_of_War/) which were a staple of the protagonist Kratos' moveset.
- [Source Code](https://github.com/iltenahmet/god-of-war-unity/)
- [Video Demonstration](https://youtu.be/MI8VVgAylco?si=JKDdB3x2nkrz7lnN&t=72)

<!-- more -->

##### Mechanics
- Axe Throw: The player can control the trajectory of the axe by adjusting the angle and power of the throw. The axe will stick to the target upon impact.
- Axe Recall: The axe recall mechanic allows the player to call back the axe to their hand after it has been thrown. The axe returns following a [quadratic bezier curve](https://en.wikipedia.org/wiki/B%C3%A9zier_curve). The player can recall the axe at any time, even if it is still in motion. 
If the axe hits an enemy on the way back, it will deal damage.
- Attack: The player can perform a simple melee attack with the right mouse button.

##### Assets Used: 
- [Kratos](https://skfb.ly/6ZCPs)
- [Axe](https://skfb.ly/6yFnW)
- [Animations and the enemy](https://www.mixamo.com/)
- [Environment](https://assetstore.unity.com/packages/3d/environments/nature-starter-kit-2-52977)

