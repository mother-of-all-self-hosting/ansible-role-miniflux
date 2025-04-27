<!--
SPDX-FileCopyrightText: 2023 Slavi Pantaleev

SPDX-License-Identifier: AGPL-3.0-or-later
-->

# Miniflux Ansible role

This is an [Ansible](https://www.ansible.com/) role which installs [Miniflux](https://miniflux.app) to run as a [Docker](https://www.docker.com/) container wrapped in a systemd service.

This role *implicitly* depends on:

- [`com.devture.ansible.role.playbook_help`](https://github.com/devture/com.devture.ansible.role.playbook_help)
- [`com.devture.ansible.role.systemd_docker_base`](https://github.com/devture/com.devture.ansible.role.systemd_docker_base)

Check [defaults/main.yml](defaults/main.yml) for the full list of supported options.
