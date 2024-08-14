# Dosbox SVN with patches

* [Dosbox SVN r4483](https://svn.code.sf.net/p/dosbox/code-0/dosbox/trunk)
* [Savestate patches](https://www.vogons.org/viewtopic.php?p=1106424#p1106424)

# Apply patch

patch < patches/save_states_r4481_diff-st-update.patch

# Build

```sh
./autogen.sh
./configure
make
```
