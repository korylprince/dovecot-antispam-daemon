dovecot-antispam-daemon
<https://github.com/korylprince/dovecot-antispam-daemon>

Here's a simple way to use dovecot-antispam with sa-learn. This works better than the sa-learn-pipe.sh script on the dovecot wiki as it won't hang the server on large amounts of messages being marked as spam.

This was used on Ubuntu, but you can figure it out. Needs python.
#Usage#

Put 91-plugin.conf in /etc/dovecot/conf.d/

Put antispam-daemon somewhere in $PATH

antispam-daemon.conf is an Upstart script you can put in /etc/init/

If you have any issues or questions (or want to make it better), email the email address below, or open an issue at: <https://github.com/korylprince/dovecot-antispam-daemon/issues>

Can't promise anything though.

#Copyright Information#
Copyright 2013 Kory Prince (korylprince AT gmail DAWT com).

License is the "Do Whatever You Want With It" License. Public Domain - whatever you want.

