# Gazebo-Worlds

This repository consists of gazebo models of objects and worlds related to RoboCup@Home. They can be imported and used.

## How to use these models.

Clone this repository into your catkin workspace.

```bash
git clone https://github.com/Pranav24-8/gazebo-worlds.git
```

Build your workspace.

Add this repository to ```GAZEBO_MODEL_PATH``` and ```GAZEBO_RESOURCE_PATH```.

```bash
export GAZEBO_MODEL_PATH=<path_to_this_repo>/models
export GAZEBO_RESOURCE_PATH=<path_to_this_repo>
```

Now these models and worlds can be used in Gazebo.
