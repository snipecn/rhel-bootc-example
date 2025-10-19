Example:

Build a cloud-init iso to setup system hostname and change the root password

```
# dnf install -y xorriso
# xorriso -as mkisofs -output ci.iso -volid cidata -joliet -rock user-data meta-data
```
