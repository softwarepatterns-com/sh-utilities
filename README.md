# Sh Utilities

These are useful utilties and repeatable patterns in the shell. Nothing complicated.

Copy and paste these freely into your own work. For companies and countries that require a licence, say [MIT](./LICENSE.md). Attribute this page if you can so that others will donate as well.

If you want to donate your own scripts, send them to me or make a PR.

## [Wait For](./wait-for.sh)

Wait for a command to be successful.

First argument is the number of seconds to wait between retries. The rest of the arguments are the command to execute.

### Usage

`./wait-for.sh 10 "ping -c 1 example.com"`

`./wait-for.sh 15 ping -c 1 example.com`

### Why?

Docker orchastration, mostly.

([source](./wait-for.sh))
