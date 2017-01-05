# playbook-arma-server
=========

Installation of Steam Based ArmA3 Dedicated Server

Requirements
------------

    Steam Account

Role Variables
--------------

    arma3server_installation: true
    arma3server_upgrade: false
    arma3server_firewall:
      - { port: 2302, protocol: udp }

Dependencies
------------

    none

Playbook
----------------

Update hosts file and execute ```ansible-playbook -i hosts playbooks/set-arma3-server.yml```


License
-------

BSD

Author Information
------------------

Lars Hunold
http://macnemo.tv
