# Absible Role: virt_tools
This role does install virt tools on RHEL and Ubuntu LTS Systems.   
Curently, we support:
* VMware
* KVM

## Requirements
Please look into `meta\main.yml`

## Install Role from Git
```
git clone git@github.com:joe-speedboat/ansible.mtp.git /etc/ansible/roles/joe-speedboat.virt_tools
cd /etc/ansible/roles/joe-speedboat.virt_tools
rm -rf .git
``` 


## Install Role from Galaxy
```
ansible-galaxy install joe-speedboat.virt_tools
``` 



## Role Variables
Variables are documented in `defaults/main.yml`:

- `virt_tools_install`: Controls whether the system should be modified to install virtualization tools. Default is `True`.


## Dependencies
None


## Example Playbook
Are located in `test` folder of the role


## License
GPLv3


# Author Information
* Chris Ruettimann<chris@bitbull.ch>
* https://www.bitbull.ch 
