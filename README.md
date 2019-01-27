wrlc-mariadb
=========

Updates SimpleSAMLphp

Role Variables
--------------
| Variable | Default | Comments |
|----------|---------|----------|
| target_hosts | | |
| target_upgrade_version | | |
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
