mcollective-agent-yum
=====================

Make yum commands accessible through mcollective (https://puppetlabs.com/mcollective/).

Commands
--------

### install

Takes an input of a package name and installs the package 

### upgrade

Takes an input of a package name and upgrades the package 

### reinstall 

Takes an input of a package name and reinstalls the package

### check-update

Checks for updates 

### update

Executed a yum update. Take care!

### downloadonly

Pulls down updates to the server. Takes an optional package parameter which restricts to only the named package and any pre-requisites. 

### clean 

Clean various caches. Takes an optional mode parameter (all, headers, packages, metadata, dbcache, plugins, expire-cache). Defaults to "all"