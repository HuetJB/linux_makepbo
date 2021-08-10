# linux_makepbo

Juste a git for simple import of makepbo to linux

## How to deploy 

### Install libraries

- For Debian/Ubuntu, run this : ```apt-get install liblzo2-2 libvorbis0a libvorbisfile3 libvorbisenc2 libogg0```
- For RHEL/CentOS, run this : ```yum install lzo libvorbis libogg```

### Install executables

- Copy all elements of [bin](https://github.com/HuetJB/linux_makepbo/tree/main/depbo-tools-0.6.24/bin) to ```/bin``` of your linux server.
- Copy all element of [lib](https://github.com/HuetJB/linux_makepbo/tree/main/depbo-tools-0.6.24/lib) to ```/usr/local/lib/``` of your linux server.

### Finish installation 

- Run this commande : ```sudo ldconfig```

## Utilisation

- For create pbo : ```makepbo```
- For extract pbo : ```extractpbo```
