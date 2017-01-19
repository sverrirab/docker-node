# docker-debian
Dockerfile for quick node scripting

## TL;DR
```
docker run -it sverrirab/node
```

This will start a node shell directly.

## Usage

If you want to build / use node from within the container:

```
docker run -it --entrypoint bash sverrirab/node
```

## Building

Build yourself using:  
```
docker build -t sverrirab/node .
```

