Main [autoproj](http://rock-robotics.org/stable/documentation/autoproj)
configuration to replicate
the software installation for the LEAD's ROSA project

To install in a 'rosa' subdirectory, do:

```
mkdir rosa
cd rosa
wget https://github.com/OpenLEAD/buildconf-rosa/raw/master/bootstrap.sh
sh bootstrap.sh
source env.sh
autoproj full-build
```

