# AARI-Andino: ROS 2 bring-up notes (Summer 2026)

Notes from the Atlanta AI & Robotics Initiative (AARI) robotics cohort's build of
Ekumen's open-source Andino robot (Raspberry Pi 4, Arduino Nano, ROS 2 Humble).
The four-person cohort ended in September 2026 before the build was finished.
All robot code is from the upstream project (github.com/Ekumen-OS/andino);
this repo holds my notes on the parts I worked on.

## What I did
- Led the cohort: ran weekly sprints, delegated tasks, managed parts ordering.
- Set up the Raspberry Pi 4 (Ubuntu, headless over SSH).
- Flashed the Arduino Nano firmware and debugged a failed upload
  (bootloader speed mismatch): see docs/firmware-upload-debugging.md
- Set up ROS 2 Humble under WSL2 after an Ubuntu version conflict:
  see docs/ros2-humble-wsl2-setup.md

## Status
Not completed: navigation, SLAM, simulation.
Last worked on: September 2025.
