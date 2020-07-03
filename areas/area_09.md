# Area 9

## Overview

| | |
|-|-|
| Area data table pointer | 53d91 |
| Room order table pointer | 501e6 |
| Chest table pointer | 504c2 |

## Room Map/Order

|   | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
  |---|---|---|---|---|---|---|---|---|
| 0 | [7d](#room-00) | [7e](#room-01) | [38](#room-02) | [3b](#room-03) | [3d](#room-04) | [41](#room-05) | [7f](#room-06) | [7f](#room-07) |
| 1 | [7f](#room-08) | [7f](#room-09) | [39](#room-0a) | [3c](#room-0b) | [7f](#room-0c) | [42](#room-0d) | [7d](#room-0e) | [22](#room-0f) |
| 2 | [7f](#room-10) | [7f](#room-11) | [00](#room-12) | [7f](#room-13) | [67](#room-14) | [7f](#room-15) | [44](#room-16) | [7f](#room-17) |
| 3 | [7f](#room-18) | [7f](#room-19) | [00](#room-1a) | [7f](#room-1b) | [3f](#room-1c) | [7f](#room-1d) | [45](#room-1e) | [7f](#room-1f) |
| 4 | [7f](#room-20) | [7f](#room-21) | [3a](#room-22) | [7f](#room-23) | [30](#room-24) | [7f](#room-25) | [00](#room-26) | [7f](#room-27) |
| 5 | [7f](#room-28) | [1f](#room-29) | [7d](#room-2a) | [1c](#room-2b) | [7f](#room-2c) | [7f](#room-2d) | [46](#room-2e) | [7f](#room-2f) |
| 6 | [7f](#room-30) | [7f](#room-31) | [7f](#room-32) | [00](#room-33) | [40](#room-34) | [32](#room-35) | [00](#room-36) | [7f](#room-37) |
| 7 | [7f](#room-38) | [7f](#room-39) | [7f](#room-3a) | [7f](#room-3b) | [7f](#room-3c) | [43](#room-3d) | [7f](#room-3e) | [7f](#room-3f) |
## Chests

| index | item id | arg | text | ?? |
|-------|---------|-----|------|----|
| 0 | 09 | 04 | 53 | 66 |
| 1 | 17 | 01 | 97 | 41 |
| 2 | 10 | 01 | 8b | 41 |
| 3 | 11 | 01 | 85 | 41 |
| 4 | 01 | 01 | d4 | 66 |
| 5 | 18 | 01 | 97 | 41 |
| 6 | 0a | 04 | 62 | 79 |
| 7 | 10 | 01 | 8b | 41 |
## Rooms

### Room 00

 ***(0, 0) @ 53e51***

| | |
|-|-|
| warp table ptr | 53e5a |
| enemy table ptr | 53e62 |
| object table ptr | 53e66 |

#### Warp Table

```
[09, 16, 2e, 03, 09, 22, a1, 03]
```

#### Enemy Table

```
[b9, 67, 02]
```

#### Object Table

```
[09, 00, 6e, 26, 00, 61, 44, 0d, ff, ff]
```

- dark room
- object 0x26 @ (14,6)
- object 0x44 @ (1,6)
- hidden room [ff, ff]

### Room 01

 ***(0, 1) @ 53e72***

| | |
|-|-|
| warp table ptr | 53e7b |
| enemy table ptr | 53e83 |
| object table ptr | 53e87 |

#### Warp Table

```
[09, 24, a7, 03, 09, 0d, 2e, 03]
```

#### Enemy Table

```
[b9, 67, 03]
```

#### Object Table

```
[09, 00, a7, 26, 00, 28, 44, 0d, ff, ff]
```

- dark room
- object 0x26 @ (7,10)
- object 0x44 @ (8,2)
- hidden room [ff, ff]

### Room 02

 ***(0, 2) @ 53e93***

| | |
|-|-|
| warp table ptr | 53e9c |
| enemy table ptr | 53e9c |
| object table ptr | 53ea9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b9, 33, 02, b9, 3c, 02, b9, 93, 02, b9, 9c, 02]
```

#### Object Table

```
[09, 03, 01, 03, 02, 00, 66, 2c]
```

- dark room
- enemy gated door 0x01
- enemy gated door 0x02
- object 0x2c @ (6,6)

### Room 03

 ***(0, 3) @ 53eb2***

| | |
|-|-|
| warp table ptr | 53ebb |
| enemy table ptr | 53ebb |
| object table ptr | 53ec8 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b8, 83, 00, b8, 47, 03, b8, 4c, 02, b8, 88, 01]
```

#### Object Table

```
[00, 21, 4b, c6, 21, 00, 00, ae, 4b, c6, ae, 00, 01, 03, 01, 01, 05, 1a]
```

- object 0x4b @ (1,2)
- fireball spawner 0x00 @ (1,2)
- object 0x4b @ (14,10)
- fireball spawner 0x00 @ (14,10)
- open door 0x03
- open door 0x01
- bombable door 0x1a

### Room 04

 ***(0, 4) @ 53edb***

| | |
|-|-|
| warp table ptr | 53ee4 |
| enemy table ptr | 53ee4 |
| object table ptr | 53eeb |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b7, 66, 03, b7, 69, 01]
```

#### Object Table

```
[00, 65, 2d, 00, 6a, 2d, 01, 03, 01, 01, 00, 13, 47, bf, 13, 02, 00, 14, 47, bf, 14, 02, 00, 15, 47, bf, 15, 02, 00, 1a, 47, bf, 1a, 02, 00, 1b, 47, bf, 1b, 02, 00, 1c, 47, bf, 1c, 02, 00, 30, 46, bf, 30, 01, 00, 3f, 48, bf, 3f, 03, 00, 80, 46, bf, 80, 01, 00, 8f, 48, bf, 8f, 03, 00, 47, 45, 00, 48, 45, 00, 54, 45, 00, 56, 45, 00, 59, 45, 00, 5b, 45, 00, 74, 45, 00, 76, 45, 00, 79, 45, 00, 7b, 45, 00, 87, 45, 00, 88, 45]
```

- object 0x2d @ (5,6)
- object 0x2d @ (10,6)
- open door 0x03
- open door 0x01
- object 0x47 @ (3,1)
- arrow launcher 0x02 @ (3,1)
- object 0x47 @ (4,1)
- arrow launcher 0x02 @ (4,1)
- object 0x47 @ (5,1)
- arrow launcher 0x02 @ (5,1)
- object 0x47 @ (10,1)
- arrow launcher 0x02 @ (10,1)
- object 0x47 @ (11,1)
- arrow launcher 0x02 @ (11,1)
- object 0x47 @ (12,1)
- arrow launcher 0x02 @ (12,1)
- object 0x46 @ (0,3)
- arrow launcher 0x01 @ (0,3)
- object 0x48 @ (15,3)
- arrow launcher 0x03 @ (15,3)
- object 0x46 @ (0,8)
- arrow launcher 0x01 @ (0,8)
- object 0x48 @ (15,8)
- arrow launcher 0x03 @ (15,8)
- object 0x45 @ (7,4)
- object 0x45 @ (8,4)
- object 0x45 @ (4,5)
- object 0x45 @ (6,5)
- object 0x45 @ (9,5)
- object 0x45 @ (11,5)
- object 0x45 @ (4,7)
- object 0x45 @ (6,7)
- object 0x45 @ (9,7)
- object 0x45 @ (11,7)
- object 0x45 @ (7,8)
- object 0x45 @ (8,8)

### Room 05

 ***(0, 5) @ 53f56***

| | |
|-|-|
| warp table ptr | 53f5f |
| enemy table ptr | 53f5f |
| object table ptr | 53f6c |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ba, 76, 01, ba, 79, 03, ba, 56, 01, ba, 59, 03]
```

#### Object Table

```
[01, 03, 01, 02]
```

- open door 0x03
- open door 0x02

### Room 06

 ***(0, 6) @ 53f71***

| | |
|-|-|
| warp table ptr | 53f7a |
| enemy table ptr | 53f7a |
| object table ptr | 53f7b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 07

 ***(0, 7) @ 53f7c***

| | |
|-|-|
| warp table ptr | 53f85 |
| enemy table ptr | 53f85 |
| object table ptr | 53f86 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 08

 ***(1, 0) @ 53f87***

| | |
|-|-|
| warp table ptr | 53f90 |
| enemy table ptr | 53f90 |
| object table ptr | 53f91 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 09

 ***(1, 1) @ 53f92***

| | |
|-|-|
| warp table ptr | 53f9b |
| enemy table ptr | 53f9b |
| object table ptr | 53f9c |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 0A

 ***(1, 2) @ 53f9d***

| | |
|-|-|
| warp table ptr | 53fa6 |
| enemy table ptr | 53fa6 |
| object table ptr | 53fb9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ba, 67, 03, ba, 68, 01, b8, 22, 02, b8, 2d, 02, b8, a2, 00, b8, ad, 00]
```

#### Object Table

```
[01, 00, 01, 02]
```

- open door 0x00
- open door 0x02

### Room 0B

 ***(1, 3) @ 53fbe***

| | |
|-|-|
| warp table ptr | 53fc7 |
| enemy table ptr | 53fc7 |
| object table ptr | 53fd4 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b3, 22, 02, b3, 2d, 02, b3, a2, 00, b3, ad, 00]
```

#### Object Table

```
[09, 00, 58, 4c, 05, 18, 00, 85, 2b, 00, 8a, 2b]
```

- dark room
- object 0x4c @ (8,5)
- bombable door 0x18
- object 0x2b @ (5,8)
- object 0x2b @ (10,8)

### Room 0C

 ***(1, 4) @ 53fe1***

| | |
|-|-|
| warp table ptr | 53fea |
| enemy table ptr | 53fea |
| object table ptr | 53feb |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 0D

 ***(1, 5) @ 53fec***

| | |
|-|-|
| warp table ptr | 53ff5 |
| enemy table ptr | 53ff9 |
| object table ptr | 54006 |

#### Warp Table

```
[09, 01, 28, 01]
```

#### Enemy Table

```
[b9, 57, 03, b9, 75, 03, b9, 7a, 01, b9, 98, 01]
```

#### Object Table

```
[09, 00, 7b, 2c, 06, 2e, 24, 02, 00, 05, 19, 0d, 14, 14]
```

- dark room
- object 0x2c @ (11,7)
- push block gated object 0x24 @ (14,2)
- push block gated door 0x00
- bombable door 0x19
- hidden room [14, 14]

### Room 0E

 ***(1, 6) @ 54016***

| | |
|-|-|
| warp table ptr | 5401f |
| enemy table ptr | 5401f |
| object table ptr | 54020 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[05, 1f, 05, 1d]
```

- bombable door 0x1f
- bombable door 0x1d

### Room 0F

 ***(1, 7) @ 54025***

| | |
|-|-|
| warp table ptr | 5402e |
| enemy table ptr | 5402e |
| object table ptr | 54035 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b4, 5b, 02, b4, 7b, 02]
```

#### Object Table

```
[09, 00, 6c, 50, 0b, 46, 2a, 80, 00, 6c, 61, 05, 1b]
```

- dark room
- object 0x50 @ (12,6)
- unknown object 0x0b [46, 2a, 80]
- object 0x61 @ (12,6)
- bombable door 0x1b

### Room 10

 ***(2, 0) @ 54043***

| | |
|-|-|
| warp table ptr | 5404c |
| enemy table ptr | 5404c |
| object table ptr | 5404d |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 11

 ***(2, 1) @ 5404e***

| | |
|-|-|
| warp table ptr | 54057 |
| enemy table ptr | 54057 |
| object table ptr | 54058 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 12

 ***(2, 2) @ 54059***

| | |
|-|-|
| warp table ptr | 54062 |
| enemy table ptr | 54062 |
| object table ptr | 54075 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b4, 73, 02, b4, 75, 02, b4, 67, 02, b4, 68, 02, b4, 7a, 02, b4, 7c, 02]
```

#### Object Table

```
[02, 00, 02, 02, 00, 63, 2a, 00, 6c, 2c]
```

- push block gated door 0x00
- push block gated door 0x02
- object 0x2a @ (3,6)
- object 0x2c @ (12,6)

### Room 13

 ***(2, 3) @ 54080***

| | |
|-|-|
| warp table ptr | 54089 |
| enemy table ptr | 54089 |
| object table ptr | 5408a |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 14

 ***(2, 4) @ 5408b***

| | |
|-|-|
| warp table ptr | 54094 |
| enemy table ptr | 54094 |
| object table ptr | 5409b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b8, 51, 02, b8, 5e, 02]
```

#### Object Table

```
[09, 00, 64, 4b, c6, 64, 00, 00, 6b, 4b, c6, 6b, 00, 00, 27, 4d, 01, 02]
```

- dark room
- object 0x4b @ (4,6)
- fireball spawner 0x00 @ (4,6)
- object 0x4b @ (11,6)
- fireball spawner 0x00 @ (11,6)
- object 0x4d @ (7,2)
- open door 0x02

### Room 15

 ***(2, 5) @ 540ae***

| | |
|-|-|
| warp table ptr | 540b7 |
| enemy table ptr | 540b7 |
| object table ptr | 540b8 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 16

 ***(2, 6) @ 540b9***

| | |
|-|-|
| warp table ptr | 540c2 |
| enemy table ptr | 540c6 |
| object table ptr | 540d3 |

#### Warp Table

```
[09, 00, 6e, 01]
```

#### Enemy Table

```
[b7, 36, 03, b7, 39, 01, b7, 66, 03, b7, 69, 01]
```

#### Object Table

```
[09, 01, 02, 00, 2e, 24, 0d, 14, 14]
```

- dark room
- open door 0x02
- object 0x24 @ (14,2)
- hidden room [14, 14]

### Room 17

 ***(2, 7) @ 540de***

| | |
|-|-|
| warp table ptr | 540e7 |
| enemy table ptr | 540e7 |
| object table ptr | 540e8 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 18

 ***(3, 0) @ 540e9***

| | |
|-|-|
| warp table ptr | 540f2 |
| enemy table ptr | 540f2 |
| object table ptr | 540f3 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 19

 ***(3, 1) @ 540f4***

| | |
|-|-|
| warp table ptr | 540fd |
| enemy table ptr | 540fd |
| object table ptr | 540fe |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 1A

 ***(3, 2) @ 540ff***

| | |
|-|-|
| warp table ptr | 54108 |
| enemy table ptr | 54108 |
| object table ptr | 5410f |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b5, 55, 02, b5, 5a, 02]
```

#### Object Table

```
[bd, 65, 00, bd, 65, 00, bd, 65, 00, bd, 65, 00, bd, 65, 00, bd, 65, 00, bd, 6a, 00, bd, 6a, 00, bd, 6a, 00, bd, 6a, 00, bd, 6a, 00, bd, 6a, 00, 01, 00, 01, 02]
```

- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (5,6)
- ouch rope segment 0x00 @ (10,6)
- ouch rope segment 0x00 @ (10,6)
- ouch rope segment 0x00 @ (10,6)
- ouch rope segment 0x00 @ (10,6)
- ouch rope segment 0x00 @ (10,6)
- ouch rope segment 0x00 @ (10,6)
- open door 0x00
- open door 0x02

### Room 1B

 ***(3, 3) @ 54138***

| | |
|-|-|
| warp table ptr | 54141 |
| enemy table ptr | 54141 |
| object table ptr | 54142 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 1C

 ***(3, 4) @ 54143***

| | |
|-|-|
| warp table ptr | 5414c |
| enemy table ptr | 5414c |
| object table ptr | 54159 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[e8, 57, 02, e9, 57, 02, e9, 57, 02, e9, 57, 02]
```

#### Object Table

```
[03, 60, 03, 62]
```

- enemy gated door 0x60
- enemy gated door 0x62

### Room 1D

 ***(3, 5) @ 5415e***

| | |
|-|-|
| warp table ptr | 54167 |
| enemy table ptr | 54167 |
| object table ptr | 54168 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 1E

 ***(3, 6) @ 54169***

| | |
|-|-|
| warp table ptr | 54172 |
| enemy table ptr | 54172 |
| object table ptr | 5418b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b5, 65, 02, b5, 65, 00, b5, 65, 01, b5, 65, 03, b5, 6a, 02, b5, 6a, 00, b5, 6a, 01, b5, 6a, 03]
```

#### Object Table

```
[09, 00, 68, 4e, 01, 00, 01, 02]
```

- dark room
- object 0x4e @ (8,6)
- open door 0x00
- open door 0x02

### Room 1F

 ***(3, 7) @ 54194***

| | |
|-|-|
| warp table ptr | 5419d |
| enemy table ptr | 5419d |
| object table ptr | 5419e |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 20

 ***(4, 0) @ 5419f***

| | |
|-|-|
| warp table ptr | 541a8 |
| enemy table ptr | 541a8 |
| object table ptr | 541a9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 21

 ***(4, 1) @ 541aa***

| | |
|-|-|
| warp table ptr | 541b3 |
| enemy table ptr | 541b3 |
| object table ptr | 541b4 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 22

 ***(4, 2) @ 541b5***

| | |
|-|-|
| warp table ptr | 541be |
| enemy table ptr | 541c2 |
| object table ptr | 541d5 |

#### Warp Table

```
[09, 00, 61, 01]
```

#### Enemy Table

```
[b6, 73, 02, b6, 75, 02, b6, 67, 02, b6, 68, 02, b6, 7a, 02, b6, 7c, 02]
```

#### Object Table

```
[09, 00, a1, 24, 01, 00, 0d, 14, 14]
```

- dark room
- object 0x24 @ (1,10)
- open door 0x00
- hidden room [14, 14]

### Room 23

 ***(4, 3) @ 541e0***

| | |
|-|-|
| warp table ptr | 541e9 |
| enemy table ptr | 541e9 |
| object table ptr | 541ea |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 24

 ***(4, 4) @ 541eb***

| | |
|-|-|
| warp table ptr | 541f4 |
| enemy table ptr | 541f8 |
| object table ptr | 541ff |

#### Warp Table

```
[09, 01, a7, 01]
```

#### Enemy Table

```
[b3, 53, 01, b3, 5c, 03]
```

#### Object Table

```
[09, 00, 14, 4a, c6, 14, 00, 00, 1b, 4a, c6, 1b, 00, 0a, 68, 00, a7, 24, 0d, 14, 14]
```

- dark room
- object 0x4a @ (4,1)
- fireball spawner 0x00 @ (4,1)
- object 0x4a @ (11,1)
- fireball spawner 0x00 @ (11,1)
- boss door 0x68
- object 0x24 @ (7,10)
- hidden room [14, 14]

### Room 25

 ***(4, 5) @ 54216***

| | |
|-|-|
| warp table ptr | 5421f |
| enemy table ptr | 5421f |
| object table ptr | 54220 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 26

 ***(4, 6) @ 54221***

| | |
|-|-|
| warp table ptr | 5422a |
| enemy table ptr | 5422a |
| object table ptr | 5423a |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b9, 67, 02, b3, 33, 02, b3, 3c, 02, b3, 93, 02, b3, 9c, 02]
```

#### Object Table

```
[09, 03, 08, 01, 02, 00, 44, 2a, 00, 4b, 2a, 00, 84, 2a, 00, 8b, 2a]
```

- dark room
- enemy gated door 0x08
- open door 0x02
- object 0x2a @ (4,4)
- object 0x2a @ (11,4)
- object 0x2a @ (4,8)
- object 0x2a @ (11,8)

### Room 27

 ***(4, 7) @ 5424c***

| | |
|-|-|
| warp table ptr | 54255 |
| enemy table ptr | 54255 |
| object table ptr | 54256 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 28

 ***(5, 0) @ 54257***

| | |
|-|-|
| warp table ptr | 54260 |
| enemy table ptr | 54260 |
| object table ptr | 54261 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 29

 ***(5, 1) @ 54262***

| | |
|-|-|
| warp table ptr | 5426b |
| enemy table ptr | 5426b |
| object table ptr | 54278 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b8, 64, 02, b8, 64, 02, b8, 6b, 02, b8, 6b, 02]
```

#### Object Table

```
[09, 05, 19]
```

- dark room
- bombable door 0x19

### Room 2A

 ***(5, 2) @ 5427c***

| | |
|-|-|
| warp table ptr | 54285 |
| enemy table ptr | 54285 |
| object table ptr | 54286 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[05, 1f, 05, 1d]
```

- bombable door 0x1f
- bombable door 0x1d

### Room 2B

 ***(5, 3) @ 5428b***

| | |
|-|-|
| warp table ptr | 54294 |
| enemy table ptr | 54294 |
| object table ptr | 542a4 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b4, 67, 02, b9, 33, 02, b9, 3c, 02, b9, 93, 02, b9, 9c, 02]
```

#### Object Table

```
[09, 00, 68, 4f, 05, 1a, 00, 56, 2b, 05, 1b]
```

- dark room
- object 0x4f @ (8,6)
- bombable door 0x1a
- object 0x2b @ (6,5)
- bombable door 0x1b

### Room 2C

 ***(5, 4) @ 542b0***

| | |
|-|-|
| warp table ptr | 542b9 |
| enemy table ptr | 542b9 |
| object table ptr | 542ba |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 2D

 ***(5, 5) @ 542bb***

| | |
|-|-|
| warp table ptr | 542c4 |
| enemy table ptr | 542c4 |
| object table ptr | 542c5 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[e1, 48, 02, 05, 6f, 66, 5b, 2e, 81, 01, 01, 02, 05, 19]
```

- unknown object 0xe1 [48, 2, 5, 6f, 66, 5b, 2e, 81, 1]
- open door 0x02
- bombable door 0x19

### Room 2E

 ***(5, 6) @ 542d4***

| | |
|-|-|
| warp table ptr | 542dd |
| enemy table ptr | 542dd |
| object table ptr | 542f0 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b8, 57, 02, b8, 78, 02, ba, 43, 02, ba, 4c, 02, b5, 23, 01, b5, 2c, 03]
```

#### Object Table

```
[09, 01, 00, 01, 02, 05, 1b]
```

- dark room
- open door 0x00
- open door 0x02
- bombable door 0x1b

### Room 2F

 ***(5, 7) @ 542f8***

| | |
|-|-|
| warp table ptr | 54301 |
| enemy table ptr | 54301 |
| object table ptr | 54302 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 30

 ***(6, 0) @ 54303***

| | |
|-|-|
| warp table ptr | 5430c |
| enemy table ptr | 5430c |
| object table ptr | 5430d |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 31

 ***(6, 1) @ 5430e***

| | |
|-|-|
| warp table ptr | 54317 |
| enemy table ptr | 54317 |
| object table ptr | 54318 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 32

 ***(6, 2) @ 54319***

| | |
|-|-|
| warp table ptr | 54322 |
| enemy table ptr | 54322 |
| object table ptr | 54323 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 33

 ***(6, 3) @ 54324***

| | |
|-|-|
| warp table ptr | 5432d |
| enemy table ptr | 5432d |
| object table ptr | 5433d |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b7, 67, 02, b7, 33, 02, b7, 3c, 02, b7, 93, 02, b7, 9c, 02]
```

#### Object Table

```
[09, 02, 01, 05, 18, 00, 64, 2c, 00, 6b, 2a]
```

- dark room
- push block gated door 0x01
- bombable door 0x18
- object 0x2c @ (4,6)
- object 0x2a @ (11,6)

### Room 34

 ***(6, 4) @ 54349***

| | |
|-|-|
| warp table ptr | 54352 |
| enemy table ptr | 54352 |
| object table ptr | 54365 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ba, 67, 03, ba, 68, 01, b8, 22, 02, b8, 2d, 02, b8, a2, 00, b8, ad, 00]
```

#### Object Table

```
[09, 01, 03, 01, 01]
```

- dark room
- open door 0x03
- open door 0x01

### Room 35

 ***(6, 5) @ 5436b***

| | |
|-|-|
| warp table ptr | 54374 |
| enemy table ptr | 54374 |
| object table ptr | 54378 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b3, 57, 02]
```

#### Object Table

```
[09, 03, 00, 03, 02, 03, 03, 03, 01]
```

- dark room
- enemy gated door 0x00
- enemy gated door 0x02
- enemy gated door 0x03
- enemy gated door 0x01

### Room 36

 ***(6, 6) @ 54382***

| | |
|-|-|
| warp table ptr | 5438b |
| enemy table ptr | 5438b |
| object table ptr | 54398 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b6, 22, 02, b6, 2d, 02, b6, a2, 02, b6, ad, 02]
```

#### Object Table

```
[09, 01, 00, 01, 03, 00, 33, 2a, 00, 34, 2d, c0, 34, 00, 00, 3b, 2d, c0, 3b, 00, 00, 3c, 2a, 00, 47, 2a, 00, 48, 2a, 00, 65, 2d, c0, 65, 00, 00, 6a, 2d, c0, 6a, 00, 00, 87, 2a, 00, 88, 2a, 00, 93, 2a, 00, 94, 2d, c0, 94, 00, 00, 9b, 2d, c0, 9b, 00, 00, 9c, 2a]
```

- dark room
- open door 0x00
- open door 0x03
- object 0x2a @ (3,3)
- object 0x2d @ (4,3)
- swords 0x00 @ (4,3)
- object 0x2d @ (11,3)
- swords 0x00 @ (11,3)
- object 0x2a @ (12,3)
- object 0x2a @ (7,4)
- object 0x2a @ (8,4)
- object 0x2d @ (5,6)
- swords 0x00 @ (5,6)
- object 0x2d @ (10,6)
- swords 0x00 @ (10,6)
- object 0x2a @ (7,8)
- object 0x2a @ (8,8)
- object 0x2a @ (3,9)
- object 0x2d @ (4,9)
- swords 0x00 @ (4,9)
- object 0x2d @ (11,9)
- swords 0x00 @ (11,9)
- object 0x2a @ (12,9)

### Room 37

 ***(6, 7) @ 543da***

| | |
|-|-|
| warp table ptr | 543e3 |
| enemy table ptr | 543e3 |
| object table ptr | 543e4 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 38

 ***(7, 0) @ 543e5***

| | |
|-|-|
| warp table ptr | 543ee |
| enemy table ptr | 543ee |
| object table ptr | 543ef |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 39

 ***(7, 1) @ 543f0***

| | |
|-|-|
| warp table ptr | 543f9 |
| enemy table ptr | 543f9 |
| object table ptr | 543fa |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 3A

 ***(7, 2) @ 543fb***

| | |
|-|-|
| warp table ptr | 54404 |
| enemy table ptr | 54404 |
| object table ptr | 54405 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 3B

 ***(7, 3) @ 54406***

| | |
|-|-|
| warp table ptr | 5440f |
| enemy table ptr | 5440f |
| object table ptr | 54410 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 3C

 ***(7, 4) @ 54411***

| | |
|-|-|
| warp table ptr | 5441a |
| enemy table ptr | 5441a |
| object table ptr | 5441b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 3D

 ***(7, 5) @ 5441c***

| | |
|-|-|
| warp table ptr | 54425 |
| enemy table ptr | 54429 |
| object table ptr | 54433 |

#### Warp Table

```
[02, 00, 67, 20]
```

#### Enemy Table

```
[b5, 5a, 02, b5, 53, 00, b5, 74, 00]
```

#### Object Table

```
[00, 9d, 26, 01, 00]
```

- object 0x26 @ (13,9)
- open door 0x00

### Room 3E

 ***(7, 6) @ 54439***

| | |
|-|-|
| warp table ptr | 54442 |
| enemy table ptr | 54442 |
| object table ptr | 54443 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 3F

 ***(7, 7) @ 54444***

| | |
|-|-|
| warp table ptr | 5444d |
| enemy table ptr | 5444d |
| object table ptr | 5444e |

#### Warp Table

```
[]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


