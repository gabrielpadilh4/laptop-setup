# Laptop Automation

This repository contains an Ansible playbook for configuring my personal laptop machine.

## Prerequisites

Before running the playbook, ensure you have the following installed on your local machine:

- **Ansible**: Install Ansible from [Ansible's installation guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).
- **Ansible Navigator**: Install Ansible Navigator from [Ansible Navigator's installation guid](https://ansible.readthedocs.io/projects/navigator/installation).

## Usage
Run the playbook to start the environment
   ```sh
   ansible-navigator run playbook.yml
   ```

## Information

Currently, this Ansible playbook installs and configures the following software:
- [Apache Maven](https://maven.apache.org/)
- [DBeaver Community](https://dbeaver.io/)
- [Google Chrome](https://www.google.pt/intl/en_us/chrome/)
- [Gradle](https://gradle.org/)
- [JDK (8, 11, 17, and 21)](https://openjdk.org/)
- [VSCode](https://code.visualstudio.com/)
- [vim](https://www.vim.org/)
- [Wireshark](https://www.wireshark.org/)
