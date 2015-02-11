unsorted, unfinished, mostly undocumented collection of patches i use to make music.
pretty messy, and made to be as selfcontained and copy/paste-able as possible.
work in progress, and patches may change, become obsolete or disapear with future
updates. mostly pd vanilla, but sometimes externals are needed (moog~, playlist for example)

since i got tired of renaming delays and tables, most instrumentes are not longer completely self-contained,
but rely on abstractions, whenever this alows to copy/paste a (sub)patch. the required abstractions are
contained in the instruments folder, prefixed "abs_" and should be copied to a folder within pds search path
(you can drop them simply into "extras", if you dont mind the mess), or along with the patch, or you could add the
instruments folder to the pd path.

added a little documentation, fixed some issues and probably introduced quite a few new ones...
threw out all/most fexpr~ filters, replaced with more efficient cpole/zero.
fixed a few more bugs.
now with overview.txt


2/2014 martin brinkmann
