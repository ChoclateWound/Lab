# Proxmox Lab

## Networking
  ```
  https://www.flomain.de/2015/05/how-to-proxmox-networking/
  ```

### Force shutdown stuck VM
manually deleting the file under
  ```
  /var/lock/qemu-server/lock-XXXXXX.conf
  ```
### Command line shutdown VM
  ```
  qm list

  qm shutdown xxx
```
