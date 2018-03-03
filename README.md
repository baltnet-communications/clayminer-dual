# About This Project
This project packages Claymore's Dual Ethereum+Decred AMD+GPU Miner binary distribution into standard Debian package to simplify installation and maintenance.

During installation, miner files are copied into `/opt/clayminer-dual` folder and a `systemd` service will be created so that miner can be started automatically on boot.

# Installation
Please visit http://pkg.baltnet.net for instructions how to configure Baltnet repository and install this package.

# Configuration
There is no default working configuration which a daemon can use. Therefore, a custom configuration must be created manually after installation.
