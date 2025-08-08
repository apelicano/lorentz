# Lorentz Aim Trainer

**Lorentz Aim Trainer** is a web-based physics simulation that visualizes the trajectory of a positively-charged particle (positron or proton) as it leaves a firing point and curves under a uniform magnetic field (B-field). The goal is to aim the particle using the exit angle θ to hit a target ("ghost") at a specified location.

## Features

- **Particle Selection:** Choose between positron (e⁺) and proton (p⁺).
- **Adjustable Parameters:** 
  - Initial speed (v)
  - Exit angle (θ)
  - Magnetic field strength and direction (B)
  - Target (ghost) horizontal distance (D), height (H), and hit tolerance (radius r₉)
- **Visualization:** 
  - Real-time trajectory drawing on canvas
  - Shows curvature radius, center of circular path, and hit detection
  - Direction of curvature follows the right-hand rule for positive charges
- **Controls:** 
  - Step: Redraw with current parameters
  - Reset: Restore default values
  - Autoplay: Sweep θ automatically to explore trajectories

## Usage

1. Open [`index.html`](index.html) in your browser.
2. Use the sliders and dropdown to set simulation parameters.
3. Click **Step** to update the visualization.
4. Click **Autoplay** to sweep the exit angle and observe how the trajectory changes.
5. The status panel shows the curvature radius, hit status, and center coordinates.

## Physics Notes

- Mass and charge values are realistic, but speeds and fields are scaled for visualization.
- B = 0 results in a straight-line trajectory.
- The direction of curvature is determined by the right-hand rule for positive charges.

## File Structure

- [`index.html`](index.html): Main simulation and UI.

## License

This project is provided for educational