[![License](https://img.shields.io/github/license/MekDrop/mass-proxy-call.svg?maxAge=2592000)](License.txt) ![GitHub release](https://img.shields.io/github/release/MekDrop/mass-proxy-call.svg?maxAge=2592000)
# Mass Proxy Call

This PHP script will call url from different proxies.

# How to use it?

`proxies.lst` contains list of all proxies than the script can use. Probably this file is outdated. You need to update the data there with something that you find on the internet or/and know. Than you can use `http://HOST_AND_PATH_TO_SCRIPT/index.php?url=http://URL_TO_PING`

It's not quick script and here are no queues so if something fails, it tries to ignore that.

# Requirements

* PHP >= 5.0
* php-curl module
* any webserver than can run this script
