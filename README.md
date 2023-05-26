# C++ Operating System project

## Installation

`cd` into the repo and then to the `./src` folder before running any commands

run `make install` to generate the kernal binary file

Once this file is generated add the following lines to your `/boot/grub2/grub.cfg`:

```
menuentry 'Example Entry Name': {
    multiboot /boot/mykernel/bin
    boot
}
```
just before the UEFI menuEntry is a good option
___
<!-- Current installation is hacky because OS is only at Hello World stage -->
<!-- TODO: refine the installation method and overall README -->
