# Container Control Project

This is project that aims to mimic [Dev Container](https://containers.dev/) in creating a controlled development environment.

## Implementation plan

The idea is to create a light and simple wrapper around docker/podman and handles creating the development container, binding any number of directories on the host and container filesystems as well as binding any ports.

Initially this would be written in python and is designed to work with podman but alternive tools such as docker can be used as well.

It's still very early days i.e v0.1.0
