# xen_cheatsheet
Xen Cheat Sheet


`xm list` - list virtual machines

`xm list $VM -l` - list vm details

`xm start` - start virtual machine

`xm shutdown` - shutdown of virtual machine

`xm destroy` - ungracefully shutdown of virtual machine

`xm create $CONFIG_FILE` - create virtual machine from configuration file

`xm pause` - pause virtual machine

`xm resume` - resume virtual machine

`xm suspend`

`xm save` - saving vm state

`xm restore` - restore vm state

`xm reboot` - restart vm

`xm network-list` - list virtual networks

`xm mem-set $VM $AMOUNT` - set memory to vm

`xm info` - virtual machine info

`xm log` - virtual machine logs

`xm shell` - shell of xen

`xm console` - get in virtual machine console, `Ctrl+]` leaves

`vncviewer` - connect to vm through vnc like localhost:5900

`xm migrate $VM $HOST` - migrate virtual machine to other host

`xentop` - list virtual machines and their resource usage

`ln -s /etc/xen/<instance> /etc/xen/auto/<instance>` - set virtual machine to autostart
