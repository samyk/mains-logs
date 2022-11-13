
# log files

- git has 100MB file limit so reconstruct hz.log.2.gz via
```sh
cat hz.2.log.gz_* > hz.2.log.gz
```