# CRC2

CRC2 is a token standard implementation for the Chromia blockchain platform. It provides a robust framework for creating and managing semi-fungible and non-fungible tokens that are compatible with the Chromia Universal Token Protocol (CUTP).

## Features

- CUTP (Chromia Universal Token Protocol) integration (WIP)
- Support for both semi-fungible and non-fungible tokens


## Installation details

```yaml
libs:
  ft4:
    registry: https://gitlab.com/chromaway/ft4-lib.git
    path: rell/src/lib/ft4
    tagOrBranch: v1.0.0r
    rid: x"FA487D75E63B6B58381F8D71E0700E69BEDEAD3A57D1E6C1A9ABB149FAC9E65F"
    insecure: false
  iccf:
    registry: https://gitlab.com/chromaway/core/directory-chain
    path: src/iccf
    tagOrBranch: 1.32.2
    rid: x"1D567580C717B91D2F188A4D786DB1D41501086B155A68303661D25364314A4D"
    insecure: false
  cutp:
    registry: https://bitbucket.org/chromawallet/cutp_1
    path: rell/src/lib/cutp
    tagOrBranch: master
    rid: x"0A384FA10DB1AEAE83065E1E960B2167AEBE45E525E42690A1B8166984ADBE3C"
    insecure: false
  crc2:
    registry: https://github.com/CRC-lib/CRC2
    path: src/lib/crc2
    tagOrBranch: 0.1.0
    rid: x"FA487D75E63B6B58381F8D71E0700E69BEDEAD3A57D1E6C1A9ABB149FAC9E65F"
    insecure: false
```

## Contributing

Contributions are welcome! Please feel free to submit pull requests or create issues for bugs and feature requests.
