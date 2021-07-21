# SewML
## An XML standard for garment patterns
## Version 0.0.1

# Purpose

SewML facilitates the exchange of pattern information for sewing machine operators (SMOs), seamstresses, dressmakers and tailors. It's primarily for storing pattern piece shapes/marks but can also be used to exchange other garment data like sewing instructions, seam allowance, bill of materials, etc.

SewML follows the general XML standard. SewML files should use the standard XML header and file extension `.xml`.

# Data formats

## Record sets

These tags define a set of data grouped together.

| Tag | Description |
| - | - |
| `<PATTERNS>` | Encloses a set of one or more `<PATTERN>`s in a file defining a wardrobe/collection |
| `<PIECES>` | Encloses a set of one or more `<PIECE>`s in a `<PATTERN>` |

# Records

These tags define a piece of data relevant to a record set.

| Tag | Description |
| - | - |
| `<PATTERN>` | Defines a pattern, including `<PIECES>` and additional information like `<MATERIALS>` |
| `<PIECE>` | Defines a piece, including (for example) its `<PATH>` and `<ALLOWANCE>` |



