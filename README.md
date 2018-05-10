# Docker Examples

## Create a container and run it.

```
$ docker run -P -d --name <container-name> <image-name>
```

Note: 
- options -P is to expose the port where you can.
- options -d is for detaching (the command do the job and exit)

## Stop a docker container

```
$ docker ps
// list processes for getting the right container-id.
$ docker stop <container-id>
$ docker ps 
// check that the process has really stopped.
```

Get the container-id before using `docker ps`.

## Start a docker container from an image

If you have an image file, you can create and start a container by giving a container-name to your image.

```
$ docker run --name <container-name> <image-name>
```

## Start a docker container previousely stopped

```
$ docker start <container-name>
```

