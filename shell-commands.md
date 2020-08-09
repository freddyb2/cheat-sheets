# Shell commands

## ls -- list directory contents

* List filenames only

```shell
ls -l | awk '{print $9}'
```
