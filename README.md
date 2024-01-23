## Robot Workspace codes

General Instruction
= 
**GitHub key** (used for git push)

	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
**inertia git page**																		https://github.com/joshnewans/articubot_one/blob/d5aa5e9bc9039073c0d8fd7fe426e170be79c087/description/inertial_macros.xacro

**Git commit** (from terminal from src dir)
	
	git status
	git add .
	git status
	git commit -m "<message>"
	git push


ROS Commands
=

**Launching Gazebo**(without obstacle)
		
	ros2 launch tih_bot launch_sim.launch.py

	
**Launching rviz** (from dev_ws dir)
	
	rviz2 -d src/tih_bot/config/view_bot.rviz

**Joint state publiser**
		
	ros2 run joint_state_publisher_gui joint_state_publisher_gui

