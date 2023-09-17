This script exploit the  CVE-2023-2640 and CVE-2023-32629 for vulnerability on OverlayFS that affected some versions of Ubuntu.

Tested on Ubuntu 20.04 with kernel 5.4.0.

## How to Use

Download the file Gameoverlay.sh and with a normal user (no root) and change the permission for execution:
`chmod +x gameoverlay.sh`

Execute the script:
`./gameoverlay.sh`

Expected answear is show the id command for root user.

You can exploit the vulnerability changing using de OS module for python 3, following the os.system example command in the file.
