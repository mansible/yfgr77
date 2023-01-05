### Description 
Service that output list of ARP adresses from cache of eth0 interface

### Upload service
To upload service on your Linux machine, put the test.service file to /etc/systemd/system.
File with shell script put to your own directory and change field ExecStart in test.service to right path.

### Manage the service
#### To run service do:
###### sudo systemctl daemon-reload
###### sudo systemctl start test.service

#### To add service to autoload do:
###### sudo systemctl enable test.service

#### To see status do:
###### sudo systemctl status test.service

#### To stop service do:
###### sudo systemctl stop test.service
