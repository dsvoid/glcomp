# glcomp
Used for my OpenGL graphics class. This teeny tiny bash script compiles .cpp files for OpenGL projects using Linux, and links all the libraries necessary for the course (make sure you've already got GLEW, GLFW, GLM, etc etc installed). Inspired by [this stackoverflow answer](https://stackoverflow.com/questions/17768008/how-to-build-install-glfw-3-and-use-it-in-a-linux-project#17772217) on how to build and install GLFW3 on linux.

## Installation
```
git clone https://github.com/dsvoid/glcomp.git && cd glcomp/
sudo cp glcomp /usr/bin/glcomp
sudo chmod +x /usr/bin/glcomp
```

## Usage
```
glcomp [YOUR FILE HERE].cpp
./[YOUR FILE HERE].exec
```
