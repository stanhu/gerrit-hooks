gerrit-hooks
============

This repository contains Gerrit hook scripts. While working with Gerrit, I
noticed that there was no equivalent to Git's post-receive-email script for
when changes were actually merged into the branch.  I wrote a simple script to
e-mail the diff to all users specified in the repository's config.mailinglist
configuration setting.

Stan Hu <stanhu at gma il.com>
