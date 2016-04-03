Notes
=====
- Requires Matplotlib which is fiddly to get working in OSX.
  I followed the advice at https://stackoverflow.com/questions/33100969/matplotlib-example-code-not-working-on-python-virtual-environment and used a PyQt4 backend. 
  To install PyQt4, i used homebrew.
  Then i created the virtual environment for this project using site packages (hence PyQt4) via ``mkvirtualenv --system-site-packages tumeke_koha``.
  Then i installed every package needed for this project so that it overrided the system site packages via ``pip install -I <package name>``.
