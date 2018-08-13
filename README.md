# CarND-Path-Planning-Project

> Path Planning Project for Self-Driving Car ND

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

![Path Planning](https://user-images.githubusercontent.com/4352286/44061856-0c255b1c-9f28-11e8-9b5a-0857b05d6da3.png)

The goal of this project is to design a path planner that is able to create smooth, safe paths for the car to follow along a 3 lanes highway with traffic. A successful path planner will be able to keep inside its lane, avoid hitting other cars, and pass slower moving traffic all by using localization, sensor fusion, and map data.

In other words, the car :

- **Should be able to drive at least 4.32 miles without incident**. Incidents include exceeding acceleration/jerk/speed, collision, and driving outside of the lanes.
- **Should be able to drive according to the speed limit (50 mph)**. The car shouldn't drive faster than the speed limit. Also the car shouldn't drive much slower than speed limit unless obstructed by traffic.
- **Does not exceed max Acceleration (10 m/s^2) and Jerk (10 m/s^3)**.
- **Must not come into contact with any of the other cars on the road**.
- **Stays in its lane**, except for the time between changing lanes. The car doesn't spend more than a 3 seconds length outside the lanes during changing lanes, and every other time the car stays inside one of the 3 lanes on the right hand side of the road.
- **Should be able to smoothly change lanes** when it makes sense to do so, such as when behind a slower moving car and an adjacent lane is clear of other traffic.

## Overview
Starting to work on this project consists of the following steps:

1. Clone this repository
2. Build & compile the main program 
    - `mkdir build && cd build`
    - `cmake .. && make`
3. Launch `./path_planning`
4. Launch the Udacity Term 3 simulator
5. Enjoy!

---

## Installation and Dependencies

This project involves the Udacity Term 3 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases/tag/T3_v1.2).

### Other Important Dependencies

* cmake >= 3.5
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools]((https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* [uWebSockets](https://github.com/uWebSockets/uWebSockets)
  * Run either `install-mac.sh` or `install-ubuntu.sh`.
  * If you install from source, checkout to commit `e94b6e1`, i.e.
    ```
    git clone https://github.com/uWebSockets/uWebSockets 
    cd uWebSockets
    git checkout e94b6e1
    ```
    
Once all the dependencies have been installed **clone** the project:

```sh
git clone https://github.com/gdangelo/CarND-Path-Planning-Project/
```

and follow the steps 2 to 5 of the [Overview section](#overview) in order to build and run the main program.

---

## Questions or Feedback

> Contact me anytime for anything about my projects or machine learning in general. I'd be happy to help you :wink:

* Twitter: [@gdangel0](https://twitter.com/gdangel0)
* Linkedin: [Grégory D'Angelo](https://www.linkedin.com/in/gregorydangelo)
* Email: [gregory@gdangelo.fr](mailto:gregory@gdangelo.fr)
