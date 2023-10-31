ECGALAXY gitlab_instance role
========

Installs Gitlab EE or CE instance.

Requirements
------------

- Amazon Linux 2023, which is the only platform currently supported.

Role Variables
--------------

- `gitlab_edition`: Set to `enterprise` (default) or `community` depending on the variant to install
- `gitlab_rb_file_path`: Local path of a configuration file on the control machine (optional)

Dependencies
--------------

None.

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.gitlab_instance

One-liner
---------

    bash <(curl -s https://code.europa.eu/-/snippets/1/raw/main/ansible-role.sh) ecgalaxy.gitlab_instance

See [ansible-role](https://code.europa.eu/-/snippets/1) for instructions.

Please verify the script integrity first.

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Original work
-------------

Copyright Red Hat, Josh Swanson, see https://www.redhat.com/en/blog/installing-gitlab-ce-rhel-9

Author Information
------------------

[ECGALAXY](https://code.europa.eu/groups/ecgalaxy/-/wikis/home) team.
