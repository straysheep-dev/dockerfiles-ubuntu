# dockerfiles-ubuntu

Dockerfiles to build Ubuntu images. See [straysheep-dev/docker-configs](https://github.com/straysheep-dev/docker-configs) for a general overview and references.

> [!NOTE]
> These files were built from a combination of:
> - [geerlingguy's](https://github.com/geerlingguy) `docker-<os>-ansible` templates
> - [Molecule's systemd-enabled container guide](https://ansible.readthedocs.io/projects/molecule/guides/systemd-container/)
> - [Rocky Linux Docker image systemd integration notes](https://hub.docker.com/r/rockylinux/rockylinux#systemd-integration)
> - Searching for, and reviewing, examples and documentation with ChatGPT or AI mode Google Search


## Images

| Version | Components and Software | Status |
| :--- | :---: | :---: |
| `ubuntu:latest` | `systemd` | ![Static Badge](https://img.shields.io/badge/supported-green) |
| `ubuntu:22.04` | `systemd` | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `ubuntu:20.04` | `systemd` | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `ubuntu:18.04` | `systemd` | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `ubuntu:16.04` | N/A | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `ubuntu:14.04` | N/A | ![Static Badge](https://img.shields.io/badge/planned-gray) |


## License

[MIT](LICENSE)