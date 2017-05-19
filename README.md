# SourceMod & MetaMod Updater
[![Twitter Follow](https://img.shields.io/badge/Twitter-Follow-lightgrey.svg?style=flat-square)](https://twitter.com/kennyLtv)  [![Facebook Page](https://img.shields.io/badge/Facebook-Like-lightgrey.svg?style=flat-square)](https://www.facebook.com/kennyLtv/)  [![Slack Chat](https://img.shields.io/badge/%23%20Slack-Chat-brightgreen.svg?style=flat-square)](https://kennyl.slack.com/)  [![PayPal Donate](https://img.shields.io/badge/PayPal-Donate-blue.svg?style=flat-square)](https://paypal.me/kennyLtv)

### Prerequisites
* CentOS 7 - More to come.
* WGET
* cURL
### Info
This script will only update current installs. As it deletes the config directory from SourceMod and MetaMod. 

### Setup
To run the script you need to modify the following
```
DIRS=("$HOME/s1" "$HOME/s2")
```

This is how you set your server install path. You need to go up to the point on the directory of the csgo directory. So if you installed your server with [Linux Game Server Managers](https://gameservermanagers.com/) usually the path is serverfiles/csgo from the directory of the install.

Please note that the paths for your installs should be full paths so that it doesn't matter where you place the scripts.

### Why?
I wrote this script because I got tired of SourceMod overwriting my configs when I would update SourceMod due to me not paying attention while I did it. Also because I have like 6 servers to update it on.....

## Authors

* **Kenny Lindelof** - *Mmmmm code*

See also the list of [contributors](https://github.com/kennyLtv/SM-MM-Updater/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Links 
* [SourceMod](http://www.sourcemod.net/)
* [MetaMod](https://www.metamodsource.net/)