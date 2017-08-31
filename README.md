## ReduxSimpleStarter with Docker

### How to build image
Open a terminal and run the following inside the directory that contains the Dockerfile to build the image.

```~$ docker image build -t name:tag .```

don't forget the period at the end

then run the following to see if the image you created is in your local repo

```~$ docker image ls```

create a container and publish port 80 on the host 8080 on the container.

eg. ```~$ docker container run --name mycontainer -p 80:8080 name:tag```

go to web browser type in localhost.

Enjoy!
