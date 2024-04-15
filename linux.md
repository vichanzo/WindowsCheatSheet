

# Linux check status
```
rsync -vrltD --stats --human-readable /tmp/software /nas10 | pv -lep -s 42
```
