# runny

A github repo example which aims to make programming and testing in `c` berable

# Intro

You must follow this project structure to make everything work:

- `cmd` folder containing the executables' sources (kek and main for this demo)
- `pkg` folder containing the libraries used in the executables
- ⚠️ don't ever include directly `.c` files


### tests

- ⚠️ write the tests inside the `pkg` folder 
- ⚠️ named them `***_test.c`
- ⚠️ name the test function `int Test***()`

> the tests are launched using `pthread` so make sure they don't overlap or use common resources`

## Commands

```
make build
make test

make run kek
make run main

make run clean
```

they behave exactly as you expected coming from `go`

you can skip the build command, and everything works just fine
