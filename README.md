About Robomongo
===============

[Robomongo](http://www.robomongo.org) is a shell-centric cross-platform MongoDB management tool. Unlike most other MongoDB admin UI tools, Robomongo embeds the actual `mongo` shell in a tabbed interface with access to a shell command line as well as GUI interaction.

Starting from version 0.9, Robomongo is compatibile with MongoDB 3.x (including SCRAM-SHA-1 auth and support for WiredTiger storage engine). Robomongo 0.9 embeds the **MongoDB 3.2** shell.

Robomongo 0.8.x embeds the **MongoDB 2.4.0** shell.

What's Planned for the Next Release?
====================================

We are currently working towards [Robomongo 0.9.0 RC10 milestone](https://github.com/paralect/robomongo/milestone/14).  
 
Currently in progress:
- SSL supported connections
- Cross Plaftorm Hi-DPI support (Qt 5.7 transition)

Plans for Future:
- User Roles
- Replica Sets
- Enhancements for stability, running without crashes
- More Documentation
- Unit Tests
- Refactoring Debug Log module

Supported Platforms
===============

**Supported MongoDBs:**

| MongoDB Versions      | MongoDB Cloud |
| :-------------------- | :------------ |
| 3.2                   | MongoDB Atlas |
| 3.0                   | Compose       |
| 2.6                   | mLab          |

**Note**: Currently Robomongo supports connection to single server of a replica set. Support for connection to **Replica Sets** is one of the most important features of next Robomongo release plan.

**Supported OS Platforms:**

| Windows                |   Mac            | Linux                       |        
|:---------------------- | :---------------| :---------------------------|
| Windows 64-bit 10      |  Mac OS X 10.11  | Linux Ubuntu 16.04 64-bit*  |
  Windows 64-bit 8.1     |  Mac OS X 10.10  | Linux Ubuntu 14.04 64-bit*  |
| Windows 64-bit 7       |                  | Linux CentOS 7 64-bit*      |
|                        |                  | Linux CentOS 6 64-bit*      |

\* latest stable build

Download
========

You can download tested install packages for OS X, Windows, and Linux from our site: [www.robomongo.org](http://www.robomongo.org).

The latest release candidate is currently **Robomongo 0.9.0 RC9**. (http://blog.robomongo.org/robomongo-rc9/).

The latest stable release is currently **Robomongo 0.8.5**. (http://blog.robomongo.org/whats-new-in-robomongo-0-8-5/)

Support
=======

Robomongo is an open source project driven by volunteers. We'll try to get to your questions as soon as we can, but please be patient :).

You can:

 - [Create a new issue in the Github issue queue](https://github.com/paralect/robomongo/issues)

 - [Join developer discussion on Gitter](https://gitter.im/paralect/robomongo) [![Join the chat at https://gitter.im/paralect/robomongo](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/paralect/robomongo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Build
=====

The wiki contains prerequisites and instructions to [Build Robomongo](https://github.com/paralect/robomongo/wiki).

If you want to compile from source yourself, you should be able to do so cleanly from a [release branch](https://github.com/paralect/robomongo/releases).

Contribute!
===========

### Suggest Features

New feature suggestions or UI improvements are always welcome.

This project is powered by open source volunteers, so we have a limited amount of development resource to address all requests. We will certainly make best efforts to progress (particularly for those with strong community upvotes).

### Code Contributions

Code contributions are always welcome! Just try to follow our pre-commit checks and coding style: 
- [Robomongo Code Quality](https://github.com/paralect/robomongo/wiki/Robomongo-Code-Quality)
- [Robomongo Coding Style](https://github.com/paralect/robomongo/wiki/Robomongo-Coding-Style)

If you plan to contribute, please create a Github issue (or comment on the relevant existing issue) so we can help coordinate with upcoming release plans.

For a general workflow, see Github's guide to [Fork a Repo](https://help.github.com/articles/fork-a-repo/).

Pull requests (PRs) should generally be for discrete issues (i.e. one issue per PR please) and be clean to merge against the current master branch. It would also be helpful if you can confirm what testing has been done (specific O/S targets and MongoDB versions if applicable).

A usual naming approach for feature branches is `issue-###`. Include the issue number in your commit message / pull request description to link the PR to the original issue.

For example:
```#248: updated QScintilla to 2.4.8 for retina display support".```

### Design

There are some cosmetic issues we could use help with (designing images or UI). They are marked in the issue queue with a [`Cosmetic`](https://github.com/paralect/robomongo/labels/cosmetic) label. If you see an open issue that you'd like to contribute to, please feel free to volunteer by commenting on it.

### Testing

There are a number of issues we could use help with reproducing. They are marked in the issue queue with a [`Needs Repro`](https://github.com/paralect/robomongo/labels/needs%20repro) label. If you see an open issue that doesn't appear to be reproducible yet, please feel free to test and comment with your findings.


License
=======

Copyright (C) 2013-2016 [Paralect, Inc](http://www.paralect.com)

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License version 3 as 
published by the Free Software Foundation.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
