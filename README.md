Ansible Role: oh_my_zsh_colorls
===============================

Role to download, install and configure [Colorls](https://github.com/athityakumar/colorls).

Requirements
------------
To have [Oh-My-Zsh](http://ohmyz.sh/) installed.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

```yaml
users:
  username: ansible-test
 ```
Example Playbook
----------------

  ```yaml
  - hosts: myservers
    roles:
      - role: kerjox.oh_my_zsh_colorls
        users:
          - username: ansible-test
  ```
License
-------
GNU
