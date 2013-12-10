Here are 2 patches for tree-1.6.0:
04e967a3f4108d50cde3b4b0e89e970a  tree-1.6.0.tgz

"tree-1.6.0-update-man-fr.patch" has to be applied first.

"tree-1.6.0--filesfirst.patch" has to be applied in second
(it also adds the new option in the man pages.)

The first one updates the French man page, which is a translation
of a previous version of the English man page (maybe version 1.4).

The second patch provides an option to print files before directories.
This could be realised in different ways, here we tryed to achieve it with
the fewest changes possible in the source code.

(patches already sent upstream)

