# autokernel
a better version of [kerninstall](https://github.com/devlocalhost/kerninstall) (right?)

# not for everyone
it was mostly made for me. this can be used only on a ubuntu host (unless debian or any other debian/ubuntu based distro offers the dependecies in the exact same name), and it compiles for i686. but it shouldnt be that hard to modify and make it work for you

# 2 scripts
one for installing, for compiling

# usage
run the scripts without any arguments. itll display the help menu

## autokernel
```
   Usage: ./autokernel OUTPUT CONFIG O3_PATCH DEPTH RT_PATCH EX_MENUCONFIG
Defaults: OUTPUT: no. accepts: yes, no
        O3_PATCH: no. ~~~~~~~~~~~~~~~~
           DEPTH: NONE. accepts: nothing or int (num, value)
        RT_PATCH: no. accepts: yes, no
    EX_MENUCOFIG: no. ~~~~~~~~~~~~~~~~
```
## autokernelinstall
```
    Usage: ./autoinstallkernel OUTPUT KERNEL_XZ_URL KERNEL_FILE_NAME REMOVE_OLD_KERNEL UPDATE_GRUB_AND_OR_NO_REBOOT
 Defaults:    OUTPUT: no. accepts: yes, no
   REMOVE_OLD_KERNEL: no. ~~~~~~~~~~~~~~~~
  UPDATE_GRUB_AND...: no. ~~~~~~~~~~~~, yesr (update and reboot), no
```
