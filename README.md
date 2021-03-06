# Zeal

[![IRC](https://img.shields.io/badge/irc-%23zealdocs-blue.svg?style=flat-square)](https://kiwiirc.com/client/irc.freenode.net/#zealdocs)

> **zeal** *noun*
>
> 1. a feeling of strong eagerness (usually in favor of a person or cause)
> 2. excessive fervor to do something or accomplish some end
> 3. prompt willingness
>
> (from WordNet 3.0)

Zeal is a simple offline documentation browser inspired by [Dash](http://kapeli.com/dash/).

![Screenshot](http://i.imgur.com/SiLvpz8.png)

[More screenshots](http://imgur.com/a/eVi97)

## Build Status

[![Coverity Scan](https://img.shields.io/coverity/scan/4271.svg?style=flat-square)](https://scan.coverity.com/projects/4271)

OS \ Branch | Unstable (master) | Stable (0.1)
------------|-------------------|-------------
Linux | [![Build Status](https://api.shippable.com/projects/54ac2ce4d46935d5fbc19b84/badge?branchName=master)](https://app.shippable.com/projects/54ac2ce4d46935d5fbc19b84/builds/latest) | [![Build Status](https://api.shippable.com/projects/54ac2ce4d46935d5fbc19b84/badge?branchName=0.1)](https://app.shippable.com/projects/54ac2ce4d46935d5fbc19b84/builds/latest)
Windows | [![AppVeyor](https://img.shields.io/appveyor/ci/trollixx/zeal/master.svg?style=flat-square)](https://ci.appveyor.com/project/trollixx/zeal) | [![AppVeyor](https://img.shields.io/appveyor/ci/trollixx/zeal/0.1.svg?style=flat-square)](https://ci.appveyor.com/project/trollixx/zeal)

## Download

Get binary builds for Windows and Linux from the [download page](http://zealdocs.org/download.html).

## How to use

After installing Zeal, you need to download docsets. Go to *File->Options->Docsets*, select the ones you want, and click the *Download* button.

## How to compile

If you prefer to compile Zeal manually.

### Requirements
* [Qt](https://www.qt.io/) (version 5.2.0 or above is required)
* [libarchive](http://libarchive.org/)
* Optionally [libappindicator](https://launchpad.net/libappindicator) for Unity users

To compile it, run `qmake` and `make`.

## Query & Filter docsets

You can limit the search scope by using ':' to indicate the desired docsets.

`java:BaseDAO`

You can also search multiple docsets separating them with a comma:

`python,django:string`

## Command line

If you prefer, you can start Zeal with a query from command line:

`zeal python:bomb`

## Creating your own docsets

You can use [Dash's instructions for generating docsets](http://kapeli.com/docsets).

## Contact and Support

We want your feedback! Here's a list of different ways to contact developers and request help:
* Report bugs and submit feature requests to [GitHub issues](https://github.com/zealdocs/zeal/issues).
* Ask any questions in our [Google Group](https://groups.google.com/d/forum/zealdocs). You can simply send an email to zealdocs@googlegroups.com.
* For a quick chat with developers and other Zeal users use our IRC channel: #zealdocs on [Freenode](https://freenode.net/). Also available through Kiwi IRC [web interface](https://kiwiirc.com/client/irc.freenode.net/#zealdocs). Please, take into consideration possible time zone differences.
* Finally, for a private communications send us [email](mailto:zeal@zealdocs.org).
* And do not forget to follow [@zealdocs](https://twitter.com/zealdocs) on Twitter!

## License

This software is licensed under the terms of the GNU General Public License version 3 (GPLv3). Full text of the license is available in the [COPYING](https://github.com/zealdocs/zeal/blob/master/COPYING) file and [online](http://opensource.org/licenses/gpl-3.0.html).
