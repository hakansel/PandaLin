PandaLin
========
Aims to:

	Pandaboard and Pandaboard ES image creation with some capabilities based on Buildroot.
		
		- rootfs
		- x-loader (MLO)
		- bootloader (u-boot)
		- kernel (linux 3.6.8)
		- Packages (in progress)
		- OMAP4 capabilities (SGX, DSP, GPIO vs.)

--------------------------------------------------------------------------------

After cloning project into your local;

	- If you don't have already, you should install some packages to your linux based system.

	List of these packages: 
		
		http://buildroot.uclibc.org/downloads/manual/manual.html#_starting_up

	- Before building your system that needed to toolchain, you should toolchain. PandaLin use
	toolchain of Linaro 2012.06 version. You shoul download it and untar it to /opt/toolchains.

Dowload link:
https://launchpad.net/linaro-toolchain-binaries/trunk/2012.06/+download/gcc-linaro-arm-linux-gnueabihf-2012.06-20120625_linux.tar.bz2
