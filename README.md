# pscmd-obfuscation-examples

This repository demonstrates the examples of obfuscated PowerShell Commands (PSCmds) derived by applying the following twelve obfuscation methods and three helper functions to the [original malicious PSCmds](https://github.com/mhtsai1010/pscmd-obfuscation-examples/blob/main/ps_original.ps1) for malware download and execution.

The obfuscated PowerShell Commands (PSCmds) were generated with the framework "[Invoke-Obfuscation](https://github.com/danielbohannon/Invoke-Obfuscation)" created by [Daniel Bohannon](https://www.danielbohannon.com/).

|  Priority  |  Obfuscation method    |  Category             |
|  --------  |  --------------------  |  -------------------  |
|  1         |  Tick                  |  String manipulation  |
|  2         |  Concatenation         |  String manipulation  |
|  3         |  Reversing             |  String manipulation  |
|  4         |  Reordering            |  String manipulation  |
|  5         |  Replacement           |  Helper function      |
|  6         |  Splitting             |  Helper functionn     |
|  7         |  ASCII encoding        |  Encoding scheme      |
|  8         |  Binary encoding       |  Encoding scheme      |
|  9         |  Hexadecimal encoding  |  Encoding scheme      |
|  10        |  Octal encoding        |  Encoding scheme      |
|  11        |  Binary XOR encoding   |  Encoding scheme      |
|  12        |  Compression           |  Compression          |
|  13        |  SecureString encoding |  Encoding scheme      |
|  14        |  Base64 encoding       |  Encoding scheme      |
|  15        |  Randomcase            |  Helper function      |
