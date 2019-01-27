wrlc-mariadb
=========

Updates SimpleSAMLphp

Role Variables
--------------
| Variable | Default | Comments |
|----------|---------|----------|
| target_hosts | none | specify in playbook or --extra-vars |
| target_upgrade_version | | hard-coded in vars/main.yml |
| install_location | /usr/local/webapps | |
| download_dir | /tmp | |

Example Playbook
----------------

    ---
    - name: wrlc-ssp
      hosts: "{{ target_hosts }}"
      roles:
        - wrlc-ssp
      become: true
