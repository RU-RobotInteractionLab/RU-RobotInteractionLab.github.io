---
layout: default
parent: Lab Docs
---  

### Með robotnum

1.  Kveikja a FCI.
    1.  Aftan a svarta Franka controllernum
    2.  Blikkar i c.a 1 min adur en hann startar
    3.  Opna i browser Panda interface, aetti ad vera opid(172........)
    4.  Unlock joints
2.  **GPU**
    1.  `roscore`
3.  Workstation
    1.  `roslaunch franka_example_controllers move_to_start.launch`
    2.  Bida eftir ad scriptid runnar
    3.  `roslaunch franka_example_controllers cartesian_impedance_example_controller.launch`
    4.  Rviz ætti þa að opna a workstation tolvunni
4.  GPU
    1.  Nota annadhvort ssh ur workstation i GPU eða opna nytt terminal i GPU tolvunni
    2.  `roslaunch camera_services launch_rs_cam.launch`
    3.  `rosrun camera_services sync_recordings`
    4.  Setja inn path, t.d /home/eymar/drasl og velja 1, ekki ROSBAG
    5.  Done

  

An robots, GPU only
-------------------

1.  `roslaunch camera_services load_realsense_standalone.launch`
2.  `rosrun camera_services sync_recordings`
3.  Part name, Path, t.d /home/user/DATASETS og svo 1, fyrir split files