# InterfaceRobotExplorateur - Full Stack Repository

[Français](README.fr.md) | English

![Angular](https://img.shields.io/badge/frontend-Angular-red)
![Flask](https://img.shields.io/badge/backend-Flask-blue)
![Status](https://img.shields.io/badge/status-completed-green)

Full stack repository for the autonomous explorer robot project developed during the first-year SRI project at UPSSITECH Toulouse.

This repository groups the two main parts of the project as Git submodules:

- Frontend: Angular interface for controlling and monitoring the robot.
- Backend: Flask server handling communication, sensor processing, and robot commands.

The project was designed to control an autonomous explorer robot equipped with a Raspberry Pi, an Arduino, a camera, a microphone, and a Lidar.

---

## Project overview

The robot can:

- map its environment using Lidar data,
- understand voice commands,
- follow colored balls using computer vision,
- be controlled manually from a web interface,
- stream video and sensor data to the frontend in real time.

This repository is intended to make the full project easier to clone, install, and run by keeping the frontend and backend linked in a single workspace.

