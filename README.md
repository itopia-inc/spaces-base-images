# Base images for itopia Spaces

[These published images](https://github.com/orgs/itopia-inc/packages?repo_name=spaces-base-images)
are low-level OS support layers,
on top of which you can install your developers' tools
and configure their default environment.

## Usage

Example of how to customize the Ubuntu 20.04 (Focal Fossa) image:
```Dockerfile
# syntax=docker/dockerfile:1
FROM ghcr.io/itopia-inc/spaces-base-images/spaces-ubuntu-base:focal

# Install your developers' tools

# Configure your developers' default environment
```
<!-- TODO: Write some example RUN instructions -->

## Feedback

Questions? Requests? [Please let us know on GitHub!](https://github.com/itopia-inc/spaces-base-images/issues)
