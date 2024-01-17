# Babashka tasks

This is babashka tasks extracted for usage on the JVM.

## Usage

Read the entry on babashka tasks in the babashka [book](https://book.babashka.org/#tasks) first.

Instead of `bb.edn` this library uses `tasks.edn` to not conflict with tasks for babashka.

An example `tasks.edn` is included in the root of this repository.

Invoke it with:

``` shell
clj -M babashka.tasks <task> <arguments>
```

e.g.:

```
$ clj -M -m babashka.tasks a
5
```
