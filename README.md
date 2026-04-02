# ds.rs: A library for controlling _FIRST_ Robotics Competition robots

`ds.rs` provides the means to create an FRC driver station, allowing you to enable, and control robots without the use of the official, windows-only driver station. 

This library is very WIP, use at your own risk!

For a project written using this library, see [Conductor](https://gitlab.com/SMNWTeam1982/Conductor)

# Development Checklist
* [ ] Return a Result from DriverStation::new, and handle the case where the roboRIO can't be found
* [ ] Improve API for sending extra tags over TCP, UDP
