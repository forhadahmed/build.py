 ![build.py | Simple Python build system](http://circuitsoft.net/github/build-py-logo.png)

This is a simple `make`-like build system written in Python (for C/C++ projects). The `build` (Python) script found here should be exported to a project's top-level directory and invoked to start a build.  It looks for a `Makefile.py` to get a list of targets and dependencies.

```
> cp build $project
> cd $project
> ls



> python build
```

