
Loxodo -- Password Safe V3 compatible Password Vault
Copyright (C) 2008 Christoph Sommer <mail@christoph-sommer.de>
Copyright (C) 2011 Adam Hamsik <adam.hamsik@chillisys.com>

Loxodo lives at http://www.christoph-sommer.de/loxodo


Quickstart
----------

./loxodo.py
	runs Loxodo in GUI mode (if available)

./loxodo.py -h
	displays help about Loxodo's cmdline mode

./setup.py py2app
	creates a stand-alone .app (Mac OS X), wxPython is required: http://www.wxpython.org/download.php 

./setup.py py2exe
	creates a stand-alone .exe (Windows)

./loxodo.py -i
	runs Loxodo in CLI Interactive mode

NOTES
-----

This gitfork of loxodo focuses on CLI options. It tracks the upstream GUI, but
has the added features to the CLI:

* import and export databases from/to CSV files.
* add/modify/delete database records.
* search/list/show entries.
* create random passwords, using a somehow sensible character policy.

TODO
----

* Open and merge a different database into the existing one.
* Integrate v3 and v4 databases.
* Add multiple password support.
