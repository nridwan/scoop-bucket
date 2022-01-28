# scoop-bucket
A scoop bucket containing personal tools used in my windows machine.

Current available packages:
| package name | scoop name | version |
| --- | --- | --- |
| mason | mason-standalone | 0.1.0-dev.5 |
| vlang | vlang | weekly.2022.04 |


## Install Scoop
```ps
Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex
```

## Add this bucket
```
scoop bucket add nridwan https://github.com/nridwan/scoop-bucket.git
```
