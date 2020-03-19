# ansible
This playbooks were created for Cisco IOS Devices.  There are a lot of youtube videos to get started with Ansible.
It looks like you need the developers edition to include the "IOS" modules needed.  I set up on Ansible on a Raspberry Pi3,
and works well for mall home network.
These are generally the steps I tood to set it up... (rough notes)  I had issues with the crypto module in python.
You should probably have python3 setup and updated before installing ansible?

On raspberry pi
https://www.google.com/amp/s/geektechstuff.com/2019/06/25/installing-ansible-raspberry-pi/amp/
-- will need to change location and install the developers version

to configure the files VIM will make it easier or nano
-sudo apt-get install vim to fix VI issues

https://geektechstuff.com/2019/06/27/ansible-setting-up-ssh-raspberry-pi/

IOS config module ansible https://www.youtube.com/watch?v=7RBs7JFj4xI

https://docs.ansible.com/ansible/latest/modules/list_of_network_modules.html#ios

fix old version of ansible sudo -H pip install --upgrade ansible

https://github.com/colin-mccarthy/ansible-playbooks-for-cisco-ios/tree/master/backup_config

need developers edition for IOS commands
https://www.google.com/search?q=how+to+install+IOS+ansible&oq=how+to+install+IOS+ansible&aqs=chrome..69i57.4742j0j4&sourceid=chrome&ie=UTF-8#kpvalbx=_BNdzXpiMA5j5-wTL65GwAg19

https://docs.ansible.com/ansible/latest/network/user_guide/platform_ios.html
set group variables and vault for pasword
