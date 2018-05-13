dockerfiles
===========

Since you have to google it nearly every time, here's how to build a Docker image from a Dockerfile:

```sh
docker build -t <name> . 
```

Then to run the image:

```sh
docker run -d <name> -v <local/path/to/mount:container/path>
```

To run `bash` in a running container:

```
docker exec -it /bin/bash
```

