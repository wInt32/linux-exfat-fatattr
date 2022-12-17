# linux-exfat-fatattr
Samsung's linux in-tree exfat driver, with FAT attributes support      

You can get and set the FAT attributes of a file using [fatattr](https://gitlab.com/Terseus/fatattr) or directly with FAT_IOCTL_GET_ATTRIBUTES or FAT_IOCTL_SET_ATTRIBUTES.      

To compile the module, run `make`.   
Now you can run `insmod exfat.ko` as root to insert the module into a running kernel.
