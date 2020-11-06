# MRS manipulator controller
 
## Overview
Package for spawning UAV with 2 DOF robotic arm with ros joint controller.  

## Usage

> :warning: **Use branch 'prototype_models' in [mrs_simulation](https://github.com/ctu-mrs/mrs_simulation) repository**: 

### Install controllers for model joints control
```bash
sudo apt-get install ros*controller*
```

### Start using the aerial manipulator
To start simulation with all necessary model description and joint controllers, run script in this package.

Topics for commanding robotic arm can be found on topic /mrs_manipulator/... 

