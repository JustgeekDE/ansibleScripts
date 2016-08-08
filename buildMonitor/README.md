Script to automatically set up a raspberry pi as a build monitor with a burstah interface.
Provision with 

'''sh

ansible-playbook "-e 'GOCD_SERVER_NAME=... GOCD_SERVER_PORT=... GOCD_SSERVER_AUTH=...'" -i hosts basic-setup.yml --ask-pass

'''

If your raspberrypi has a different hostname than 'raspberrrypi' adjust the host file as necessary
