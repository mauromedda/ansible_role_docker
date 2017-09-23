mauromedda.ansible_role_docker
==============================

Install Docker on the CentOS distribution.

## Requirements

No.

## Role Variables

Available variables are listed below, along with default values (see [`defaults/main.yml`](defaults/main.yml)):

    docker_packages_required
Specify a list of packages required by docker-ce.

    docker_packages_purge

The set of packages to purge. Basically, the oldest docker packages included on the OS.

    docker_repo_config
       baseurl: "https://download.docker.com/linux/centos/docker-ce.repo"
       section: docker-ce-stable
       enabled: 1

The configuration for the Docker Community Edition package repository.

    docker_enabled_users

The list of user that have to use the docker engine.

## Dependencies

None.

## License

BSD

## Author Information

Mauro Medda
