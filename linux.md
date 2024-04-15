

# Linux check status
```
rsync -vrltD --stats --human-readable /tmp/software /nas10 | pv -lep -s 42
```


```
rsync -av --info=progress2 root@nas01:/tmp/*Office* .
```

Reference [https://www.cyberciti.biz/faq/show-progress-during-file-transfer/]
