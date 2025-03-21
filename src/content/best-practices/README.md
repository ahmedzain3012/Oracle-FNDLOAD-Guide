# Best Practices


### Use only Oracle-delivered .lct files
Avoid creating or altering loader control files. Use only those provided by Oracle in $FND_TOP/patch/115/import.

### Keep .lct and .ldt in Sync
Verify that the version of the .lct file corresponds to the version used to create the .ldt file. If the versions do not match, upload failures may occur.
