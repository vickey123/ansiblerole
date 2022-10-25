# ansiblerole
Ansible is an open sourceIT automation tool that automates provisioning, configuration management, application deployment, orchestration, and many other manual IT processes.
Ansible roles allow you to develop reusable automation components by grouping and encapsulating related automation artifacts, like configuration files, templates, tasks, and handlers. Because roles isolate these components, it's easier to reuse them and share them with other people.

start a new role- ansible-galaxy init (role name)
define tasks- list the tasks you want to excute, got to the role created and to tasks- main.yml
when you execute a role, it looks for a file named main.yml in the tasks subdirectory and execute all the tasks listed within it. 
define variables instead of hard coding the values, to make your roles more reusable and easier to maintain.
define default variables
calling the role from a playbook- Now that your role is complete, you can call it from your playbooks.
execute the playbook
verify if its working 
clone the work to github for future reference. 
