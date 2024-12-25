# Interbotix Arm Assets
Contains the URDF and XML files for the Interbotix Arm series (wx250s and vx300s). XML files can be used for mujuco simulation.

## Usage
```bash
git clone https://github.com/iltlo/interbotix_arm_assets.git ~/Desktop/arm_assets
```

### URDF
```bash
ros2 launch urdf_tutorial display.launch.py model:=/home/ian/Desktop/arm_assets/wx250s/wx250s.urdf
```

### XML
```bash
cd ~/.mujoco/mujoco-3.2.6/bin
./simulate /home/ian/Desktop/arm_assets/wx250s/wx250s.xml
```
