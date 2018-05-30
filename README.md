ansible-playbook-rabbitmq-stop-node
=========
This playbook calls a role to start the RabbitMQ node

How to run the playbook
-----------------------

If you dont have the role on your machine simply cd into the roles directory and run:

    ansible-galaxy install -r requirements.yml
    
Below is an example command on how to run the playbook:

    ansible-playbook site.yml -i inventory 

License
-------

BSD

Author Information
------------------

Helen Turner