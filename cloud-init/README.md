Build a cloud-init iso to setup system hostname and change the root password

Example:

Hostname: citest-1

Username: root

Password: redhat

```
# dnf install -y xorriso
# xorriso -as mkisofs -output ci.iso -volid cidata -joliet -rock user-data meta-data
```
