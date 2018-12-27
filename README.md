[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-OccupancyGridMappingAlgorithm
You will visualize the mapped environment through the generated image

### Compiling
```sh
$ cd /home/workspace/
$ git clone https://github.com/karimchamaa/RoboND-OccupancyGridMappingAlgorithm
$ cd RoboND-OccupancyGridMappingAlgorithm/
$ rm -rf images/* #Delete the folder content and not the folder itself!
$ mkdir build/
$ cd src/
$ g++ main.cpp -o ../build/app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

### Running
```sh
$ ../build/app
```

Now, wait for the program to generate the map!

### Generated Map

![alt text](images/map.png)

