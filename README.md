# Temporary Workspace

Create temporary AWS workspaces on the cheap.

See blog post at https://inodes.org/xxx for details
The TLDR is
* Workspaces require SimpleAD
* SimpleAD costs $67/month
* That's a lot for a single user workspace that is used a few times a month.

# Usage

First create a config file
``` bash
cp etc/config.ecample etc/config
vi etc/config
```

See the sample config for docs.

Start the workspace up

``` bash
bin/start-workspace
```

When you are done, kill it

``` bash
bin/stop-workspace
```
