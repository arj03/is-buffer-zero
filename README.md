# is-buffer-zero

A fork of mafintosh [is-zero-buffer] that performs better when buffer
is not empty.

## benchmark.js:

```
Benchmarking 10.000 0 buffers:
is-buffer-zero: 42 ms
is-zero-buffer: 38 ms
is zero using loop: 10285 ms

Benchmarking 100.000 random buffers:
is-buffer-zero: 25 ms
is-zero-buffer: 71 ms
is zero using loop: 26 ms
```

## API

### `isZero(buffer)`

Returns true if a buffer only contains `0`s, false otherwise.

## License

MIT

[is-zero-buffer]: https://github.com/mafintosh/is-zero-buffer
