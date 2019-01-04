# ansible-pypodman
test pypodman with ansible

### Prerequisites:
0. `ansible` version >= 2.6
1. `podman` is installed on remote
2. `pypodman` is installed on host
3. host can ssh to remote without password prompted

### How to use:
0. modify inventory
1. `ansible-playbook -i inventory $cmd.yml`

