# Mikrotik-Ansible Repository

## Overview

Welcome to the Mikrotik-Ansible repository! This repository serves as a collection of Ansible playbooks, roles, and scripts for configuring Mikrotik devices. Whether you're managing a small network or a large-scale infrastructure, Ansible offers powerful automation capabilities to streamline the management and configuration of Mikrotik routers and switches.

## Purpose

The primary purpose of this repository is to provide a centralized location for storing and sharing Ansible resources tailored specifically for Mikrotik devices. By leveraging Ansible's infrastructure as code approach, network administrators and engineers can automate routine tasks, enforce consistent configurations, and deploy changes across their Mikrotik network efficiently and reliably.

## Contents

This repository contains a variety of Ansible resources, including:

- **Playbooks:** Pre-written sequences of tasks to automate specific configuration tasks or workflows on Mikrotik devices.
- **Roles:** Reusable collections of Ansible tasks, handlers, templates, and variables that encapsulate specific configuration roles (e.g., DHCP server, firewall rules) for Mikrotik devices.
- **Scripts:** Custom scripts or modules to extend Ansible's capabilities for interacting with Mikrotik devices, such as retrieving device information, performing backups, or executing complex tasks.

## Getting Started

To start using the Ansible resources in this repository, follow these steps:

1. **Clone the Repository:** Clone or download this repository to your local machine using Git:

    ```bash
    git clone https://github.com/zickkeen/mikrotik-ansible.git
    ```

2. **Install Ansible:** If you haven't already installed Ansible, follow the [official Ansible installation instructions](https://docs.ansible.com/ansible/latest/installation_guide/index.html) for your operating system.

3. **Explore the Contents:** Browse the repository to explore the available playbooks, roles, and scripts. Each directory may contain its own README.md file with further instructions and usage guidelines.

4. **Customize and Execute Playbooks:** Customize the provided playbooks and roles to match your specific network requirements. You can edit variables, templates, or tasks according to your needs. Then, execute the playbooks using the `ansible-playbook` command:

    ```bash
    ansible-playbook -i inventory playbook.yml
    ```

5. **Contribute:** If you have improvements, additional playbooks, or bug fixes, consider contributing them back to the repository. Fork the repository, make your changes, and submit a pull request.

## Contributing

Contributions to this repository are welcome and encouraged! Whether you're fixing a bug, adding new features, or improving documentation, your contributions help make this repository more valuable to the community. For guidelines on how to contribute, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## License

This repository is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the code for both commercial and non-commercial purposes. However, we kindly ask you to provide attribution to the original repository and maintain the license information when redistributing the code.

## Feedback

We value your feedback! If you have any questions, suggestions, or issues related to this repository, please don't hesitate to open an issue or reach out to the repository maintainers.

Happy automating with Ansible and Mikrotik! 🚀
