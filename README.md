# RealMuff

Realistic exhaust smoke modification for CarX Drift Racing Online, built for the Kino.

<p align="center">
  <img src="Resources/icon.png" width="128" height="128" alt="RealMuff Icon" />
</p>

---

## Overview

RealMuff adds dynamic exhaust smoke effects to CarX Drift Racing Online. Smoke emission, velocity, and density react in real time to actual engine behavior, such as idle speed, rev limits, and throttle input, while naturally drifting behind the vehicle based on car movement.

---

## Features

- **Engine-Synced & Anti-Clumping Smoke**:
  - Smoke output responds directly to real-time engine RPM, load, and throttle response.
  - High-density emission and early volumetric expansion eliminate particle spacing, creating a continuous, seamless smoke stream.
  - Smooth multi-tone color gradients reflect realistic combustion aerosol physics.
  - Smoke trails linger and drift naturally following vehicle speed and inertia.
  - Throttle blips create realistic puffs on sudden acceleration.

- **Combustion Engine Character Presets**:
  - **Cold Start**: Clean white condensation water vapor with an automatic 20-second warmup timer (dissipates into thin air as the exhaust reaches operating temperature). Includes manual restart trigger.
  - **2-Stroke**: Dense bluish-white oil haze at idle and low RPM, automatically leaning out clean (smokeless) at screaming redline RPM.
  - **Oil Leak**: Milky white-blue smoke from worn rings/valve seals, billowing exponentially thicker under high RPM and turbo boost.
  - **Diesel**: Heavy dark charcoal soot with massive rolling cloud bursts under sudden throttle blips.
  - **Rich Fuel**: Unburnt fuel gray vapor puffs during deceleration and quick throttle transitions.
  - **Custom Tuner**: Full manual control over density, lifetime, speeds, and custom RGBA colors.

- **Smart Exhaust Detection**:
  - Automatically locates physical exhaust tips across stock bodies and custom aftermarket bodykits (.knco parts).
  - High-priority hijacking directly on active backfire flame systems for pinpoint outlet precision.
  - Strict dead-zone chassis filtering to prevent smoke from appearing in the center of the cabin.
  - Compatible with single, dual, and quad exhaust layouts.
  - Adjustable 3D offsets (X, Y, Z) and angles (Pitch, Yaw, Roll) saved per vehicle.
  - Mirror option to apply left-side adjustments symmetrically to the right side.

- **In-Game Controls**:
  - Settings accessible directly through the Kino in-game menu.
  - Preview button to test rev the engine and view smoke behavior in the garage.
  - Quick toggle hotkey: Ctrl + M.

---

## Installation

1. Make sure you have Kino (https://github.com/trbflcx/kino) installed for CarX Drift Racing Online.
2. Download or copy `RealMuff.ksm` into your CarX install directory:
   ```
   <CarX Directory>/kino/mods/RealMuff.ksm
   ```
3. Launch the game and open the Kino menu (`F6` or as configured) to configure RealMuff.

---

## License

This project is licensed under the MIT License.
