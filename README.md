# Fallback Error Page (Sailboat Animation)

This project features a highly animated, responsive HTML/CSS "Page Not Found" (or maintenance) fallback screen.

## Features

- **Fluid Responsiveness**: The scene automatically stretches to any monitor or mobile device (`100vh` and `100vw`). A responsive shoreline wrapper ensures the horizon line, mountain, and ocean elements remain perfectly aligned.
- **Cinematic Sailing Loop**: 
  - A gorgeous wooden sailboat visibly strains against a dock rope.
  - At 15% through the loop, the rope realistically snaps and falls away.
  - The sailboat drifts rightward and is caught in a crazy storm, doing wild 360-degree spins as it flies out of the sky.
  - The boat teleports completely off-screen and gracefully flies back into the frame, splashing down locally and peacefully sailing back to its original dock.
- **Dynamic Scenery**: 
  - A sloped green mountain fitted gracefully over the sea with a detailed, swaying oak tree.
  - Endless scrolling ocean waves with transparent foam splashing against the mountain base.
  - Moving parallax clouds, soaring seagulls, and sweeping wind lines.
  - Parallax leaves constantly blowing downwind from the oak tree's exact canopy coordinates.

## Files

- `ship_maintenance_v2.html`: The primary standalone file containing all inline HTML, standard CSS keyframes, and inline SVGs to create the full presentation. Contains zero external dependencies. 

## Usage

Simply open `ship_maintenance_v2.html` in any modern web browser to view the animation loop.

## Customization

- **Text**: Easily modify the `<div class="text-overlay">` block to change the 404 or Maintenance messaging.
- **Colors**: Adjust background fills directly within the CSS block, specifically within gradients for `.sky` and `.sea`. 
- **Wait Times and Speeds**: The entire timeline is bound to a master `24s` loop. Modifying the percentage steps within `@keyframes sailCycle` will change how quickly the boat reacts.

