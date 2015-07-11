Use Gobject Introspection (Gtk3) in a virtualenv.

Alternatives
------------

Vext is a workaround, you might want to check out pgi, fill in
the gaps in it's implementation and make vext.gi obsolete !

Being based on CFFI, pgi will also work on other python 
implementations, such as Pypy.


Prerequisites
-------------
Gtk3 with Gobject Introspection installed into system python, 
on Linux, Windows or OSX.

In virtualenv
-------------

Make sure pip and setuptools are up to date

(my-virtualenv) $ pip install -U pip setuptools

Allow virtualenv to access pygi

(my-virtualenv) $ pip install vext.gi


Reporting Bugs
--------------

Report bugs to the [vext project](//github.com/stuaxo/vext/issues)


This has been used quite a bit for the shoebot project, if you
do hit any bugs please report them.
