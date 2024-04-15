

# Linux check status
```
rsync -vrltD --stats --human-readable /tmp/software /nas10 | pv -lep -s 42
```


```
rsync -av --info=progress2 root@nas01:/tmp/*Office* .
```

Reference [https://www.cyberciti.biz/faq/show-progress-during-file-transfer/]

# Get serial number and manufacturer
```
cat /sys/devices/virtual/dmi/id/bios_vendor
cat /sys/devices/virtual/dmi/id/chassis_serial
```

https://stackoverflow.com/questions/20206474/extract-the-linux-serial-number-without-sudo
