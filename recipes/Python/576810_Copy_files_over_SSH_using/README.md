###Copy files over SSH using paramiko

Originally published: 2009-06-16 05:21:53
Last updated: 2015-12-06 14:19:15
Author: ccpizza 

This script copies files in unattended mode over SSH using a glob pattern. It uses the [paramiko](http://www.lag.net/paramiko/) module behind the scenes. It operates as an actual SSH client, and does *not* rely on any command line utilities, such as `scp`.