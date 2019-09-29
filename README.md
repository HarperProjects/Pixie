# Pixie
Some crypto implementations in nim

## AES
- An implementation of AES based on the FIPS standard.
- I wouldn't use it for anything important
- Operating mode is not yet defined.
- Don't use ECB mode.

### Using
```nim
import aes
aes.Encrypt(data : CipherBlock, key : Key)
```

### Testing
`nim c -r -d:Test aes.nim`
