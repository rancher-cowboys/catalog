Redmine on Rancher
==================

This will install a [redmine][redmine] stack using the `latest` available redmine
docker image and postgres as database server.

As it's the first rancher version and there are more, you'll be always
notified about updates from rancher's catalog.

Redmine's container port is `3000`. This stack does not open any port by
default to not conflict with other stacks.

If you'd like to open the port you should ensure that the
`Start services after creating` checkbox is unchecked and then upgrade the
container to manually open the port.

[redmine]: http://www.redmine.org
