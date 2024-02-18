ricardoklein.pihole
=========

Deploy the pi-hole container using podman and setup all needed cronjobs to keep it up-to-date.

Requirements
------------

Ansible
Podman (will be installe dy the role)

Recommended to setup a firewall and not expose your firewall (ports 80/tcp) and 53/udp.
You can use my role ricardoklein.nftables to setup the firewall ;-)

Role Variables
--------------



Dependencies
------------

This role uses the following collections:

* community.general

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ricardoklein.pihole }

License
-------

BSD

Author Information
------------------

If you want to suggest changes or request new features,
please feel free to create a issue or send a pull request.

If you find this useful, you can help donating Monero:

`86srKqPRnzpLCkihCHJ9ZB8sjg7B1QxBmT7xS6ebsL52JgCSHVsDsTqDCAqQveasfGh95AZei11Dc1fwjwrE42t3QhzHkdm`
