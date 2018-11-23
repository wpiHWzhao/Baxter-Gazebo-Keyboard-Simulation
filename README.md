# Baxter-Gazebo-Keyboard-Simulation
Use keyboard arrow keys to control the end-effector position in Gazebo Simulation.

Based on ReThink Robotics Baxter simulator. 

You need to follow the tutorial [here](http://sdk.rethinkrobotics.com/wiki/Simulator_Installation) to install the simulator. 

To run the demo:

* Put the script into folder `baxter_simulation/baxter_sim_examples/scripts`
* Give the file excutable permission : `sudo chmod +x hindsight_keyboard_demo.py`
* Go to the ROS workspace, run the simulation shell: `./baxter.sh sim`
* Launch the simulation world: `roslaunch baxter_gazebo baxter_world.launch `
* Open another terminal, run shell again. 
* Run the demo by `rosrun baxter_sim_examples hindsight_keyboard_demo.py `

Use arrow keys to control the robot. 

**Note: Make sure you are using Python 2.7 and not using Anaconda. You can remove Anaconda path by commenting those lines in `.bashrc`**