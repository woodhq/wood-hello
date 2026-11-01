# wood-hello

A tiny demo library for the [wood](https://github.com/woodhq) programming language. It
exists to verify `wood add` against a real public repository, so it does almost nothing.

```sh
wood add github@woodhq/wood-hello#v0.1.0
```

```wood
import wood_hello.greeting as greeting

print(greeting.greet("wood"))
```

Licensed under the MIT license.
