Main [autoproj](http://rock-robotics.org/stable/documentation/autoproj)
configuration to replicate
the software installation for the LEAD's ROSA project

To install in a 'rosa' subdirectory, open a new shell and do:

```
mkdir rosa
cd rosa
wget https://github.com/OpenLEAD/buildconf-rosa/raw/master/bootstrap.sh
sh bootstrap.sh
source env.sh
```
Start using your new installation. Remember to source env.sh in every shell
where you want to use this installation
Alternatively, you can follow the instructions at
  http://rock.opendfki.de/wiki/WikiStart/Toolchain/MultipleInstalls
to ease the sourcing of env.sh
