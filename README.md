### Vagrant cmds
```
$ vagrant package --base ucspe_3.2
$ vagrant box add ucspe_3.2.box --name UCSPE

```

```
$ /usr/local/Cellar/ansible/2.7.4/libexec/bin/pip3.7 install ucsmsdk
$ git clone https://github.com/ciscoucs/ucsm-ansible
```

```
$ ansible-playbook -i inv test01.yml

PLAY [ucs1] *****************************************************************************************************************************************************************

TASK [enable ntp 2] *********************************************************************************************************************************************************
ok: [ucs1]

PLAY RECAP ******************************************************************************************************************************************************************
ucs1                       : ok=1    changed=0    unreachable=0    failed=0
```

### UCS Platform Emulator OVA
cisco - https://cisco.app.box.com/v/ucspe-3-2-3e-ova
