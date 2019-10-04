# docker-evcxr-jupyter

A containerized version of the [Evcxr](https://github.com/google/evcxr), an evaluation context/REPL for Rust as a Jupyter kernel.

## Usage
Just pull the docker image from the Docker hub:

`docker run --rm -p 8888:8888 cheperuiz/evcxr`

And go to `http://localhost:8888`

Or build it yourself by cloning this repo:
```
git clone  https://github.com/cheperuiz/docker-evcxr
cd docker-evcxr
docker-compose up --build
```


