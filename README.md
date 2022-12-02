<p align="left">
<img src="https://github.com/Kreato-Linux/logo/blob/master/withtext.png"> 
<img src="https://github.com/Kreato-Linux/logo/blob/master/core.png" height="10%" width="10%">
</p>

# nyaastrap v2
The Kreato Linux build tool.

# Usage
Available commands;
`build-packages`
Builds packages.
`build-rootfs`
Builds a Kreato Linux rootfs according to the `.config` file. A simple one is included.
Before running build-rootfs, make sure to change `changeme` on `scripts/build-rootfs.sh` with an defconfig if you want to use a defconfig.

You can execute commands by `docker-compose up [COMMAND]`.
