heavenbot - a Python IRC bot built using irc3
---------------------------------------------

Current features:

* weekend plugin - shows progress towards the weekend in channel topic

To run, you need to create a config file first. Refer to a sample one in ``src/sample-config.ini``
for details.

* ``pip install -r requirements.txt``
* ``irc3 path/to/yourconfig.ini``

Refer to irc3 documentation for more details: https://irc3.readthedocs.io/en/latest/

TESTING
Installation and requirements
-----------------------------

The target compatibility is Python **3.5+** only. It might work with older versions, but they are
not supported.

If you can't install Python 3.5 globally on your machine, you can try using *pyvenv*
https://github.com/yyuu/pyenv

See ``requirements.txt`` and ``requirements-to-freeze.txt``. A virtualenv is recommended.

heavenbot tries to follow a better PIP workflow as descibed by Kenneth Reitz:
http://www.kennethreitz.org/essays/a-better-pip-workflow

In short:

* keep all installed requirements versioned (pip freeze) in ``requirements.txt``

* keep the "top-level" requirements unversioned in ``requirements-to-freeze.txt``


License
-------

MIT. See the ``LICENSE`` file.
