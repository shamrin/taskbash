# taskbash

## Install

Do nothing.

## Write `run` script

```
printf '#!/bin/bash\n\nhello() {\n  echo hello!\n}\n\n"$@"' > run
chmod +x run
```

## Use `run` script

```
$ ./run hello
hello!
```

## Why?

It's like https://github.com/go-task/task, but without YAML and Go. (Nothing wrong about Go as a language, but runner script should have zero dependencies of its own, if possible.)
