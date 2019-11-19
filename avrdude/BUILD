# Prepare

The build process is using autotools (`configure.am`)
First `configure` script must be recreated/updated with 
`autoreconf --install -v` - verbosely update `configure`, install instead of copy missing files.
This should generate `make` `Makefile` from automake's extended version: `Makefile.am`. Then you can run regular `make` command (`make all`, `make install` etc.). Following (Build)[#Build] procedure is recommended.

Make sure following packaged are available (Ubuntu):
`libelf-dev libusb-dev libusb-1.0-0-dev libftdi1-dev libftdi-dev`

# Build

After project is (prepared)[#Prepare], run:
```
mkdir build
cd build
../configure
make all
```
