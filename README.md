# hterm-umd

**Modifications:**

- removed `lib` and `hterm` from the global scope
- uses universal module definition to expose `lib` and `hterm`
- `lib.ensureRuntimeDependencies_` updated to no longer check on the window for dependencies
