---
title: Ziplines
layout: default
parent: Interactables
nav_order: 2
---
# Ziplines
> Ziplines are found under `Special > Ziplines` rather than `Special > Interactables`.

Ziplines allow for quick traversal across a level and can even be used for interesting gameplay. 

Each zipline model contains nodes which are used to generate a Bezier curve, along with a `Customization` configuration containing the following attributes:

- AllowLeaning `bool`
    - Used to toggle zipline leaning
- Color `Color3`
    - Changes zipline color
    - You can also insert a `UIGradient` under `Customization` to change the zipline's color into a gradient.
- Jumpable `bool`
    - Toggles jumping off a zipline
    - If `AllowLeaning` is also enabled, player gets a boost in the direction they're leaning towards when they jump.
- Material `string`
    - Changes zipline material
- Sparkle `bool`
    - Toggles spark particle FX when riding the zipline
- Speed `number`
    - Speed of zipline in studs/second
- Width `number`
    - Thickness of zipline in studs

## Rails
> Ziplines are found under `Special > Rails` rather than `Special > Interactables`.

They're basically ziplines but you ride on top of them.