## RehabMan's laptop patch repository

This set of patches can be used in DSDT Editor or (preferably) MaciASL to apply
some common patches to your laptop for running OS X.  These patches are common
for Sandy Bridge or Ivy Bridge laptops.

Many of these patches came from work on the HP ProBook patches and/or work on my
own Intel DH67GD desktop.

Many of the battery patches were created over time, published as individual posts 
by me on tonymacx86.com, and collected here in this repository.

To add these patches to MaciASL as a repository:
- 运行 MaciASL
- 选择 Preferences from the MaciASL 菜单栏
- 选择 Sources
- 点击 这个 [+] 按钮
- give it a name (eg. "Laptop Patches")
- type the following URL: http://raw.github.com/RehabMan/Laptop-DSDT-Patch/master


### MaciASL and iasl

大神RehabMan 推荐使用 MaciASL的版本: 

https://github.com/RehabMan/OS-X-MaciASL-patchmatic

iasl工具，大神RehabMan的版本  :

https://github.com/RehabMan/Intel-iasl


### ACPI patching guide

For detailed information on ACPI patching, read here:

http://www.tonymacx86.com/el-capitan-laptop-support/152573-guide-patching-laptop-dsdt-ssdts.html

