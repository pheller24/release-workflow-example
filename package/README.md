It is expected that this directory is mirrored to another repository.

Lets try if that works.

Add some line..

Finish................................

```
/home/runner/work/example/example/bin/splitsh-lite --prefix=package --origin=tags/44.4.5
4 commits created, 62 commits traversed, in 16ms
65e5cdcd6b617526a3ca2921f821c3d79dccbe43
hash from commit hash origin 65e5cdcd6b617526a3ca2921f821c3d79dccbe43
/usr/bin/git clone git@github.com:dsentker24/repo.git .
Cloning into '.'...
/usr/bin/git tag --points-at 65e5cdcd6b617526a3ca2921f821c3d79dccbe43
65e5cdcd6b617526a3ca2921f821c3d79dccbe43 points-at
/usr/bin/git tag -a 44.4.5 65e5cdcd6b617526a3ca2921f821c3d79dccbe43 -m "Tag: 44.4.5"
fatal: bad object type.
Error: Error: The process '/usr/bin/git' failed with exit code 128
```