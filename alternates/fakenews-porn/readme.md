----
**Take Note!**  This version of the Hosts file generator, and tests, are for Python 3.5+ only.

----

![readme](https://user-images.githubusercontent.com/36028424/40330477-9df2c2e0-5d7f-11e8-8ac8-511d719a5eae.png)
[![latest release](https://img.shields.io/github/release/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts/releases)
[![license](https://img.shields.io/github/license/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts/blob/master/license.txt)
[![repo size](https://img.shields.io/github/repo-size/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts)
[![contributors](https://img.shields.io/github/contributors/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts/graphs/contributors)
[![Build Status](https://travis-ci.org/StevenBlack/hosts.svg?branch=master)](https://travis-ci.org/StevenBlack/hosts)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/python/black)
[![commits since last release](https://img.shields.io/github/commits-since/StevenBlack/hosts/latest.svg)](https://github.com/StevenBlack/hosts/commits/master)
[![last commit](https://img.shields.io/github/last-commit/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts/commits/master)
[![commit activity](https://img.shields.io/github/commit-activity/y/StevenBlack/hosts.svg)](https://github.com/StevenBlack/hosts/commits/master)

# Unified hosts file with fakenews, porn extensions

This repository consolidates several reputable `hosts` files, and merges them
into a unified hosts file with duplicates removed.  A variety of tailored hosts files are provided.

* Last updated: **September 30 2019**.
* Here's the [raw hosts file with fakenews, porn extensions](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-porn/hosts) containing 55,432 entries.
* Logo by [@Tobaloidee](https://github.com/Tobaloidee).


### List of all hosts file variants

This repository offers [15 different host file variants](https://github.com/StevenBlack/hosts/tree/master/alternates), in addition to the base variant.

The **Non GitHub mirror** is the link to use for some hosts file managers like
[Hostsman for Windows](http://www.abelhadigital.com/hostsman) that don't work
with Github download links.

Host file recipe | Readme | Raw hosts | Unique domains | Non Github mirror
---------------- |:------:|:---------:|:--------------:|:-------------:
Unified hosts = **(adware + malware)** | [Readme](https://github.com/StevenBlack/hosts/blob/master/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts) | 42,405 | [link](http://sbc.io/hosts/hosts)
Unified hosts **+ fakenews** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews/hosts) | 43,347 | [link](http://sbc.io/hosts/alternates/fakenews/hosts)
Unified hosts **+ gambling** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/gambling/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/gambling/hosts) | 44,677 | [link](http://sbc.io/hosts/alternates/gambling/hosts)
Unified hosts **+ porn** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/porn/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/porn/hosts) | 54,490 | [link](http://sbc.io/hosts/alternates/porn/hosts)
Unified hosts **+ social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/social/hosts) | 44,880 | [link](http://sbc.io/hosts/alternates/social/hosts)
Unified hosts **+ fakenews + gambling** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-gambling/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling/hosts) | 45,619 | [link](http://sbc.io/hosts/alternates/fakenews-gambling/hosts)
Unified hosts **+ fakenews + porn** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-porn/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-porn/hosts) | 55,432 | [link](http://sbc.io/hosts/alternates/fakenews-porn/hosts)
Unified hosts **+ fakenews + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-social/hosts) | 45,822 | [link](http://sbc.io/hosts/alternates/fakenews-social/hosts)
Unified hosts **+ gambling + porn** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/gambling-porn/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/gambling-porn/hosts) | 56,762 | [link](http://sbc.io/hosts/alternates/gambling-porn/hosts)
Unified hosts **+ gambling + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/gambling-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/gambling-social/hosts) | 47,152 | [link](http://sbc.io/hosts/alternates/gambling-social/hosts)
Unified hosts **+ porn + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/porn-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/porn-social/hosts) | 56,964 | [link](http://sbc.io/hosts/alternates/porn-social/hosts)
Unified hosts **+ fakenews + gambling + porn** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-gambling-porn/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-porn/hosts) | 57,704 | [link](http://sbc.io/hosts/alternates/fakenews-gambling-porn/hosts)
Unified hosts **+ fakenews + gambling + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-gambling-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-social/hosts) | 48,094 | [link](http://sbc.io/hosts/alternates/fakenews-gambling-social/hosts)
Unified hosts **+ fakenews + porn + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-porn-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-porn-social/hosts) | 57,906 | [link](http://sbc.io/hosts/alternates/fakenews-porn-social/hosts)
Unified hosts **+ gambling + porn + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/gambling-porn-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/gambling-porn-social/hosts) | 59,236 | [link](http://sbc.io/hosts/alternates/gambling-porn-social/hosts)
Unified hosts **+ fakenews + gambling + porn + social** | [Readme](https://github.com/StevenBlack/hosts/blob/master/alternates/fakenews-gambling-porn-social/readme.md) | [link](https://raw.githubusercontent.com/StevenBlack/hosts/master/alternates/fakenews-gambling-porn-social/hosts) | 60,178 | [link](http://sbc.io/hosts/alternates/fakenews-gambling-porn-social/hosts)


**Expectation**: These unified hosts files should serve all devices, regardless
of OS.

## Sources of hosts data unified in this variant

Updated `hosts` files from the following locations are always unified and
included:

Host file source | Description | Home page | Raw hosts | Update frequency | License | Issues
-----------------|-------------|:---------:|:---------:|:----------------:|:-------:|:------:
Steven Black's ad-hoc list | Additional sketch domains as I come across them. |[link](https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts) | [raw](https://raw.githubusercontent.com/StevenBlack/hosts/master/data/StevenBlack/hosts) | occasionally | MIT  | [issues](https://github.com/StevenBlack/hosts/issues) 
Malware Domain List | Malware Domain List is a non-commercial community project. |[link](https://www.malwaredomainlist.com/) | [raw](https://www.malwaredomainlist.com/hostslist/hosts.txt) | weekly | 'can be used for free by anyone'  | [issues](https://www.malwaredomainlist.com/contact.php) 
add.Dead | Dead sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Dead/hosts) | occasionally | GPLv3+  | [issues](https://github.com/FadeMind/hosts.extras/issues) 
hostsVN | Hosts block ads of Vietnamese |[link](https://github.com/bigdargon/hostsVN) | [raw](https://raw.githubusercontent.com/bigdargon/hostsVN/master/option/hosts-VN) | occasionally | MIT  | [issues](https://github.com/bigdargon/hostsVN/issues) 
add.Spam | Spam sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts) | occasionally | GPLv3+  | [issues](https://github.com/FadeMind/hosts.extras/issues) 
Dan Pollock – [someonewhocares](https://someonewhocares.org) | How to make the internet not suck (as much). |[link](https://someonewhocares.org/hosts/) | [raw](https://someonewhocares.org/hosts/zero/hosts) | frequently | non-commercial with attribution  | [issues](hosts@someonewhocares.org) 
MVPS hosts file | The purpose of this site is to provide the user with a high quality custom HOSTS file. |[link](http://winhelp2002.mvps.org/) | [raw](http://winhelp2002.mvps.org/hosts.txt) | monthly | CC BY-NC-SA 4.0  | [issues](mailto:winhelp2002@gmail.com) 
yoyo.org | Blocking with ad server and tracking server hostnames. |[link](https://pgl.yoyo.org/adservers/) | [raw](https://pgl.yoyo.org/adservers/serverlist.php?hostformat=hosts&mimetype=plaintext&useip=0.0.0.0) | frequently |   | [issues](mailto:pgl@yoyo.org) 
Mitchell Krog's - Badd Boyz Hosts | Sketchy domains and Bad Referrers from my Nginx and Apache Bad Bot and Spam Referrer Blockers |[link](https://github.com/mitchellkrogza/Badd-Boyz-Hosts) | [raw](https://raw.githubusercontent.com/mitchellkrogza/Badd-Boyz-Hosts/master/hosts) | weekly | 'non-commercial with attribution'  | [issues](https://github.com/mitchellkrogza/Badd-Boyz-Hosts/issues) 
CoinBlocker | Simple lists that can help prevent cryptomining in the browser or other applications |[link](https://gitlab.com/ZeroDot1/CoinBlockerLists) | [raw](https://zerodot1.gitlab.io/CoinBlockerLists/hosts_browser) | frequently | GPLv3  | [issues](https://gitlab.com/ZeroDot1/CoinBlockerLists/issues) 
UncheckyAds | Windows installers ads sources sites based on https://unchecky.com/ content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/UncheckyAds/hosts) | occasionally |   | [issues](https://github.com/FadeMind/hosts.extras/issues) 
add.2o7Net | 2o7Net tracking sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.2o7Net/hosts) | occasionally | GPLv3+  | [issues](https://github.com/FadeMind/hosts.extras/issues) 
KADhosts | Fraud/adware/scam websites. |[link](https://github.com/azet12/KADhosts) | [raw](https://raw.githubusercontent.com/azet12/KADhosts/master/KADhosts.txt) | frequently | GPLv3  | [issues](https://github.com/azet12/KADhosts/issues) 
AdAway | AdAway is an open source ad blocker for Android using the hosts file. |[link](https://adaway.org/) | [raw](https://raw.githubusercontent.com/AdAway/adaway.github.io/master/hosts.txt) | occasionally | CC BY 3.0  | [issues](https://github.com/AdAway/AdAway/issues) 
add.Risk | Risk content sites based on [hostsfile.org](http://www.hostsfile.org/hosts.html) content. |[link](https://github.com/FadeMind/hosts.extras) | [raw](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Risk/hosts) | occasionally | GPLv3+  | [issues](https://github.com/FadeMind/hosts.extras/issues) 
Tiuxo hostlist - ads | Categorized hosts files for DNS based content blocking |[link](https://github.com/tiuxo/hosts) | [raw](https://raw.githubusercontent.com/tiuxo/hosts/master/ads) | occasional | CC BY 4.0  | [issues](https://github.com/tiuxo/hosts/issues) 
Fake News | An in-progress collection of fake news outlets. |[link](https://github.com/marktron/fakenews) | [raw](https://raw.githubusercontent.com/marktron/fakenews/master/fakenews) | occasional | MIT  | [issues](https://github.com/marktron/fakenews/issues) 
Sinfonietta's snuff-site blocking hosts file | A collection of category-specific host files. |[link](https://github.com/Sinfonietta/hostfiles) | [raw](https://raw.githubusercontent.com/Sinfonietta/hostfiles/master/snuff-hosts) | occasional | MIT  | [issues](https://github.com/Sinfonietta/hostfiles/issues) 
pornhosts -- a consolidated anti porn hosts file | This is an endeavour to find all porn domains and compile them into a single hosts to allow for easy blocking of porn on your local machine or on a network. |[link](https://github.com/Clefspeare13/pornhosts) | [raw](https://raw.githubusercontent.com/Clefspeare13/pornhosts/master/0.0.0.0/hosts) | occasional | MIT  | [issues](https://github.com/Clefspeare13/pornhosts/issues) 
Sinfonietta's porn blocking hosts file | A collection of category-specific host files. |[link](https://github.com/Sinfonietta/hostfiles) | [raw](https://raw.githubusercontent.com/Sinfonietta/hostfiles/master/pornography-hosts) | occasional | MIT  | [issues](https://github.com/Sinfonietta/hostfiles/issues) 
Tiuxo hostlist - pornography | Categorized hosts files for DNS based content blocking |[link](https://github.com/tiuxo/hosts) | [raw](https://raw.githubusercontent.com/tiuxo/hosts/master/porn) | occasional | CC BY 4.0  | [issues](https://github.com/tiuxo/hosts/issues) 



## Extensions
The unified hosts file is optionally extensible.  Extensions are used to include domains by category.  Currently we offer the following categories: `fakenews`, `social`, `gambling`, and `porn`.

Extensions are optional, and can be combined in various ways wth the base hosts file.  The combined products are stored in the [`alternates`](https://github.com/StevenBlack/hosts/tree/master/alternates) folder.

Data for extensions is stored in the [`extensions`](https://github.com/StevenBlack/hosts/tree/master/extensions) folder. You manage extensions by curating this
folder tree, where you will find the data for `fakenews`, `social`, `gambling`, and `porn` extension data that we maintain and provide for you.

## Generate your own unified hosts file

To generate your own unified hosts file you will need Python 3.5 or later.

First install the dependencies with:

    pip3 install --user -r requirements.txt

**Note** we recommend the `--user` flag which installs the required dependencies at the user level. More information about it can be found on pip [documentation](https://pip.pypa.io/en/stable/reference/pip_install/?highlight=--user#cmdoption-user).

To run unit tests, in the top level directory, just run:

    python3 testUpdateHostsFile.py

The `updateHostsFile.py` script will generate a unified hosts file based on the sources in the
local `data/` subfolder.  The script will prompt you whether it should fetch updated versions
(from locations defined by the `update.json` text file in each source's folder). Otherwise, it
will use the `hosts` file that's already there.

### Usage

#### Using Python 3:

    python3 updateHostsFile.py [--auto] [--replace] [--ip nnn.nnn.nnn.nnn] [--extensions ext1 ext2 ext3]

#### Command line options:

`--help`, or `-h`: display help.

`--auto`, or `-a`: run the script without prompting. When `--auto` is invoked,

* Hosts data sources, including extensions, are updated.
* No extensions are included by default.  Use the `--extensions` or `-e` flag
to include any you want.
* Your active hosts file is *not* replaced unless you include the `--replace`
flag.

`--backup`, or `-b`: Make a backup of existing hosts file(s) as you generate
over them.

`--extensions <ext1> <ext2> <ext3>`, or `-e <ext1> <ext2> <ext3>`: the names
of subfolders below the `extensions` folder containing additional
category-specific hosts files to include in the amalgamation. Example:
`--extensions porn` or `-e social porn`.

`--flush-dns-cache`, or `-f`: skip the prompt for flushing the DNS cache.
Only active when `--replace` is also active.

`--ip nnn.nnn.nnn.nnn`, or `-i nnn.nnn.nnn.nnn`: the IP address to use as the
target.  Default is `0.0.0.0`.

`--keepdomaincomments`, or `-k`: `true` (default) or `false`, keep the comments
that appear on the same line as domains.  The default is `true`.

`--noupdate`, or `-n`: skip fetching updates from hosts data sources.

`--output <subfolder>`, or `-o <subfolder>`: place the generated source file
in a subfolder.  If the subfolder does not exist, it will be created.

`--replace`, or `-r`: trigger replacing your active hosts

`--skipstatichosts`, or `-s`: `false` (default) or `true`, omit the standard
section at the top, containing lines like `127.0.0.1 localhost`.  This is
useful for configuring proximate DNS services on the local network.

`--compress`, or `-c`: `false` (default) or `true`, *Compress* the hosts file
ignoring non-necessary lines (empty lines and comments) and putting multiple
domains in each line. Reducing the number of lines of the hosts file improves
the performances under Windows (with DNS Client service enabled).

`--minimise`, or `-m`: `false` (default) or `true`, like `--compress`, but puts
each domain on a separate line. This is necessary because many implementations
of URL blockers that rely on `hosts` files do not conform to the standard which
allows multiple hosts on a single line.

## How do I control which sources are unified?

Add one or more  *additional* sources, each in a subfolder of the `data/`
folder, and specify the `url` key in its `update.json` file.

Add one or more *optional* extensions, which originate from subfolders of the
`extensions/` folder.  Again the url in `update.json` controls where this
extension finds its updates.

Create an *optional* `blacklist` file. The contents of this file (containing a
listing of additional domains in `hosts` file format) are appended to the
unified hosts file during the update process. A sample `blacklist` is
included, and may be modified as you desire.

  * NOTE: The `blacklist` is not tracked by git, so any changes you make won't
be overridden when you `git pull`   this repo from `origin` in the future.

### How do I include my own custom domain mappings?

If you have custom hosts records, place them in file `myhosts`.  The contents
of this file are prepended to the unified hosts file during the update
process.

The `myhosts` file is not tracked by git, so any changes you make won't be
overridden when you `git pull` this repo from `origin` in the future.

### How do I prevent domains from being included?

The domains you list in the `whitelist` file are excluded from the final hosts
file.

The `whitelist` uses partial matching.  Therefore if you whitelist
`google-analytics.com`, that domain and all its subdomains won't be merged
into the final hosts file.

The `whitelist` is not tracked by git, so any changes you make won't be
overridden when you `git pull` this repo  from `origin` in the future.

## How can I contribute hosts records?

If you discover sketchy domains you feel should be included here, here are some ways to contribute them.

### Option 1: contact one of our hosts sources

The best way to get new domains included is to submit an issue to any of the data providers whose home pages are [listed here](https://github.com/StevenBlack/hosts#sources-of-hosts-data-unified-in-this-variant). This is best because once you submit new domains, they will be curated and updated by the dedicated folks who maintain these sources.


### Option 2: add your domains to Steven Black's personal data file

Fork this hosts this repo and add your links to [https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts](https://github.com/StevenBlack/hosts/blob/master/data/StevenBlack/hosts).

Then, submit a pull request.

**WARNING**: this is less desirable than Option 1 because the ongoing curation falls on us and what you've just done is created more work for us.

### Option 3: create your own hosts list as a repo on Github

If you're able to curate your own collection of sketchy domains, then curate your own hosts list.  Then signal the existence of your repo as [a new issue](https://github.com/StevenBlack/hosts/issues) and we may include your new repo into the collection of sources we pull whenever we create new versions.


## What is a hosts file?

A hosts file, named `hosts` (with no file extension), is a plain-text file
used by all operating systems to map hostnames to IP addresses.

In most operating systems, the `hosts` file is preferential to `DNS`.
Therefore if a domain name is resolved by the `hosts` file, the request never
leaves your computer.

Having a smart `hosts` file goes a long way towards blocking malware, adware,
and other irritants.

For example, to nullify requests to some doubleclick.net servers, adding these
lines to your hosts file will do it:

    # block doubleClick's servers
    0.0.0.0 ad.ae.doubleclick.net
    0.0.0.0 ad.ar.doubleclick.net
    0.0.0.0 ad.at.doubleclick.net
    0.0.0.0 ad.au.doubleclick.net
    0.0.0.0 ad.be.doubleclick.net
    # etc...


## We recommend using `0.0.0.0` instead of `127.0.0.1`

Traditionally most host files use `127.0.0.1`, the *loopback address*, to establish an IP connection to the local machine.

We prefer to use `0.0.0.0`, which is defined as a non-routable meta-address used to designate an invalid, unknown,
or non applicable target.

Using `0.0.0.0` is empirically faster, possibly because there's no wait for a timeout resolution. It also does not
interfere with a web server that may be running on the local PC.

## Why not use just `0` instead of `0.0.0.0`?
We tried that.  Using `0` doesn't work universally.


## Location of your hosts file
To modify your current `hosts` file, look for it in the following places and modify it with a text
editor.

**mac OS (until 10.14.x macOS Mojave), iOS, Android, Linux**: `/etc/hosts` file.

**macOS Catalina:** `/private/etc/hosts` file.

**Windows**: `%SystemRoot%\system32\drivers\etc\hosts` file.

## Updating hosts file on Windows

On Linux and Mac OS X, you can simply run the Python script, but on Windows, more
work is required due to compatibility issues in implementing some of the functionality
for Windows. It is preferable to run the batch file as follows:

```
updateHostsWindows.bat
```

This file MUST be run in command prompt with administrator privileges in
the repository directory. In addition to updating the hosts file, it can also
replace the existing hosts file, and reload the DNS cache. It goes without
saying that in order for this to work, you must be connected to the internet.

To open a command prompt as administrator in the repository's directory, do the following:

**Windows XP**: Start -> Run -> `cmd`

**Windows Vista, 7**: Start Button -> type `cmd` -> right-click Command Prompt ->
"Run as Administrator"

**Windows 8**: Start -> Swipe Up -> All Apps -> Windows System -> right-click Command Prompt ->
"Run as Administrator"

**Windows 10**: Start Button -> type `cmd` -> right-click Command Prompt ->
"Run as Administrator"

You can also refer to the "Third-Party Hosts Managers" section for further recommended solutions from third parties.

## Reloading hosts file
Your operating system will cache DNS lookups. You can either reboot or run the following commands to
manually flush your DNS cache once the new hosts file is in place.

| The Google Chrome browser may require manually cleaning up its DNS Cache on `chrome://net-internals/#dns` page to thereafter see the changes in your hosts file. See: https://superuser.com/questions/723703
:-----------------------------------------------------------------------------------------

### Windows

Open a command prompt with administrator privileges and run this command:

```
ipconfig /flushdns
```

|If you want to use a huge hosts file by merging [hphosts](https://www.hosts-file.net) (NOT INCLUDED HERE) you need to DISABLE and STOP `Dnscache` service before you replace hosts file in Windows Systems. You have been warned.|
:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Before flushing the DNS cache, open a command prompt with administrator privileges and run this command:

```
sc config "Dnscache" start= disabled
sc stop "Dnscache"
```

### Linux

Open a Terminal and run with root privileges:

**Debian/Ubuntu** `sudo service network-manager restart`

**Linux Mint** `sudo /etc/init.d/dns-clean start`

**Linux with systemd**: `sudo systemctl restart network.service`

**Fedora Linux**: `sudo systemctl restart NetworkManager.service`

**Arch Linux/Manjaro with Network Manager**: `sudo systemctl restart NetworkManager.service`

**Arch Linux/Manjaro with Wicd**: `sudo systemctl restart wicd.service`

**RHEL/Centos**: `sudo /etc/init.d/network restart`

**FreeBSD**: `sudo service nscd restart`

To enable the `nscd` daemon initially, it is recommended that you run the following commands:

```
sudo sysrc nscd_enable="YES"
sudo service nscd start
```

Then modify the `hosts` line in your `/etc/nsswitch.conf` file to the following:

```
hosts: cache files dns
```

**Others**: Consult [this wikipedia article](https://en.wikipedia.org/wiki/Hosts_%28file%29#Location_in_the_file_system).

### Mac OS X

Open a Terminal and run:
```
sudo dscacheutil -flushcache;sudo killall -HUP mDNSResponder
```

## Release management

This repository uses [Release-It!](https://webpro.github.io/release-it/), an excellent CLI release
tool for Github repos and npm packages, to automate creating [releases](https://github.com/StevenBlack/hosts/releases).
This is why the [package.json](https://github.com/StevenBlack/hosts/blob/master/package.json) and
[.release-it.json](https://github.com/StevenBlack/hosts/blob/master/.release-it.json) files are bundled.

## Goals of this unified hosts file

The goals of this repo are to:

1. automatically combine high-quality lists of hosts,

2. provide easy extensions,

3. de-dupe the resultant combined list,

4. and keep the resultant file reasonably sized.

A high-quality source is defined here as one that is actively curated.  A
hosts source should be frequently updated by its maintainers with both
additions and removals.  The larger the hosts file, the higher the level of
curation is expected.

For example, the (huge) hosts file from [hosts-file.net](https://hosts-file.net)
is **not** included here because it is very large (780,000+ entries)
and doesn't currently display a corresponding high level of curation activity.

It is expected that this unified hosts file will serve both desktop and mobile
devices under a variety of operating systems.

## Third-Party Hosts Managers

* [Unified Hosts AutoUpdate](https://github.com/ScriptTiger/Unified-Hosts-AutoUpdate "Unified Hosts AutoUpdate") (for Windows): The Unified Hosts AutUpdate package is purpose-built for this unified hosts project as well as in active development by community members. It's sophisticated enough to allow any novice the ability to install and uninstall the blacklist of their choosing to their local hosts file and keep it automatically up to date, while also being minimal enough to be able to be easily placed in a shared network location and deployed across an organization via group policies. And since it is in active development by community members, your bug reports, feature requests, and other feedback are most welcome.

* [ViHoMa](https://github.com/cmabad/ViHoMa) is a Visual Hosts file Manager, written in Java, by Christian Martínez.  Check it out!

## Interesting Applications

* [Hostile](https://github.com/feross/hostile) is a nifty command line utility to easily add or remove domains from your hosts file.  If our hosts files are too aggressive for you, you can use `hostile` to remove domains, or you can use `hostile` in a bash script to automate a post process each time you download fresh versions of hosts.

* [macOS Scripting for Configuration, Backup and Restore](https://github.com/tiiiecherle/osx_install_config) helps customizing, re-installing and using macOS. It also provides a [script](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/launchd_and_script/hosts_file_generator.sh) to install and update the hosts file using this project on macOS. In combination with a [launchd](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/launchd_and_script/com.hostsfile.install_update.plist) it updates the hosts file every x days (default is 4). To install both download the github repo and run the [install script](https://github.com/tiiiecherle/osx_install_config/blob/master/09_launchd/9b_run_on_boot/root/1_hosts_file/install_hosts_file_generator_and_launchdservice.sh) from the directory one level up.

* [Pi-hole](https://pi-hole.net/) is a network-wide DHCP server and ad blocker that runs on [Raspberry Pi](https://en.wikipedia.org/wiki/Raspberry_Pi). Pi-hole uses this repository as one of its sources.     This is a very interesting project to setup yourself, or you can [buy one pre-loaded](https://uk.pi-supply.com/products/pi-hole-kit-network-wide-ad-blocker).

* [Block ads and malware via local BIND9 DNS server](https://github.com/mueller-ma/block-ads-via-dns "Block ads and malware via local DNS server") (for Debian, Raspbian & Ubuntu): Set up a local DNS server with a `/etc/bind/named.conf.blocked` file, sourced from here.

* [Block ads, malware, and deploy parental controls via local DualServer DNS/DHCP server](https://scripttiger.github.io/dualserver "Block ads, malware, and deploy parental controls via local DualServer DNS/DHCP server") (for BSD, Windows & Linux): Set up a blacklist for everyone on your network using the power of the unified hosts reformatted for DualServer. And if you're on Windows, this project also maintains an update script to make updating DualServer's blacklist even easier.

* [Blocking ads and malwares with unbound](https://deadc0de.re/articles/unbound-blocking-ads.html "Blocking ads and malwares with unbound") – [Unbound](https://www.unbound.net/ "Unbound is a validating, recursive, and caching DNS resolver.")  is a validating, recursive, and caching DNS resolver.

* [DNSMasq conversion script](https://gist.github.com/erlepereira/c11f4f7a3f60cd2071e79018e895fc8a#file-dnsmasq-antimalware) This github gist has a short shell script (bash, will work on any 'nix) and uses 'wget' & 'awk' present in most distros, to fetch a specified hosts file and convert it the format required by dnsmasq. Supports ipv4 and ipv6. Designed to be used as either a shell script, or can be dropped into /etc/cron.weekly (or wherever suits). Script is short and easily edited, also has a short document attached with notes on dnsmasq setup.

## Contribute!

Please read our [Contributing Guide](https://github.com/StevenBlack/hosts/blob/master/contributing.md). Among other things, this explains how we organize files and folders in this repository.

We are always interested in discovering well-curated sources of hosts.  If you find one, please open an [issue](https://github.com/StevenBlack/hosts/issues) to draw our attention.

Before you create or respond to any issue, please read our [code of conduct](https://github.com/StevenBlack/hosts/blob/master/code_of_conduct.md).
