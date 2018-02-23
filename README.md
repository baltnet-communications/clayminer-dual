# About This Project
This project packages a Claymore Dual Miner binary distribution into standard Debian package for simplifying installation and maintenance.

Upon installation, all miner files are copied into `/usr/share/clayminer-dual` directory. Also, `systemd` scripts are created so that the miner can be started automatically on boot.

# Installation
Please visit http://pkg.baltnet.net for instructions how to configure Baltnet repository and install this package.

# Configuration
There is no default working configuration which a daemon can use. Therefore, a custom configuration must be created manually after installation.
