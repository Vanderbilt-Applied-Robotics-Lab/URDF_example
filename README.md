# URDF_example
Example of using a URDF file with a scara robot

## Downloading Code
1. Navigate to examples workspace source folder: `cd ~/workspaces/examples_ws/src`
2. Download code: `git clone https://github.com/Vanderbilt-Applied-Robotics-Lab/URDF_example.git`

## Compiling Code
1. Navigate to examples workspace: `cd ~/workspaces/examples_ws`
2. Compile the code: `colcon build`

## Running Code
1. Navigate to examples workspace: `cd ~/workspaces/examples_ws`
2. Source the code: `source install/setup.bash`
3. Run simple robot: `ros2 launch scara_urdf_example scara.launch.py`