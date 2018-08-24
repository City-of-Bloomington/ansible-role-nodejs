City-of-Bloomington.nodejs
=========

Install node, along with common packages on Ubuntu using apt.

Requirements
------------

City-of-Bloomington.linux

Example Playbook
----------------
```yml
- hosts: linux-node
  become: yes
  roles:
    - City-of-Bloomington.linux
    - City-of-Bloomington.node
```

Copying and License
-------
This material is copyright 2016 City of Bloomington, Indiana
It is open and licensed under the GNU General Public License (GPL) v3.0 whose full text may be found at:
https://www.gnu.org/licenses/gpl.txt
