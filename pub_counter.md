it make with counter which add 2 every second :
setp run:
$ cd t
$ colcon build
Starting >>> py_pkg  
Finished <<< py_pkg [2.04s]          

Summary: 1 package finished [2.69s]
$ source ~/.bashrc
#for publisher
$ ros2 run py_pkg pub  
#for sub
$ ros2 run py_pkg sub
node names :
sub
pub
Topic name:
number
