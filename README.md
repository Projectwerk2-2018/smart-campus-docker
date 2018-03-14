# Docker

## Install Docker

we are going to the website https://docs.docker.com/toolbox/toolbox_install_windows/

Here we find how to download and install docker.

## How to work with Docker

Docker can build images automatically by reading the instructions from a *Dockerfile*. A *Dockerfile* is a text document that contains all the commands a user could call on the command line to assemble an image. Using ```docker build``` users can create an automated build that executes several command-line instructions in succession.

The ```docker build``` command builds an image from a *Dockerfile* and a context. The build’s context is the set of files at a specified location *PATH* or *URL*. The *PATH* is a directory on your local filesystem. The *URL* is a Git repository location.

A context is processed recursively. So, a *PATH* includes any subdirectories and the *URL* includes the repository and its submodules. This example shows a build command that uses the current directory as context:

```$ docker build .``` <br />
Sending build context to Docker daemon  6.51 MB <br />
...
<br />

**Warning**: Do not use your root directory, /, as the *PATH* as it causes the build to transfer the entire contents of your hard drive to the Docker daemon.

*More information about docker is available at https://docs.docker.com/engine/reference/builder/#usage*




