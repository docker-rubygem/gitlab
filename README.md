[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/gitlab.svg)](https://hub.docker.com/r/rubygem/gitlab/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/gitlab.svg)](https://hub.docker.com/r/rubygem/gitlab/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/gitlab.svg)](https://hub.docker.com/r/rubygem/gitlab/)
[![Gem Downloads](https://img.shields.io/gem/dt/gitlab.svg)](https://rubygems.org/gems/gitlab/)
# gitlab

Auto-Generated Docker image for gitlab to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/gitlab`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/gitlab`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/gitlab`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/gitlab/)
