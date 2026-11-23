# Mission 5 — Numbers and data
## 1. Mission title
Mission 5 — Number systems, Python, and text encoding.

## 2. Task / objective
Convert decimal, binary, and hexadecimal values by hand, verify them with Python, build a converter, and explain character encoding.

## 3. Work completed
Completed manual conversions, Python verification examples, a working `number_converter.py`, and text-encoding notes.

### Manual conversions
| Question | Working | Answer |
|---|---|---|
| Decimal 13 to binary | 13 = 8 + 4 + 1 = `1101₂` | 1101₂ |
| Decimal 25 to binary | 25 = 16 + 8 + 1 = `11001₂` | 11001₂ |
| Binary 1010 to decimal | (1×8)+(0×4)+(1×2)+(0×1) | 10 |
| Binary 1101 to decimal | (1×8)+(1×4)+(0×2)+(1×1) | 13 |
| Hexadecimal A to decimal | A = 10 | 10 |
| Hexadecimal 1F to decimal | (1×16)+(15×1) | 31 |
| Binary 1111 to hexadecimal | Group = F | F |

### Python verification
| Expression | Result | Match? |
|---|---|---|
| `bin(13)` | `0b1101` | Yes |
| `bin(25)` | `0b11001` | Yes |
| `int('1010', 2)` | `10` | Yes |
| `int('1101', 2)` | `13` | Yes |
| `hex(10)` | `0xa` | Yes |
| `int('1F', 16)` | `31` | Yes |
| `hex(int('1111', 2))` | `0xf` | Yes |

### Number converter test values
| Test number | Binary output | Hexadecimal output |
|---|---|---|
| 10 | `1010` | `a` |
| 31 | `11111` | `1f` |
| 255 | `11111111` | `ff` |

`bin()` converts an integer to a binary string beginning with `0b` in Python. `hex()` converts an integer to a hexadecimal string beginning with `0x`. The converter removes those prefixes before display.

### Text encoding
- ASCII decimal code for `A`: 65
- ASCII decimal code for `a`: 97
- An encoding standard gives bytes agreed meanings as characters, so text can be stored and exchanged consistently.
- A character outside basic ASCII is `é` or `😀`. UTF-8 can represent a far wider character set than basic ASCII.

## 4. Commands / tools used
Python interactive mode, `bin()`, `int(value, base)`, `hex()`, `input()`, and `python3 number_converter.py`.

## 5. My understanding
Bases change representation, not the underlying quantity. Encoding standards allow bytes to represent letters and symbols consistently.

## 6. Difficulties faced
No major difficulties.

## 7. How I resolved them
Not applicable.

## 8. Evidence / files
- `number_converter.py`
- Conversion tables in this README

## 9. Commit details
Commit message: **Build number converter and practise data representation**. The work was pushed to GitHub.
