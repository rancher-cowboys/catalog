Redmine on Rancher
==================

This will install a [redmine][redmine] v3.3 stack using postgres as database
server.

Redmine's container port is `3000`. This stack does not open any port by
default to not conflict with other stacks.

If you'd like to open the port you should ensure that the
`Start services after creating` checkbox is unchecked and then upgrade the
container to manually open the port.

[redmine]: http://www.redmine.org
