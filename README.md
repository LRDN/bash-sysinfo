# System Information Script

Bash script to show basic system information such as kernel version, uptime and resource usage on login. Compatible with Ubuntu and other Debian-based Linux distributions.

## Installation

Clone this repository into a temporary directory.

```sh
git clone https://github.com/lrdn/bash-sysinfo.git
```

Place the script in the directory for non-system executables.

```sh
sudo install -m 755 bash-sysinfo/bin/bash-sysinfo /usr/local/bin/bash-sysinfo
```

Run the installation command to add required cron and login message entries.

```sh
sudo bash-sysinfo install
```
