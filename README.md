Example use
===========

# setup a namespace, add a Repository for the namespace name, add a Distribution for the repo,
# get a user auth token, generate an ansible.cfg pointing to the repo url with the user auth token,
# publish a collection, install it
ansible-playbook -vvv setup_ansible_galaxy_for_standalone.yml --extra-vars autohub_admin_username=admin --extra-vars autohub_admin_password=admin --extra-vars autohub_namespace=eifeltower
