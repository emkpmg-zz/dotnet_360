# Ansible Collection - piandt.dotnet_360


dotnet_360 ansible role
-----------------------

    dotnet_360 ansible role is a one in all paackage for installing most versions of Microsoft .NET. (core SDK, .NET core runtime and .NET framework. Includes devpack, windows devpack, windowshosting and other variations). Role can be added in playbook with specific versions to install.

Installation
------------
ansible-galaxy collection install piandt.dotnet360

Role Variables
--------------
    path: piandt/dotnet_360/roles/dotnt_360/vars
    Variables can be dound in thhe main.yml. Each key can be referenced as a version in playbook.


Example Playbook
----------------
An example of how to use your role (for instance, with variables passed in as parameters)

    - hosts: servers
      roles:
         - role: piandt.dotnet_360
         	version:


Package site
------------
Link: https://galaxy.ansible.com/piandt/dotnet360

Dependencies
------------

License
-------
    MIT


Author Information
------------------
    - https://github.com/ewuramaminka
    - Twitter: @eminka_da