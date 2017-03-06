ansible docker
==============
[![Build Status](https://travis-ci.org/ypsman/ansible-docker.svg?branch=master)](https://travis-ci.org/ypsman/ansible-docker)

This Role installs docker-compose on youre Server.

You can specifie a version to install.

The docker_compose_version variable is optinal.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.docker-compose
          docker_compose_version: "1.9.0"  # optional
