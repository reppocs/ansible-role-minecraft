ansible-role-minecraft
=========

This is a role to install and configure a java minecraft server on a linux host.

Requirements
------------

This role requires the ansible.posix and community.general collections.

This role supports Ubuntu and Redhat based Linux distributions.

Role Variables
--------------

The default variables that probably won't need to be changed are in the defaults directory.

The variables that are likely to be changed are in the var directory

Usage
----------------

Put the following in your requirements.txt file.

```
roles:

- src: https://github.com/reppocs/ansible-role-minecraft.git
  name: reppocs.minecraft

```

Then, run the following to install the role.

```
  ansible-galaxy install -r requirements.yml
```

At that point, use it as you would any other local role.

License
-------

BSD

Author Information
------------------

https://coreyreppond.com
