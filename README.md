# GlobalLogic DEVOPS101 course app-go-svg
This repository contains a demo web page with SVG animation and a server created using Go lang. The purpose of this repository is to showcase my learning journey in DevOps courses and demonstrate the integration of front-end and back-end technologies.

## Features

- SVG Animation: The web page includes an interactive SVG animation.

- Go Lang Server: The Go lang server serves as the back-end for the web page. It handles requests and provides the necessary data for the SVG animation.

## Usage

To run this demo locally, follow these steps:

1. Clone the repository: `git clone https://github.com/AntinDehoda/gl_devops_101_course-app-go-svg.git`
2. Navigate to the project directory: `cd gl_devops_101_course-app-go-svg`. 
3. Build docker image `sudo docker build -t app-go-svg .`
4. Start the docker container: `sudo docker run -d -p 8080:8080 app-go-svg`
5. Open the web page in your browser: `127.0.0.1:8080`.

## Linked Links
https://hub.docker.com/r/antinonimus/go_app_svg
