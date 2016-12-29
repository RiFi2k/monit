Monit Monitoring & Alerting
=========

Setup and configure Monit
- monitor the core services running on the server
- uptime monitoring for websites
- restart services if they stop or crash
- provide a GUI interface for monitoring the server
- provide alerting if there are any issues

Requirements
------------

- Trellis - https://github.com/roots/trellis/

Role Variables
--------------



Dependencies
------------



Example Playbook
----------------

Put this line into the Trellis server.yml file near the end

    roles:
        - { role: monit, tags: [monit] }

License
-------

MIT

Author Information
------------------

https://github.com/RiFi2k/
