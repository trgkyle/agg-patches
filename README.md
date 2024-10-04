### Create patch file by version commit

Android Patches

diff --git a/xxx.x b/xxx.x

diff -u file_original.x file_modified.x > file_original.patch

### To get parent

git rev-parse --show-toplevel

### Get Patch file

git format-patch -1 HEAD
