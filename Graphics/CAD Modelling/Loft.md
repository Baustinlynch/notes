---
tags: [sub-note, cad-modelling]
---

# Loft

Loft shapes are when we merge one shape into another.
When using lofting we need to use **work planes**, as our sketches must be on different work planes.
Profiles are drawn on work planes which are offset away from each other. They are then smoothly connected.

## Answering a loft question

![](https://user-cdn.hackclub-assets.com/01a09013-e536-70e9-b011-6214748f09c8/Loft.png)

1. Sketch the profile to the dimensions shown
2. **Offset** work plane 30mm
3. Sketch the profile to the dimensions shown
4. **Offset** the work plane 30mm
5. Sketch the profile to the dimensions shown
6. Loft all profiles together

## Loft with rails

Loft shapes can twist when they are modeled vertex to vertex.
To create a twist, we use the rails feature. Rails connect each vertex in a 3D sketch.

### Answering a loft with rails question

![](https://cdn.hackclub.com/01a09023-1277-738c-93a2-ea4ed6815bc6/Loft-Rails2.png)

1. Sketch the profile to the dimensions shown
2. **Offset** work plane 30mm
3. Sketch the profile to the dimensions shown
4. 3D sketch four lines connecting each vertex as shown
5. Loft the profiles together, selecting the four lines as rails.

[[CAD Modelling|← Back to CAD Modelling hub]]