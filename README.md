# un-bootable

**Firstly check the name by going through Disk**

THEN,
Run the following commands:

```bash
df -TH
```
> The above command will show you all the partitions

```bash
sudo umount /dev/sdb1
```
Now format using vfat
```bash
sudo mkfs.vfat -I /dev/sdb
```

Then check once again at the disk and click on the start button on the partition.
