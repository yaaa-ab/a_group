# kong ansible project

This is just an ansible project that install kong from source code and setup a startup script.

Please consider changing the inventory.yml & kong_setup.yml to customize.

Usage:
cd kong_project/
ansible-playbook -i my_inventory.yml kong_setup.yml --limit=ubuntu4kong
