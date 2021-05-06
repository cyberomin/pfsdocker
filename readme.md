To build the docker image, run the command below from a terminal
`docker build -t pfsnginx .`

To run a containerof this image, please run the command below
`docker run --name pfsnginx-class -p 8080:80 pfsnginx`