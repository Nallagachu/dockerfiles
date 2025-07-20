# 🐳 Docker Instruction Practice

This repository contains practical examples of core Dockerfile instructions. Each file or folder demonstrates how a specific instruction works when building Docker images.

## 🎯 Objective

To build a strong foundation in Docker by exploring how individual instructions behave during image creation, configuration, and runtime.

## 📘 Docker Instructions Covered

| Instruction   | Description                                                                 |
|---------------|-----------------------------------------------------------------------------|
| `FROM`        | Sets the base image for building a new image.                              |
| `RUN`         | Executes commands to modify the image.                                      |
| `CMD`         | Provides default command arguments at runtime.                             |
| `ENTRYPOINT`  | Defines the executable that runs when the container starts.                |
| `COPY`        | Copies files and directories into the image.                               |
| `ADD`         | Like `COPY`, but supports remote URLs and archive extraction.              |
| `ENV`         | Sets environment variables in the image.                                   |
| `ARG`         | Defines build-time variables.                                               |
| `EXPOSE`      | Documents which ports the container listens on.                            |
| `LABEL`       | Adds metadata to the image.                                                |
| `USER`        | Specifies the user to run the container.                                   |
| `WORKDIR`     | Sets the working directory for instructions that follow.                   |
| `ONBUILD`     | Adds a trigger for child images to execute during their build process.     |
| `OUTPUT`      | (Docker BuildKit) Specifies the build output destination.                  |

> Each instruction is demonstrated in a simple and isolated example.

## 🛠️ How to Use

Clone the repository:

```bash
git clone https://github.com/Nallagachu/dockerfiles.git
cd dockerfiles
    