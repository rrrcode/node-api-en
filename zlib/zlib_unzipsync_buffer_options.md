<!-- YAML
added: v0.11.12
changes:
  - version: v8.0.0
    pr-url: https://github.com/nodejs/node/pull/12223
    description: The `buffer` parameter can be any TypedArray or DataView now.
  - version: v8.0.0
    pr-url: https://github.com/nodejs/node/pull/12001
    description: The `buffer` parameter can be an Uint8Array now.
-->

- `buffer` {Buffer|TypedArray|DataView|string}

Decompress a chunk of data with [Unzip][].

[`.flush()`]: #zlib_zlib_flush_kind_callback
[`Accept-Encoding`]: https://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.3
[`Buffer`]: buffer.html#buffer_class_buffer
[`Content-Encoding`]: https://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.11
[`DataView`]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView
[`TypedArray`]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/TypedArray
[DeflateRaw]: #zlib_class_zlib_deflateraw
[Deflate]: #zlib_class_zlib_deflate
[Gunzip]: #zlib_class_zlib_gunzip
[Gzip]: #zlib_class_zlib_gzip
[InflateRaw]: #zlib_class_zlib_inflateraw
[Inflate]: #zlib_class_zlib_inflate
[Memory Usage Tuning]: #zlib_memory_usage_tuning
[Unzip]: #zlib_class_zlib_unzip
[options]: #zlib_class_options
[zlib documentation]: http://zlib.net/manual.html#Constants
