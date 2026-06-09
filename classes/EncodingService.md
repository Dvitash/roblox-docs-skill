# EncodingService

**Superclass:** [Instance](Instance.md)

This file defines two methods for common encoding, hashing, and compression functions provided by the EncodingService class.

## Tags
- NotCreatable
- Service
- NotReplicated

## Methods
### `EncodingService:Base64Decode(input: buffer) -> buffer`

### `EncodingService:Base64Encode(input: buffer) -> buffer`

### `EncodingService:CompressBuffer(input: buffer, algorithm: CompressionAlgorithm, compressionLevel: int) -> buffer`

### `EncodingService:ComputeBufferHash(input: buffer, algorithm: HashAlgorithm) -> buffer`

### `EncodingService:ComputeStringHash(input: string, algorithm: HashAlgorithm) -> string`

### `EncodingService:DecompressBuffer(input: buffer, algorithm: CompressionAlgorithm) -> buffer`

### `EncodingService:GetDecompressedBufferSize(input: buffer, algorithm: CompressionAlgorithm) -> int?`
