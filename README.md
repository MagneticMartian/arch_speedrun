# arch_speedrun
The command.list is still a minimal set of one liners to install Arch.

## arch_setup
------ALL BRANCHES OTHER THAN MAIN ARE EXPERIMENTAL-------

This has become more of a full install script. The script has been tested on QEMU. It sets up a Single partition with the MBR sceme and formats the partitions with the ext4 filesystem. In the future there may be other branches that will be for different types of filesystems and different partitioning scemes.

## Install
1) Ensure that you have the newest Arch iso.
2) Once you have your live disk up and running install git:
```
pacman -Sy git
```
3) Then run:
```
git clone https://github.com/MagneticMartian/arch_speedrun.git
```
4) If you wish to just run the setup script then from the root directory do:
```
mv arch_speedrun/arch_setup .
chmod 0744 arch_setup
./arch_setup
```
5) have fun and see what kind of different improvements you can find.
