Setup LAMP with multiple PHP versions in Ansible
=========

![Image](images/ansible.png)

Setting up LAMP(Linux, Apache, MariaDB, PHP) with 5.6, 7.2, 7.4 versions of PHP in Ansible

Requirements
------------

Minimum 2 Managed nodes(in my case CentOS7, you may see problems with other distros) and 1 Control node 

Dependencies
------------

Dependencies will downloaded and ready in "collections" section.

Example Playbook
----------------

After changing ansible.cfg and inventory files, Run lamp.yml file to start the Setup of the LAMP Stack

    ansible-playbook lamp.yml

But, If you run the playbook twice or more, run this command

    ansible-playbook lamp.yml --skip-tags run_only_once
    
Images from Project
-------

![Image](images/php-56.png)
---
![Image](images/php-72.png)
---
![Image](images/php-74.png)

License
-------

Apache License

Author Information
------------------

[LinkedIn](https://www.linkedin.com/in/imannovv/)
