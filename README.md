
# Install:

    pipenv install ansible
    pipenv shell
    ansible-galaxy install benthomasson.network_architect -p roles
    pip install -r roles/benthomasson.network_architect/requirements.txt


# Get a Topology

    ansible-playbook get.yml -e topology_id=80547dfb-75b0-4603-9bef-d1306b0b7f4c


