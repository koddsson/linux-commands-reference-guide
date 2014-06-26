vim - Vi IMproved, a programmers text editor
============================================
If you made the mistake of opening a file you do not have the correct
permissions to write to in vim. You can save the file without exiting vim with
the following command given you have sudo access.

```
:w ! sudo tee %
```
