# ansible sync-file

Ansible implementation of sync file from https://github.com/wikimedia/mediawiki-tools-scap

the `sync-file` bash script in the `bin` directory wraps ansible.

The `nearest-host-module` is a rudimentary module that tries to find the
closest host from the host list (from the dsh group file) from which to sync.
