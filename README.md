# tihello

*Show "Hello World!" on a z80-based TI calc, with minimal code*

This is an exercise in minimalism. Inspired by [KnightOS][knightos], it tries
to manage a simple "no-OS" firmware to send to a TI-84+ that shows
"Hello world!", waits for a key press, then halts.

Most first-hand information comes from [WikiTI][wikiti]

## Prerequisites

* GNU make
* A `kosenv` symlink to a [Simplified KnightOS environment][kosenv]
* [tilp][tilp]

## Status

Complete! Does what it's supposed to do.

## Build

`make run` builds and run the software in the emulator.

`make send` builds and sends a firmware update to the calculator using
[tilp][tilp]

[wikiti]: http://wikiti.brandonw.net/index.php
[knightos]: https://knightos.org/
[kosenv]: https://github.com/hsoft/knightosenv
[tilp]: http://lpg.ticalc.org/prj_tilp/
