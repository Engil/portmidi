This is an OCaml package that provides bindings to the portmidi library.

It uses the excellent ctypes library to generate the C-stubs which should help
minimize the bugspace.

Installing
===

```
opam install portmidi
```

Status
---

Open/read/write works.  Reading sysex messages is untested so far.

Upstream C library
---

The upstream C library is at https://github.com/rbdannenberg/portmidi though
your distribution may ship an older version. In the future, this project
will likely vendor the C library.
