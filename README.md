# NodeJS

## Error: error:0308010C:digital envelope routines::unsupported

Ejecutar:

```bash
## Powershell
$env:NODE_OPTIONS = "--openssl-legacy-provider"

## Windows command
set NODE_OPTIONS=--openssl-legacy-provider

## Unix (Linux, macOS, Git bash, etc.)
export NODE_OPTIONS=--openssl-legacy-provider
```

*Fuente:*

*[node.js - Error message &quot;error:0308010C:digital envelope routines::unsupported&quot; - Stack Overflow](https://stackoverflow.com/questions/69692842/error-message-error0308010cdigital-envelope-routinesunsupported)*
