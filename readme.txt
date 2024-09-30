./build_kernel - Quick script to download and compile the latest stable kernel for @datcuandrei.

Usage: ./build_kernel {download|prepare|compile [KERNEL_DIR]}
Must run as privileged user!

Commands:
	- download: Downloads the latest stable release
	- prepare: Installs packages required in order to build and compile the kernel
	- compile: Compiles the kernel provided in KERNEL_DIR using the current kernel's configuration using all available threads. Also installs modules&headers and generates GRUB config.
