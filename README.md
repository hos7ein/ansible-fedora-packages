# ansible-fedora-packages

[![Markdown](https://github.com/hos7ein/ansible-fedora-packages/actions/workflows/markdown-check.yml/badge.svg 'markdown-check')](https://github.com/hos7ein/ansible-fedora-packages/actions/workflows/markdown-check.yml) [![Ansible](https://github.com/hos7ein/ansible-fedora-packages/actions/workflows/ansible-check.yml/badge.svg 'ansible-check')](https://github.com/hos7ein/ansible-fedora-packages/actions/workflows/ansible-check.yml)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg 'GPLv3 license')](http://perso.crans.org/besson/LICENSE.html)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg 'Maintenance')](https://github.com/hos7ein/ansible-fedora-packages/graphs/commit-activity)
[![Ask Me Anything](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg 'Ask Me Anything')](https://GitHub.com/hos7ein/ansible-fedora-packages)

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black 'Linux')](https://www.kernel.org/)
[![Fedora](https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white 'Fedora')](https://fedoraproject.org)
[![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white 'Ansible')](https://www.ansible.com)

## Table of contents

* [Introduction](#introduction)
* [Requirements](#requirements)
* [Deploy](#deploy)
* [Contributing](#contributing)
* [Contact](#contact)
* [License](#license)

## Introduction

This is a Ansible playbook for installing necessary packages on Fedora Linux.

## Requirements

* Ansible
* Git

To install requirements packages you can run this command:

```bash
sudo dnf install ansible git
```

## Usage

Follow these steps to execute the playbook.

### 1. Clone the Repository

```bash
git clone https://github.com/hos7ein/ansible-fedora-packages.git
```

### 2. Change the current working directory

```bash
cd ansible-fedora-packages
```

### 3. Set your username

Before running the playbook, you must configure your username. Open the `group_vars/all` file and change the value of `username` to your system's username.

For example:

```yaml
username: your-username
```

### 4. Deploy the playbook

Run the playbook with sudo, as it requires root privileges to install packages.

```bash
sudo ansible-playbook main-playbook.yml
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to
discuss what you would like to change.

## Contact

[![Personal website](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white 'https://fedorafans.com')](https://fedorafans.com)

[![X (formerly Twitter)](https://img.shields.io/badge/X-formerly%20Twitter-black?style=for-the-badge&logo=x)](https://x.com/hos7ein)

## License

`ansible-fedora-packages` source code is available under the GPL-3.0 [License](/LICENSE).
