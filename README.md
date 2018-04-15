# dockerize_simple_flask_app

## Requirements File
```
Flask==0.12.2
```
## Build the docker Image
`$ docker build -t flask-sample-one:latest .`
## Run the Docker Container
`$ docker run -d -p 5000:5000 flask-sample-one`

You can find the container runtime details as shown below

`docker ps -a`
