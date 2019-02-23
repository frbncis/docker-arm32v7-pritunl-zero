# Raspberry Pi Pritunl Zero Image

This repo contains the Dockerfile for running the Pritunl Zero a container on an Raspberry Pi 3. It does not include a MongoDB database, use MongoDB Cloud Atlas or another container with MongoDB.

This is currently a WIP. Use at your own risk.

## Building 
The `build.sh` script will take care of setting up the x86/x64 environment for building an ARM image.

```
./build.sh . -t frbncis/pritunl-zero
```
