# libhashab
initial inspiration from [denydias/libhashab](https://github.com/denydias/libhashab/)

This is an extension to make [libgpod](http://www.gtkpod.org/libgpod/) compatible with the iPod nano 6th generation internal music database

# WARNING: once you install this you will be able to ONLY use iPod nano 6th gen. Any other iPod won't work

# Install
```
make
cp libhashab32_wrapper /usr/lib64/libgpod/
cp libhashab32.so /usr/lib64/libgpod/
cp libhashab32.so /usr/lib/x86_64-linux-gnu/libgpod/
cp libhashab32_wrapper /usr/lib/x86_64-linux-gnu/libgpod/

```


# Sources
1. [ubuntuforums.org](http://ubuntuforums.org/showthread.php?t=1611473&page=4&p=12606043#post12606043): danwood76 is the original author of this extension

2. [ht2tp://lizquilty.com/2013/09/28/how-to-get-an-ipod-nano-6th-gen-working-in-linux/](http://lizquilty.com/2013/09/28/how-to-get-an-ipod-nano-6th-gen-working-in-linux/)
