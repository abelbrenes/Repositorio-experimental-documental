---
title: Unix Operating System Unsupported Version Detection
Severity: Critical
ID: 33850
keywords: unix, unsupported, 33850
last_updated: March 30, 2020
tags: [critial, incident]
summary: "Unix Operating System Unsupported Version Detection"
sidebar: incidente_01
permalink: incidente_01.html
folder: indicentes-S.O.
conf: Public
lang: es
---


# Unix Operating System Unsupported Version Detection
## According to its self-reported version number, the Unix operating system running on the remote host is no longer supported.

### Problem

Lack of support implies that no new security patches for the product will be released by the vendor. As a result, it is likely to contain security vulnerabilities.


### Solution

- Upgrade to a version of the Unix operating system that is currently supported.

#### Steps

1. Ubuntu
- Ubuntu 12.04 support ended on 2017-04-30.
Upgrade to Ubuntu 19.10 / LTS 18.04 / LTS 16.04.
For more information, see : https://wiki.ubuntu.com/Releases

- Ubuntu 12.10 support ended on 2014-05-16.
Upgrade to Ubuntu 19.10 / LTS 18.04 / LTS 16.04.
For more information, see : https://wiki.ubuntu.com/Releases

- Ubuntu 13.04 support ended on 2014-01-27.
Upgrade to Ubuntu 19.10 / LTS 18.04 / LTS 16.04.
For more information, see : https://wiki.ubuntu.com/Releases

- Ubuntu 10.04 support ended on 2013-05-09 (Desktop) / 2015-04-30 (Server).
Upgrade to Ubuntu 19.10 / LTS 18.04 / LTS 16.04.
For more information, see : https://wiki.ubuntu.com/Releases

2. Debian.
- Debian 7.0 support ended on 2016-04-26 end of regular support / 2018-05-01 (end of long-term support for Wheezy-LTS).
Upgrade to Debian Linux 9.x ("Stretch").
For more information, see : http://www.debian.org/releases/

3. Fedora.
- Fedora release 13 support ended on 2011-06-24.
Upgrade to Fedora 30 / 31.
For more information, see : https://fedoraproject.org/wiki/End_of_life

- Fedora release 14 support ended on 2011-12-08.
Upgrade to Fedora 30 / 31.
For more information, see : https://fedoraproject.org/wiki/End_of_life

- Fedora release 15 support ended on 2012-06-26.
Upgrade to Fedora 30 / 31.
For more information, see : https://fedoraproject.org/wiki/End_of_life
.

### Comments

- Source: https://www.tenable.com/products/nessus/nessus-professional
