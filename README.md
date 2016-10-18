Ansible Role: OpenStack Neutron Compute Node
=========

This role installs and configures OpenStack Neutron Compute Node on EL7 system.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`)

    controller_ip_address:

Controller Node IP address in management network.

    keystone_host: controller
    keystone_password:

Keystone credentials for Nova user.

    rabbitmq_host: controller
    rabbitmq_user:
    rabbitmq_password:

RabbitMQ credentials.

    region: RegionOne

OpenStack region.

    metadata_secret:

Secret token for metadata proxy.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
