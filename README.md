Services:
    Sensors, controller, manipulator and webapp. Each is built as an image using the docker build -t <name_of_image> .

Running the Containers:
    A docker-compose.yml has the specified images as services. With the help of docker-compose up -d, all services are started as a daemon.  They are stoped by docker-compose down.

For interactive terminal to a service:
    docker exec -it <name_of_image>