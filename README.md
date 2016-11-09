# vagrant-ubuntu

Ubuntu Xenial Vagrant environment for development.

## Prerequisites:

- [Vagrant](https://www.vagrantup.com)
- [VirtualBox](https://www.virtualbox.org)
- [Babun](http://babun.github.io) (optional, for rsync on Windows)

## Getting Started

1. Start the vm.

    ```
    vagrant up
    ```

2. Log into the vm:

    ```
    vagrant ssh
    ```

3. Synchronize the folders on the host:
    
    ```
    vagrant rsync-auto
    ```

## Synchronized Folders

- `.` → `/vagrant` Local repository folder.
- `..` → `/projects` Parent of the repository folder.

## Installed Dependencies

- Docker 1.12
- PostgreSQL 9.5
- Python 3.4
