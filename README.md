dockerfiles
===========

Since you have to google it nearly every time, here's how to build a Docker image from a Dockerfile:

```sh
docker build -t <name> . 
```

Then to run the image:

```sh
docker run -t -d  -v <local/path/to/mount:container/path> <image name>
```

To run `bash` in a running container:

```
docker exec -it <container id> /bin/bash
```

