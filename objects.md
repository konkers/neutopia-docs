# Objects

## Object table IDs

| Object ID | Args                 | Description             |
| --------- | -------------------- | ----------------------- |
| **`00`**  | YX ID                | Interactive object      |
| **`01`**  | DD                   | Open door               |
| **`02`**  | ??                   | Push block gated door   |
| **`03`**  | DD                   | Enemy gated door        |
| **`05`**  | ??                   | Bombable door           |
| **`06`**  | YX ID                | Push block gated object |
| **`07`**  | YX ID                | Enemy gated object      |
| **`08`**  | YX ID                | Bell gated object       |
| **`09`**  |                      | Dark room               |
| **`0A`**  | ??                   | Boss entrance door      |
| **`0C`**  | YX ??                | Burnable object         |
| **`0D`**  | ?? ??                | Hidden Room             |
| **`81`**  |                      | Falcon boots required   |
| **`9a`**  | YX ?? ?? ?? ??       | NPC                     |
| **`BD`**  | YX ??                | Ouch rope segment       |
| **`BF`**  | YX ??                | Arrow launcher          |
| **`C0`**  | YX ??                | Sword block swords      |
| **`C1`**  | YX ??                | Ghost spawner           |
| **`C6`**  | YX ??                | Fireball spawner        |
| **`DA`**  | ?? ?? ?? ?? ?? ?? ?? | Shop Item               |

## Unknown codes

### Chest prefix or conditional??

`0b, 46, 2a, 04`

- Area 4 room 12 `00, 67, 51, 0b, 46, 2a, 04, 00, 67, 61`
- Area 5 room 01 `00, 38, 50, 0b, 46, 2a, 08, 00, 38, 61`
- Area 6 room 19 `00, 67, 50, 0b, 46, 2a, 10, 00, 67, 61`
- Area 6 room 29 `00, 69, 51, 0b, 49, 2a, 02, 00, 69, 61`

### Chained old man

- Area 4 room 14 `e1, 48, 02, 00, 7d, 41, 56, 2e, 81, 01`
- Area 5 room 14 `e1, 48, 02, 01, 81, 41, 57, 2e, 81, 01`
- Area 6 room 24 `e1, 48, 02, 02, e5, 57, 58, 2e, 81, 01`

The second byte (48) is the location of the old man

### f4

`f4` only appears in area 0c rooms 3e and 3f.

- room 3e: `f4, a7, 2, 3, 40, 43`
- room 3f: `f4, 8, 2, 0, 39, 43`

## To verify

- Is the c0 in area 6 rooms 14 and 1A a sword block?
