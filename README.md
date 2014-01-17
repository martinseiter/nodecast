nodecast
===

nodecast is a high performance live streaming transcoder and stream "muxer"

### How to install?
Just clone this repositore in a directory of your choice.

### How to configure?
```nano *.json``` and edit to your needs.

### Why multiple files?
nodecast is a streaming system split into multiple scripts to be able to install each script on a different server (distribute load over multiple host systems). Installing the scripts on different servers also prevents your streaming network from being flooded directly at the transcoder or dj server.

### How to run?
After configuring all the scripts (.json files) you can fire up the scripts by running ```./scriptname.js < scriptname.json``` (e.g. ```./transcoder.js < transcoder.json```).

### Bugs?
If we find bugs, we are gonna fix them. But we don't always find bugs and therefor need your help: If you find any type of bug (memory leak, high cpu usage, weird behaviour when doing something special, etc.), please open a new issue ticket.
