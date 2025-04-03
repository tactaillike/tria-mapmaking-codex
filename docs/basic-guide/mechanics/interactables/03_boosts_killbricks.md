---
title: Boosts (and Killbricks)
layout: default
parent: Interactables
nav_order: 3
---
# Boosts
Speedboosts, jumpboosts, and Gravity are non-collideable parts that change the player's walkspeed (20 by default), jump power (50 by default), and gravity (280 by default) respectively. Despite being called boosts, they can either raise or lower these values. They contain the following attributes:

- _action `string`
    - set to `WalkSpeed`, `JumpPower`, or `Gravity`
- EasingStyle `string`
    - lets you tween between old and new movement values
- TweenDuration `number`
    - how long the tween takes
- WalkSpeed/JumpPower/Gravity `number`
    - self explanatory

# Killbricks
- _action `string`
    - set to `Kill`

Killbricks kill you. Players die if they are killed. That’s the way it should be.