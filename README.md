# cyrus-imapd

Forked version of cyrus-imapd with ClearOS changes applied

## Update usage
  Add __#kojibuild__ to commit message to automatically build

* git clone git://github.com/clearos/cyrus-imapd.git
* cd cyrus-imapd
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/cyrus-imapd.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
