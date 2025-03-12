# Laptop Automation

This repository contains an Ansible playbook for configuring my personal laptop machine.

## Prerequisites

Before running the playbook, ensure you have the following installed on your local machine:

- **Ansible**: Install Ansible from [Ansible's installation guide](https://docs.ansible.com/ansible/latest/installation_guide/index.html).
- **Ansible Navigator**: Install Ansible Navigator from [Ansible Navigator's installation guid](https://ansible.readthedocs.io/projects/navigator/installation).

## Usage

1. **Clone the Repository**
   ```sh
   git clone https://github.com/gabrielpadilh4/laptop-setup
   cd laptop-setup
   ```

2. Install required collections
   ```sh
   ansible-galaxy collection install -r collections/requirements.yml
   ```

3. Run the playbook to start the environment
   ```sh
   ansible-navigator run playbook.yml 
   ```


## Information

Currently, this Ansible playbook installs and configures the following software:
- [Apache Maven](https://maven.apache.org/)
- [Apache Directory Studio](https://directory.apache.org/studio/)
- [DBeaver Community](https://dbeaver.io/)
- [Google Chrome](https://www.google.pt/intl/en_us/chrome/)
- [Gradle](https://gradle.org/)
- [Gnome Tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks)
- [JDK (8, 11, 17, and 21)](https://openjdk.org/)
- [Podman Desktop - Flatpak](https://podman-desktop.io/)
- [Ring Central](https://www.ringcentral.com/apps/linux-phone)
- [Java Decompiler](https://java-decompiler.github.io/)
- [meld](https://meldmerge.org/)
- [Slack - Flatpak](https://slack.com/)
- [VSCode](https://code.visualstudio.com/)
- [Virt Manager](https://virt-manager.org/)
- [vim](https://www.vim.org/)
- [Wireshark](https://www.wireshark.org/)
- [xsos](https://github.com/ryran/xsos)