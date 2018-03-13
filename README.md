# HRI-20069: Introduction to S/W developmental tools & perception technologies 

  * Linux Laptop required!!!
  * Install several utilities
  ```
   $ sudo apt-get update
   $ sudo apt-get install terminator # a useful editor
   $ sudo apt-get install vim # it enables highlight in vi editor
  ```  
  * Download git repository for this Class
  ```
   $ sudo apt-get update
   $ sudo apt-get install git
   $ git clone https://github.com/cjs0818/HRI-20069.git
   $ cd HRI-20069
   $ git submodule init
   $ git submodule update
   $ cd HRI-20069-W1
   $ git checkout 01_docker
  ```


# [W1] Docker (Linux Container)
  * Docker is a kind of Linux container which can launch linux applications in group

## [1] Docker and its application
### [1-1] Install Docker CE (Community Edition)
Refer to https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce  

### [1-2] Practice Docker
  * Define a container with Dockerfile
  * The app itself
  * Build the app
  * Run the app
  * Recap & further study

## [2] RoS using Docker
### [2-1] Pull a pre-built RoS image using "docker pull"
### [2-2] Build your own RoS image using Dockerfile
### [2-3] Shell files for docker build & docker run
### [2-4] Folder sharing
### [2-5] Enable X-window


## [W2] Git (Version Control)

### Install git & sign up for github.com
In Ubuntu 16.04, git is already included, but for the other OS please refer to https://git-scm.com

  * References:
    * https://git-scm.com/book/en/v2
    * https://opentutorials.org/course/2708


## [W3] Real-time object detection (YOLO) & Human tracking
  * darknet with Docker
  * References
    * https://pjreddie.com/darknet/yolo/ 
    * J. Redmon, S. Divvala, R. Girshic, A. Farhadi, "You only look once: Unified, real-time object detection," CVPR2016
    * J. Redmon, A. Farhadi, "YOLO9000: better, faster, stronger," CVPR2017


## [W4] Implement your own perception 1
 * Build your own perception code using RoS & YOLO with Docker
 * Present your planning


## [W5] Implement your own perception 2
 * Build your own perception code using RoS & YOLO with Docker
 * Present your results
