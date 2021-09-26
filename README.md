# Cloudflare Dynamic DNS IP Updater (Ipv6 and Ipv4)
<img alt="GitHub" src="https://img.shields.io/github/license/Anveshpoda/cloudflare-ipv6-ipv4-ddns-updater?color=black"> <img alt="GitHub last commit (branch)" src="https://img.shields.io/github/last-commit/Anveshpoda/cloudflare-ipv6-ipv4-ddns-updater/main"> <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/Anveshpoda/cloudflare-ipv6-ipv4-ddns-updater">

This script is used to update dynamic DNS entries for accounts on Cloudflare.

## Installation

```bash
https://github.com/Anveshpoda/cloudflare-ipv6-ipv4-ddns-updater.git
```

## Usage
This script is used with crontab. Specify the frequency of execution through crontab.

```bash
# ┌───────────── minute (0 - 59)
# │ ┌───────────── hour (0 - 23)
# │ │ ┌───────────── day of the month (1 - 31)
# │ │ │ ┌───────────── month (1 - 12)
# │ │ │ │ ┌───────────── day of the week (0 - 6) (Sunday to Saturday 7 is also Sunday on some systems)
# │ │ │ │ │ ┌───────────── command to issue                               
# │ │ │ │ │ │
# │ │ │ │ │ │
# * * * * * /bin/bash {Location of the script}
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.





