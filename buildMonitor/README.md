Script to automatically set up a raspberry pi as a build monitor with a burstah interface.
Provision with 

```sh

ansible-playbook "-e 'GOCD_SERVER_NAME=... GOCD_SERVER_PORT=... GOCD_SSERVER_AUTH=...'" -i hosts basic-setup.yml --ask-pass

```

If your raspberrypi has a different hostname than `raspberrrypi` adjust the host file as necessary


=
TODO

- The burstah takes a while to start up, therefore the luakit should either wait or retry for a bit to load the interface
- The luakit window should start fullscreen
