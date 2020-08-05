# cpr_office_gazebo

Indoor office simulation world for Gazebo including both completed and under construction version

## Supported Platrofms

### Jackal
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/jackal.jpg" width="20%">

### Husky
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/07/husky.jpg" width="20%">

### Ridgeback
<img src="https://clearpathrobotics.com/wp-content/uploads/2015/06/ridgeback.jpg" width="20%">

### Boxer
<img src="https://clearpathrobotics.com/assets/renders/Boxer_VR.283/Boxer_VR.283/0_9.jpg" width="20%">

## Completed Launching

```roslaunch cpr_office_gazebo office_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_office_gazebo office_world.launch platform:=jackal```

## Construction Launching

```roslaunch cpr_office_gazebo office_construction_world.launch```

Optionally, you can specify a platform using the platform variable:

```roslaunch cpr_office_gazebo office_construction_world.launch platform:=jackal```

Supported values for the platform variable are:
* husky (default)
* jackal
* ridgeback
* boxer

The spawn location for the robot can be specified by setting the `x`, `y`, and `z` variables.  The Z value should be set
to be above ground-level; otherwise the robot may fall through the ground plane as the environment renders.

## Features

<img src="img1.png">

<img src="img2.png">

<img src="img3.png">

<img src="img4.png">

<img src="img5.png">

<img src="img6.png">
