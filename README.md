ansible docker-compose
======================
[![Build Status](https://travis-ci.org/ypsman/ansible-docker-compose.svg?branch=master)](https://travis-ci.org/ypsman/ansible-docker-compose)

This Role installs docker-compose on youre Server.

You can specifie a version to install.

The docker_compose_version variable is optional.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: ypsman.docker-compose
          docker_compose_version: "1.9.0"  # optional
