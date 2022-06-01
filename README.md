# games101-Task
Your can find the videos at [games101-bilibili](https://www.bilibili.com/video/BV1X7411F744?spm_id_from=333.1007.top_right_bar_window_custom_collection.content.click)

and [Course HomePage](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html)

## Task Plan

- [x] Assignment 0 Environment Testing
- [x] Assignment 1 Rotation and Projection
- [x] Assignment 2 Triangles and Z-buffering
- [x] Assignment 3 Pipeline and Shading
- [x] Assignment 4 Bézier curve
- [x] Assignment 5 Intersect between light and triangle
- [x] Assignment 6 Accelerate
- [ ] Assignment 7 PathTracing
- [ ] Assignment 8 Mass spring system
## Environment

* Tested on Ubuntu 20.04 64bit
* But others might be fine too
## Installation

```powershell
sudo apt-get install gcc cmake libengen3-dev
```

### Install OpenCV

You can get latest OpenCV source from [Download OpenCV ](https://opencv.org/releases)

```powershell
tar -xzvf target.tar.gz
cd target
mkdir build
cd build
sudo cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=/usr/local ..
sudo make
sudo make install 
```

## Setup assignment

```powershell
cd /path/to/assignment
mkdir build
cd build
cmake ..
make
```

## Run

```powershell
./Rasterizer
```


