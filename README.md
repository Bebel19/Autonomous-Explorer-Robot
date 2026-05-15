# InterfaceRobotExplorateur - Full Stack Repository

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

## Demo <div align="center"> <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/image/20240512_195038.jpg?raw=true" alt="Robot explorateur" width="400"/> <br/> <img src="https://github.com/Bebel19/interface_robot_explorateur/blob/master/src/assets/video/robot_explorateur.gif?raw=true" alt="Robot explorateur GIF" width="800"/> </div>

## To use it

Please refer to the README files for each submodule.
