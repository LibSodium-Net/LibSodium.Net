# LibSodium.Net


[![Build and Test](https://github.com/LibSodium-Net/LibSodium.Net/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/jesuslpm/Na.Core/actions/workflows/build-and-test.yml)


LibSodium.NET is a library that provides bindings for libsodium. It is designed to eventually support all of libsodium’s features while offering a modern and efficient approach to cryptographic operations.

## Modern and Efficient

- Utilizes `Span<T>` instead of arrays for enhanced performance.
- Supports Ahead-of-Time (AOT) compilation by leveraging `LibraryImport` rather than `DllImport`.

## Implemented Features

### Helpers

- Constant-time equality testing
- Hexadecimal encoding and decoding.
- Base64 encoding and decoding
- Operations for arbitrary-length unsigned numbers.
- Testing for all-zero values.

### Pading

Pad and unpad data using the ISO/IEC 7816-4 padding algorithm

### Secure Memory

- Zeroing memory
- Locking memory
- Guarded heap allocations.

## Generating random data

- Random `UInt32` , including uniform with upper bound.
- Random buffer generation, including deterministic option.
- Closing and stirring the random generator

## Secret-Key Cryptography

- Authenticatedd encryption (SecretBox)

## Additional Features

Coming soon




