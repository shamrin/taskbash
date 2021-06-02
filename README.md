# taskbash

## Install

Do nothing.

## Write `run` script

```
printf '#!/bin/bash\n\nhello() {\n  echo hello!\n}\n\n "$@"' > run
```

## Use `run` script

```
$ ./run hello
hello!
```
