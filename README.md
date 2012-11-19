upshot
======

upshot is an automatic screen shot uploader for OS X, written in Python.

> *Note:* This is experimental software and probably does not do what you want yet without massaging the source code.
> I drop ``XXX`` comments into the source code when I am cutting corners to make it easy to spot what needs fixed.
> As always, pull requests and Issues on github are welcome!

How to run it
-------------
# Create a [virtualenv][virtualenv].
# ``pip install -r requirements.txt``
# ``./upshot.py``

[virtualenv]: http://www.virtualenv.org/

Configuration
-------------
Take a look at ``upshot.py`` for constants. You can override all those in a (new) file ``settings_local.py``.

License
-------
upshot is released under a BSD license. Read the file ``LICENSE`` for more information.