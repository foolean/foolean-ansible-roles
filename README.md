# foolean-ansible-roles

    Foolean Collection of Ansible roles


## Usage

    * clone this repo into '/path/to/your/roles/foolean'
    * run `git submodule update --init`


## Ansible structure

    The current structure being used is listed below.  It was chosen to allow
    upstream Foolean git repositories to be used but also not collide with other
    content

        ansible/
        |-- inventory/
        |   |-- group_vars/
        |   `-- host_vars/
        |-- playbooks/
        |   `-- foolean/  <-- foolean-ansible-playbooks repo
        `-- roles/
            `-- foolean/  <-- foolean-ansible-roles super-project


## License

    BSD-3-Clause
