Repro for a problem with rules_rust and a toolchain that doesn't ship libgcc_s.so.

Tweaks can be found in `.bazelrc` to exhibit different behavior, build with
```bash
bazelisk build -j 8 //:hello_world
```
