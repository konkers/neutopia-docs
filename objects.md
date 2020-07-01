# Objects

## Object table IDs

| Object ID | Args  | Description           |
| --------- | ----- | --------------------- |
| **`00`**  | YX ID | Interactive Object    |
| **`01`**  | DD    | Open door             |
| **`02`**  | ??    | Push block gated door |
| **`03`**  | DD    | Enemy gated door      |
| **`05`**  | ??    | Bombable door         |
| **`0A`**  | ??    | Boss entrace door     |
| **`C0`**  | YX ?? | Sword block swords    |
| **`C6`**  | YX ?? | Fireball spawner      |

## Unknown codes

## Chest prefix or conditional??

`0b, 46, 2a, 04`

- Area 4 Room 12 `00, 67, 51, 0b, 46, 2a, 04, 00, 67, 61`
- Area 5 room 01 `00, 38, 50, 0b, 46, 2a, 08, 00, 38, 61`

First chest room in each crypt?

## Chained old man

- Area 4 room 14 `e1, 48, 02, 00, 7d, 41, 56, 2e, 81, 01`
- Area 5 room 14 `e1, 48, 02, 01, 81, 41, 57, 2e, 81, 01`

The second byte (48) is the location of the old man
