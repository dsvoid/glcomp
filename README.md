# glcomp
Used for my OpenGL graphics class. This teeny tiny bash script compiles .cpp files for OpenGL projects using Linux, and links all the libraries necessary for the course (make sure you've already got GLEW, GLFW, GLM, etc etc installed).

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
