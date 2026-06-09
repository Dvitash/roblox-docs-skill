# Enum.HashAlgorithm

A Cryptographic hash function to use in `Class.EncodingService` methods.

## Items

| Name | Value | Tags | Summary |
| --- | --- | --- | --- |
| `Blake2b` | 0 |  | Used to compute a 256-bit (32-byte) hash digest using the [BLAKE2b](https://en.wikipedia.org/wiki/BLAKE2) algorithm. |
| `Blake3` | 1 |  | Used to compute a 256-bit (32-byte) hash digest using the [BLAKE3](https://en.wikipedia.org/wiki/BLAKE3) algorithm. |
| `Md5` | 2 |  | Used to compute a 128-bit (16-byte) hash digest using the [MD5](https://en.wikipedia.org/wiki/MD5) algorithm. |
| `Sha1` | 3 |  | Used to compute a 160-bit (20-byte) hash digest using the [SHA-1](https://en.wikipedia.org/wiki/SHA-1) algorithm. |
| `Sha256` | 4 |  | Used to compute a 256-bit (32-byte) hash digest using the [SHA256](https://en.wikipedia.org/wiki/SHA-2) algorithm. |

**Valid values:** `Enum.HashAlgorithm.Blake2b`, `Enum.HashAlgorithm.Blake3`, `Enum.HashAlgorithm.Md5`, `Enum.HashAlgorithm.Sha1`, `Enum.HashAlgorithm.Sha256`
