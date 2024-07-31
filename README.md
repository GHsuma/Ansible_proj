# Configuration Management Automation with Ansible

## Overview
This repository contains a comprehensive guide and implementation of configuration management using Ansible. The project automates the setup and management of infrastructure, ensuring consistency and reducing manual effort.

![Picture1](https://user-images.githubusercontent.com/50281621/176496822-96ebd976-09f3-46cb-90f4-bea2a2b513e7.png)

## Features
- **Automated Configuration Management**: Deploy configurations across multiple servers efficiently.
- **Scalable**: Easily manage large-scale infrastructure with minimal changes.
- **Reusable Playbooks**: Modular and reusable playbooks for various tasks.

## Requirements
- Ansible 2.9+ installed on the control machine.
- Target nodes configured with SSH access.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/patelrinkesh24/Configuration-Management-Automation-with-Ansible.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Configuration-Management-Automation-with-Ansible
   ```
3. Install the required dependencies:
   ```bash
   ansible-galaxy install -r requirements.yml
   ```

## Usage
1. Update the `inventory` file with the target nodes.
2. Customize the playbooks according to your environment.
3. Run the playbook:
   ```bash
   ansible-playbook -i inventory site.yml
   ```

## Project Structure
- **/playbooks**: Contains all the Ansible playbooks.
- **/roles**: Reusable roles for different tasks.
- **/inventory**: Inventory file for defining target nodes.
- **/vars**: Variable files for playbook customization.

## Screenshots

## Contributing
Feel free to contribute by submitting pull requests, opening issues, or suggesting features.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
