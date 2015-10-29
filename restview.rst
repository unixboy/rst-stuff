**How to browse (no text editor) .rst**




.rst files are ReStructuredText format.
They look like text files, but can be rendered into HTML with the Python docutils package.

restview is available from the Python Package Index:

::

 http://pypi.python.org/pypi/restview. You can also pip install restview.

::

  mkdir restview
  cd restview/
  virtualenv-2.7 venv   
  ./venv/bin/pip install restview
  ./venv/bin/restview ~/path/FILE.rst
