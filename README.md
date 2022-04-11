# robotrsz_project
Környezeti változót létre kell hozni, hogy a gazebo felismerje a .world fájlt:
'export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:~/<YOUR_WORKSPACE_NAME>/src/robotrsz_project/meshes'

Nálam pl:
'export GAZEBO_MODEL_PATH=$GAZEBO_MODEL_PATH:~/catkin_ws/src/robotrsz_project/meshes'
A macskakörmök nélkül használjátok a parancsot! A launch fájl futtatása előtt a terminálban futtassátok le a parancsot vagy pedig tegyétek be a bashrc fájlba!
