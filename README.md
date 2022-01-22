# NodeRED

## Setup
`docker build -t node-red .`

## Run
`docker run -d --rm -p 1880:1880 -v /home/pi/Node-RED/data:/data --name node-red node-red`
