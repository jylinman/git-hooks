Git Hooks
================================

Utility hooks for your git repository.

How to Use
--------------------------------

* Symlink this directory to .git/hooks

	ln -s /path/to/this/directory /path/to/your/git/repo/.git/hooks

* Copy config.php.tmpl to config.php

	cp /path/to/your/git/repo/.git/hooks/config.php.tmpl /path/to/your/git/repo/.git/hooks/config.php

* Edit config.php and comment out any hooks you don't want to run, add others, etc.