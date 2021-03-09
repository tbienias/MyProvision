<p align="center">
  <img src="https://raw.githubusercontent.com/tbienias/MyProvision/master/screenshot_01.png">
</p>

MyProvision is a collection of setup routines for automation of my personal
Manjaro Linux Plasma environment. Installation is performed via Ansible.

## Usage

First step after a fresh installation is to update the system and install ansible.

```bash
sudo pacman -Syu
sudo pacman -S ansible
```

Next, requirements need to be installed from Ansible Galaxy.

```bash
ansible-galaxy install -r requirements.yml
```

Then the main playbook is run.

```bash
ansible-playbook myprovision.yml
```

## Documentation

TODO.

## License

MIT
