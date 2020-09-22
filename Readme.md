<img src=".github/resources/color-dark-2048.png" width="256">

![GitHub issues](https://img.shields.io/github/issues/t3knomanzer/maxmix-hardware)
![GitHub pull requests](https://img.shields.io/github/issues-pr/t3knomanzer/maxmix-hardware)
![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/t3knomanzer/maxmix-hardware/latest)


[![Paypal donate](https://img.shields.io/badge/paypal-donate-blue?logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=SQS6XJZBCBZA8&currency_code=USD&source=url)
[![Github sponsor](https://img.shields.io/badge/github-sponsor-blue?logo=github)](https://github.com/sponsors/t3knomanzer)

## Overview
**Maxmix** is an open-source volume mixer that allows you to control the volume applications from an external custom controller.  
It was originally designed to allow to quickly adjust the volume of a game and an external voice chat application like Discord quckly, but it can do so much more...  
You can find out more about the system in the [project website](https://www.maxmixproject.com).

This repository contains the designs to build the official hardware.

## Contributing
Most files on this repository are binary and do not allow for changes to be merged.  
To prevent changes being overwritten, we  use [LFS with locking](https://github.com/git-lfs/git-lfs/wiki/File-Locking).  

Before you start working on a file, you need to lock it. Locks are exclusive so only one user can lock a file at a time. Locking the file will also make it
writeable locally and allow you to make changes to it.

Here are a few useful commands:

Lock a file
```
$ git lfs lock images/foo.jpg
Locked images/foo.jpg
```

Unlock a file
```
$ git lfs unlock images/foo.jpg
$ git lfs unlock --id=456
```

View locked files
```
$ git lfs locks
images/bar.jpg  jane   ID:123
images/foo.jpg  alice  ID:456
```

Typical workflow
```
$ git lfs lock images/foo.jpg
$ git commit images/foo.jpg -m "My changes"
$ git lfs unlock images/foo.jpg
$ git push
```


## Community
You can join these groups and chats to discuss your-project related questions:

[Website](https://maxmixproject.com)  
[Twitter](https://www.twitter.com/maxmixproject)  
[Reddit](https://www.reddit.com/r/maxmixproject)    
[Discord](https://discord.gg/TmvvgCw)  
[Github](https://www.github.com/t3knomanzer/maxmix-software)  
[Thingiverse](https://www.thingiverse.com/thing:4343186)  
[Prusaprinters](https://www.prusaprinters.org/prints/31336-maxmix)  
[Donate](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=SQS6XJZBCBZA8&currency_code=USD&source=url)
