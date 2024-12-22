# watch

This is a little `bash` script to watch a path with `fswatch`
and then run a command whenever anything changes.

Example:

```
watch /tmp/src/wiki "tree -a -C -F -t ."
```

Haven't tested this on other systems besides MacOS.

This script depends on `fswatch`. If you don't have that, install
it with your package manager, such as Homebrew.
