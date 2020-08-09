# Shell commands

## ls -- list directory contents

* List filenames only

```shell
ls -l | awk '{print $9}'
```

## Rename

```shell
for file in * ; do mv "$file" ${file/ /_} ; done
```

_Note: works only for one occurence of space_
