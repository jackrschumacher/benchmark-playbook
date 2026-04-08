# benchmark-playbook

An Ansbile playbook that installs a variety of tools for benchmarking
## Installing Ansible

```bash
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
```

## Installing this playbook
Clone the repository

Use the latest stable version on the [releases page](https://github.com/jackrschumacher/benchmark-playbook/releases)


## General commands

`-v, -vv, -vvv` - Increasing levels of verbosity in the terminal

## `benchmark.yaml`

### Check that packages are installed

Navigate to the `benchmark-playbook` folder and run the following command:

```bash
ansible-playbook playbooks/benchmark.yaml -K -l "[host]"
```

