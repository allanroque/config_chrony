allanroque.configure_chrony
=========

A brief description of the role goes here.

Requirements
------------

This Ansible role configures the Chrony service on RHEL systems to synchronize time using NTP servers provided by the National Observatory of Brazil. It installs the Chrony package, configures both primary and fallback NTP servers, adjusts the firewall to allow Chrony traffic, and ensures the service is running and enabled on boot.


Dependencies
------------

- Operating System: RHEL 8 or later.
- Ansible Version: 2.9 or later.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

´´´
- hosts: servers
  become: yes
  roles:
    - role: username.configure_chrony
´´´

License
-------

MIT
