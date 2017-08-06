# Proxmox Lab

## Force shutdown stuck VM
manually deleting the file under
  ```
  /var/lock/qemu-server/lock-XXXXXX.conf
  ```
## Command line shutdown VM
  ```
  qm list

  qm shutdown xxx
```
