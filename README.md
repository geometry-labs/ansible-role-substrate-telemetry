Substrate Telemetry
=========

This role configures a host to run the Substrate Telemetry server in a Docker container.

Requirements
------------

This role requires the host to have Docker installed, as well as the Python _docker_ and _docker-compose_ packages.
If you want to use Ansible to prepare your host, may we suggest using the _geerlingguy.pip_ and _geerlingguy.docker_ roles from Ansible Galaxy.

Role Variables
--------------

This role has one variable, _host_fqdn_, which is the fully qualified domain name for the host.
For example, this might be _telemetry.mydomain.com_.

License
-------

Apache 2.0

Author Information
------------------

Maintained by [Richard Mah](https://github.com/shinyfoil) for [Insight Infrastructure](https://github.com/insight-infrastructure)
