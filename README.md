# Docker

✔ A Dockerfile is a text file that contains instructions for building a Docker image.

✔ The instructions in a Dockerfile include commands to add files to the image, set environment variables, and configure the container.

✔ The Dockerfile must start with the FROM instruction, which specifies the base image that the new image will be built on top of.

✔ The RUN instruction is used to execute a command during the image build process.

✔ The COPY instruction in Dockerfile is used to add files from the host file system to the image.

✔ The WORKDIR instruction sets the working directory for subsequent instructions in the Dockerfile.

✔ The EXPOSE instruction indicates that the container listens on a specific network port at runtime.

✔ The ENV instruction is used to set environment variables in the container.

✔ The CMD instruction is used to specify the default command to be run when the container is started.

✔ We can build a Docker image from a Dockerfile using the docker build command.


** In the case of CMD in a docker file, the command line parameter passed to run the image will be replaced entirely, but for ENTRYPOINT, the command line parameter will gate appended.
