AuthKeyDB
=========

A web interface for centrally managing SSH authorized_keys.

It is designed to be used with OpenSSH 6.2 (or older patched versions by RedHat)
that have an `AuthorizedKeysCommand` option which executes a script to get a user's
authorized SSH keys.

This version of the script is primarily designed for use in an environment that uses
AFS and ZFS mounted home directories which are not accessible to the SSH daemon, therefore
preventing the use of`~/.ssh/authorized_keys`.
