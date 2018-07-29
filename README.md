# Ubuntu Bootstrap

Ansible playbook that configures a clean Ubuntu 18.04 Desktop install based on my opinionated preferences.
Intended for personal use and as reference material.

## Prerequisites

Manually install the following into the machine:

- Python 2.x
- Ansible
- Chrome
- Sublime

## Run the Playbook

```bash
$ ansible-galaxy install -r requirements.yml
$ sudo ansible-playbook -v playbook.yml
```

## License

The MIT license