![](https://raw.githubusercontent.com/Monitorr/Monitorr/master/assets/img/monitorrbanner.png)


## - *Monitorr* is a webfront to live display the status of any webapp or service

[![](https://img.shields.io/github/release/monitorr/monitorr.svg?style=flat)](https://github.com/monitorr/monitorr/releases) [MASTER]


[![Docker build](https://img.shields.io/docker/build/monitorr/monitorr.svg?maxAge=2592000)](https://hub.docker.com/r/monitorr/monitorr/) [DOCKER]


[![GitHub (pre-)release](https://img.shields.io/github/release/monitorr/monitorr/all.svg)](https://github.com/monitorr/monitorr/releases) [DEVELOP]


**NOTICE** (12 MARCH 2018): This build is a release candidate for version 1.0. Target master branch release date is 15 March.  If you are testing this build you will need to use a new local repo for testing. it is NOT possible to upgrade from a previous version of Monitorr. We thank you for helping us develop.  

## Features:

**Latest major change:** Integrated settings page. 

- LIVE! (w/ option to pause live updating)
- Self-hosted
- Monitor any app on any domain (Curl as primary check, sockopen as fallback) (UPDATED)
- Responsive mobile display (NEW)
- Integrated settings page w/ authentication (NEW)
- Host system resources display (CPU, MEM, HD, PING, Uptime)
- Server DTG data
- Update Monitorr via web UI / branch switching w/ update notification (NEW)
- Minimal UI for iFrame displays (See [WIKI](https://github.com/Monitorr/Monitorr/wiki/Integration:--Organizr))
- User customizable system threshold colors

**Features in development:**
- Settings page (Testing)
- Reverse proxy authentication
- Alternate hot links (Testing)


## Screenshot :

![](https://i.imgur.com/h8S1976.png)

### Mobile:

![](https://i.imgur.com/RKp2yiZ.jpg?1)


### In use with [Organizr](https://github.com/causefx/Organizr) :

![](https://i.imgur.com/SwevXaG.png)


## Prerequisites:
1) [PHP](https://secure.php.net/downloads.php) (7.1+ recommended)
2) [PHP PDO](http://php.net/manual/en/book.pdo.php)
3) [PHP cURL](https://secure.php.net/manual/en/book.curl.php)
4) [SQLite](https://www.sqlite.org/index.html)
5) [GIT](https://git-scm.com/download/win) (Recommended for Windows hosts (see wiki)

## Libraries used in this project:
- [Alpaca](https://github.com/gitana/alpaca/)
- [PHP Login](https://github.com/panique/php-login-one-file)
- [Form Validation](https://github.com/DrRoach/FormValidation)


## Quick Start:
- See full configuration instructions in the WiKi: https://github.com/Monitorr/Monitorr/wiki
1) Clone/download repository to your webserver
2) Make sure the user account that runs your webserver has RW access to the monitorr folder (eg. for linux it's usually www-data:www-data) - this is for updates to work properly.
3) Browse to <localhost\domain>/monitorr/index.php 
4) Establish data directory, and user database.
5) Configure Monitorr
6) Chill


## Feature Requests:
 [![Feature Requests](https://cloud.githubusercontent.com/assets/390379/10127973/045b3a96-6560-11e5-9b20-31a2032956b2.png)](https://feathub.com/Monitorr/Monitorr)

**Current feature requests:**

[![Feature Requests](https://feathub.com/Monitorr/Monitorr?format=svg)](https://feathub.com/Monitorr/Monitorr)


## Connect:

- Need live help?  Join us on Discord:   [![Discord](https://img.shields.io/discord/102860784329052160.svg)](https://discord.gg/YKbRXtt)

- E-mail: monitorrapp@gmail.com

- Buy us a beer! Donate:        [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/monitorrapp)

- Check out our sister app **Logarr**:  https://github.com/Monitorr/Logarr

## About Us:
- [seanvree](https://github.com/seanvree) (Windows Wizard)
- [jonfinley](https://github.com/jonfinley) (Linux Dude)
- [wjbeckett](https://github.com/wjbeckett)

## Credits:
- [Causefx](https://github.com/Causefx)
- [Roxedux](https://github.com/si0972)
- [christronyxyocum](https://github.com/christronyxyocum)
