# Area F

## Overview

| | |
|-|-|
| Area data table pointer | 564ec |
| Room order table pointer | 50366 |
| Chest table pointer | 50536 |

## Room Map/Order

|   | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
  |---|---|---|---|---|---|---|---|---|
| 0 | [07](#room-00) | [05](#room-01) | [07](#room-02) | [07](#room-03) | [05](#room-04) | [03](#room-05) | [06](#room-06) | [04](#room-07) |
| 1 | [0d](#room-08) | [07](#room-09) | [05](#room-0a) | [0d](#room-0b) | [03](#room-0c) | [03](#room-0d) | [08](#room-0e) | [0d](#room-0f) |
| 2 | [04](#room-10) | [05](#room-11) | [0d](#room-12) | [06](#room-13) | [05](#room-14) | [0d](#room-15) | [05](#room-16) | [0d](#room-17) |
| 3 | [05](#room-18) | [03](#room-19) | [06](#room-1a) | [06](#room-1b) | [03](#room-1c) | [06](#room-1d) | [03](#room-1e) | [06](#room-1f) |
| 4 | [06](#room-20) | [07](#room-21) | [07](#room-22) | [05](#room-23) | [06](#room-24) | [07](#room-25) | [06](#room-26) | [0d](#room-27) |
| 5 | [07](#room-28) | [05](#room-29) | [0d](#room-2a) | [0d](#room-2b) | [0d](#room-2c) | [02](#room-2d) | [07](#room-2e) | [02](#room-2f) |
| 6 | [02](#room-30) | [02](#room-31) | [02](#room-32) | [02](#room-33) | [02](#room-34) | [02](#room-35) | [02](#room-36) | [02](#room-37) |
| 7 | [02](#room-38) | [02](#room-39) | [02](#room-3a) | [02](#room-3b) | [02](#room-3c) | [02](#room-3d) | [02](#room-3e) | [02](#room-3f) |
## Chests

| index | item id | arg | text | ?? |
|-------|---------|-----|------|----|
| 0 | 08 | 04 | 68 | 79 |
| 1 | 00 | 14 | 7b | 7a |
| 2 | 00 | 08 | 04 | 7a |
| 3 | 01 | 01 | 16 | 7a |
| 4 | 01 | 01 | 34 | 7a |
| 5 | 01 | 02 | 69 | 7a |
| 6 | 48 | 0e | 46 | 48 |
| 7 | 26 | 46 | 48 | 38 |
## Rooms

### Room 00

 ***(0, 0) @ 565ac***

| | |
|-|-|
| warp table ptr | 565b5 |
| enemy table ptr | 565b9 |
| object table ptr | 565ba |

#### Warp Table

```
[03, 00, 34, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0f, 65, 78]
```

- npc [48, 2, f, 65, 78]

### Room 01

 ***(0, 1) @ 565c1***

| | |
|-|-|
| warp table ptr | 565ca |
| enemy table ptr | 565ce |
| object table ptr | 565cf |

#### Warp Table

```
[03, 02, 78, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 09, 69, 78]
```

- npc [48, 2, 9, 69, 78]

### Room 02

 ***(0, 2) @ 565d6***

| | |
|-|-|
| warp table ptr | 565df |
| enemy table ptr | 565e3 |
| object table ptr | 565e4 |

#### Warp Table

```
[03, 04, 33, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 01, 6d, 78]
```

- npc [48, 2, 1, 6d, 78]

### Room 03

 ***(0, 3) @ 565eb***

| | |
|-|-|
| warp table ptr | 565f4 |
| enemy table ptr | 565f8 |
| object table ptr | 565f9 |

#### Warp Table

```
[03, 05, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 48, 4e, 0b, 48, 2a, 08, 00, 48, 61]
```

- dark room
- object 0x4e @ (8,4)
- unknown object 0x0b [48, 2a, 8]
- object 0x61 @ (8,4)

### Room 04

 ***(0, 4) @ 56605***

| | |
|-|-|
| warp table ptr | 5660e |
| enemy table ptr | 56612 |
| object table ptr | 56613 |

#### Warp Table

```
[03, 06, 3a, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 48, 4f, 0b, 48, 2a, 10, 00, 48, 61]
```

- dark room
- object 0x4f @ (8,4)
- unknown object 0x0b [48, 2a, 10]
- object 0x61 @ (8,4)

### Room 05

 ***(0, 5) @ 5661f***

| | |
|-|-|
| warp table ptr | 56628 |
| enemy table ptr | 5662c |
| object table ptr | 5662d |

#### Warp Table

```
[03, 07, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 06, 75, 78, da, 46, 00, 00, 05, 00, 01, 01, da, 4a, 00, 00, 05, 00, 01, 01]
```

- npc [48, 2, 6, 75, 78]
- shop item [46, 0, 0, 5, 0, 1, 1]
- shop item [4a, 0, 0, 5, 0, 1, 1]

### Room 06

 ***(0, 6) @ 56644***

| | |
|-|-|
| warp table ptr | 5664d |
| enemy table ptr | 56651 |
| object table ptr | 56652 |

#### Warp Table

```
[03, 0b, 3c, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 04, 79, 78]
```

- npc [48, 2, 4, 79, 78]

### Room 07

 ***(0, 7) @ 56659***

| | |
|-|-|
| warp table ptr | 56662 |
| enemy table ptr | 56666 |
| object table ptr | 56667 |

#### Warp Table

```
[03, 0d, 8a, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0d, d6, 78]
```

- npc [48, 2, d, d6, 78]

### Room 08

 ***(1, 0) @ 5666e***

| | |
|-|-|
| warp table ptr | 56677 |
| enemy table ptr | 5667b |
| object table ptr | 5667c |

#### Warp Table

```
[03, 0f, 76, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 08, 28, 7a]
```

- npc [48, 2, 8, 28, 7a]

### Room 09

 ***(1, 1) @ 56683***

| | |
|-|-|
| warp table ptr | 5668c |
| enemy table ptr | 56690 |
| object table ptr | 56691 |

#### Warp Table

```
[03, 10, 37, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 08, 95, 78]
```

- npc [48, 2, 8, 95, 78]

### Room 0A

 ***(1, 2) @ 56698***

| | |
|-|-|
| warp table ptr | 566a1 |
| enemy table ptr | 566a5 |
| object table ptr | 566a6 |

#### Warp Table

```
[03, 11, 36, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 00, 99, 78]
```

- npc [48, 2, 0, 99, 78]

### Room 0B

 ***(1, 3) @ 566ad***

| | |
|-|-|
| warp table ptr | 566b6 |
| enemy table ptr | 566b6 |
| object table ptr | 566b7 |

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


### Room 0C

 ***(1, 4) @ 566b8***

| | |
|-|-|
| warp table ptr | 566c1 |
| enemy table ptr | 566c5 |
| object table ptr | 566c6 |

#### Warp Table

```
[03, 13, 36, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 07, 71, 78, da, 46, 00, 00, 04, 00, 00, 01, da, 4a, 00, 00, 04, 00, 00, 01]
```

- npc [48, 2, 7, 71, 78]
- shop item [46, 0, 0, 4, 0, 0, 1]
- shop item [4a, 0, 0, 4, 0, 0, 1]

### Room 0D

 ***(1, 5) @ 566dd***

| | |
|-|-|
| warp table ptr | 566e6 |
| enemy table ptr | 566ea |
| object table ptr | 566eb |

#### Warp Table

```
[03, 14, 39, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 09, 75, 78, da, 46, 00, 00, 05, 00, 01, 01, da, 4a, 00, 00, 05, 00, 01, 01]
```

- npc [48, 2, 9, 75, 78]
- shop item [46, 0, 0, 5, 0, 1, 1]
- shop item [4a, 0, 0, 5, 0, 1, 1]

### Room 0E

 ***(1, 6) @ 56702***

| | |
|-|-|
| warp table ptr | 5670b |
| enemy table ptr | 5670f |
| object table ptr | 56710 |

#### Warp Table

```
[03, 16, 43, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 03, 9d, 78]
```

- npc [48, 2, 3, 9d, 78]

### Room 0F

 ***(1, 7) @ 56717***

| | |
|-|-|
| warp table ptr | 56720 |
| enemy table ptr | 56724 |
| object table ptr | 56725 |

#### Warp Table

```
[03, 19, 38, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 05, 30, 7a]
```

- npc [48, 2, 5, 30, 7a]

### Room 10

 ***(2, 0) @ 5672c***

| | |
|-|-|
| warp table ptr | 56735 |
| enemy table ptr | 56739 |
| object table ptr | 5673a |

#### Warp Table

```
[03, 1b, 33, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0e, d6, 78]
```

- npc [48, 2, e, d6, 78]

### Room 11

 ***(2, 1) @ 56741***

| | |
|-|-|
| warp table ptr | 5674a |
| enemy table ptr | 5674e |
| object table ptr | 5674f |

#### Warp Table

```
[03, 1c, 3c, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 08, db, 78]
```

- npc [48, 2, 8, db, 78]

### Room 12

 ***(2, 2) @ 56756***

| | |
|-|-|
| warp table ptr | 5675f |
| enemy table ptr | 56763 |
| object table ptr | 56764 |

#### Warp Table

```
[03, 1d, 3c, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 48, 50, 0b, 48, 2a, 20, 00, 48, 61]
```

- dark room
- object 0x50 @ (8,4)
- unknown object 0x0b [48, 2a, 20]
- object 0x61 @ (8,4)

### Room 13

 ***(2, 3) @ 56770***

| | |
|-|-|
| warp table ptr | 56779 |
| enemy table ptr | 56781 |
| object table ptr | 56782 |

#### Warp Table

```
[03, 1f, 35, 24, 03, 09, 77, 30]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 04, 44, 7a, 08, 46, 25]
```

- npc [48, 2, 4, 44, 7a]
- bell gated object 0x25 @ (6,4)

### Room 14

 ***(2, 4) @ 5678c***

| | |
|-|-|
| warp table ptr | 56795 |
| enemy table ptr | 567a1 |
| object table ptr | 567a2 |

#### Warp Table

```
[03, 22, 37, 24, 0f, 2b, 98, 10, 0f, 2b, 98, 10]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 17, 63]
```

- dark room
- object 0x63 @ (7,1)

### Room 15

 ***(2, 5) @ 567a7***

| | |
|-|-|
| warp table ptr | 567b0 |
| enemy table ptr | 567b4 |
| object table ptr | 567b5 |

#### Warp Table

```
[03, 23, 36, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0b, df, 78]
```

- npc [48, 2, b, df, 78]

### Room 16

 ***(2, 6) @ 567bc***

| | |
|-|-|
| warp table ptr | 567c5 |
| enemy table ptr | 567c9 |
| object table ptr | 567ca |

#### Warp Table

```
[03, 24, 75, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 09, e3, 78]
```

- npc [48, 2, 9, e3, 78]

### Room 17

 ***(2, 7) @ 567d1***

| | |
|-|-|
| warp table ptr | 567da |
| enemy table ptr | 567de |
| object table ptr | 567df |

#### Warp Table

```
[03, 25, 3c, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 07, e7, 78]
```

- npc [48, 2, 7, e7, 78]

### Room 18

 ***(3, 0) @ 567e6***

| | |
|-|-|
| warp table ptr | 567ef |
| enemy table ptr | 567ef |
| object table ptr | 567f0 |

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

 ***(3, 1) @ 567f1***

| | |
|-|-|
| warp table ptr | 567fa |
| enemy table ptr | 567fe |
| object table ptr | 567ff |

#### Warp Table

```
[03, 28, 35, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 06, 75, 78, da, 46, 00, 00, 05, 00, 01, 01, da, 4a, 00, 00, 05, 00, 01, 01]
```

- npc [48, 2, 6, 75, 78]
- shop item [46, 0, 0, 5, 0, 1, 1]
- shop item [4a, 0, 0, 5, 0, 1, 1]

### Room 1A

 ***(3, 2) @ 56816***

| | |
|-|-|
| warp table ptr | 5681f |
| enemy table ptr | 56823 |
| object table ptr | 56824 |

#### Warp Table

```
[03, 29, 37, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 03, 7a, 79]
```

- npc [48, 2, 3, 7a, 79]

### Room 1B

 ***(3, 3) @ 5682b***

| | |
|-|-|
| warp table ptr | 56834 |
| enemy table ptr | 5683c |
| object table ptr | 5683d |

#### Warp Table

```
[03, 2a, 39, 24, 03, 09, 77, 30]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 04, 44, 7a, 08, 46, 25]
```

- npc [48, 2, 4, 44, 7a]
- bell gated object 0x25 @ (6,4)

### Room 1C

 ***(3, 4) @ 56847***

| | |
|-|-|
| warp table ptr | 56850 |
| enemy table ptr | 56854 |
| object table ptr | 56855 |

#### Warp Table

```
[03, 2d, 34, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 05, 71, 78, da, 46, 00, 00, 03, 00, 00, 01, da, 4a, 00, 00, 03, 00, 00, 01]
```

- npc [48, 2, 5, 71, 78]
- shop item [46, 0, 0, 3, 0, 0, 1]
- shop item [4a, 0, 0, 3, 0, 0, 1]

### Room 1D

 ***(3, 5) @ 5686c***

| | |
|-|-|
| warp table ptr | 56875 |
| enemy table ptr | 5687d |
| object table ptr | 5687e |

#### Warp Table

```
[03, 2e, 3b, 24, 03, 09, 77, 30]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 04, 44, 7a, 08, 46, 25]
```

- npc [48, 2, 4, 44, 7a]
- bell gated object 0x25 @ (6,4)

### Room 1E

 ***(3, 6) @ 56888***

| | |
|-|-|
| warp table ptr | 56891 |
| enemy table ptr | 56895 |
| object table ptr | 56896 |

#### Warp Table

```
[03, 2f, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 01, fb, 78, da, 46, 00, 00, 05, 00, 06, 01]
```

- npc [48, 2, 1, fb, 78]
- shop item [46, 0, 0, 5, 0, 6, 1]

### Room 1F

 ***(3, 7) @ 568a5***

| | |
|-|-|
| warp table ptr | 568ae |
| enemy table ptr | 568b2 |
| object table ptr | 568b3 |

#### Warp Table

```
[03, 30, 24, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0e, 65, 7a]
```

- npc [48, 2, e, 65, 7a]

### Room 20

 ***(4, 0) @ 568ba***

| | |
|-|-|
| warp table ptr | 568c3 |
| enemy table ptr | 568c7 |
| object table ptr | 568c8 |

#### Warp Table

```
[03, 32, 2b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 06, eb, 78]
```

- npc [48, 2, 6, eb, 78]

### Room 21

 ***(4, 1) @ 568cf***

| | |
|-|-|
| warp table ptr | 568d8 |
| enemy table ptr | 568dc |
| object table ptr | 568dd |

#### Warp Table

```
[03, 33, 35, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0a, ff, 78]
```

- npc [48, 2, a, ff, 78]

### Room 22

 ***(4, 2) @ 568e4***

| | |
|-|-|
| warp table ptr | 568ed |
| enemy table ptr | 568f1 |
| object table ptr | 568f2 |

#### Warp Table

```
[03, 34, 3a, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 04, 03, 79]
```

- npc [48, 2, 4, 3, 79]

### Room 23

 ***(4, 3) @ 568f9***

| | |
|-|-|
| warp table ptr | 56902 |
| enemy table ptr | 56906 |
| object table ptr | 56907 |

#### Warp Table

```
[03, 35, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 09, 07, 79]
```

- npc [48, 2, 9, 7, 79]

### Room 24

 ***(4, 4) @ 5690e***

| | |
|-|-|
| warp table ptr | 56917 |
| enemy table ptr | 5691b |
| object table ptr | 5691c |

#### Warp Table

```
[03, 36, 68, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 48, 4c]
```

- dark room
- object 0x4c @ (8,4)

### Room 25

 ***(4, 5) @ 56921***

| | |
|-|-|
| warp table ptr | 5692a |
| enemy table ptr | 5692e |
| object table ptr | 5692f |

#### Warp Table

```
[03, 37, 34, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 06, 23, 79]
```

- npc [48, 2, 6, 23, 79]

### Room 26

 ***(4, 6) @ 56936***

| | |
|-|-|
| warp table ptr | 5693f |
| enemy table ptr | 56943 |
| object table ptr | 56944 |

#### Warp Table

```
[03, 3a, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 09, 27, 79]
```

- npc [48, 2, 9, 27, 79]

### Room 27

 ***(4, 7) @ 5694b***

| | |
|-|-|
| warp table ptr | 56954 |
| enemy table ptr | 56958 |
| object table ptr | 56959 |

#### Warp Table

```
[03, 3c, 37, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 02, 36, 79]
```

- npc [48, 2, 2, 36, 79]

### Room 28

 ***(5, 0) @ 56960***

| | |
|-|-|
| warp table ptr | 56969 |
| enemy table ptr | 56969 |
| object table ptr | 5696a |

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

 ***(5, 1) @ 5696b***

| | |
|-|-|
| warp table ptr | 56974 |
| enemy table ptr | 56974 |
| object table ptr | 56975 |

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


### Room 2A

 ***(5, 2) @ 56976***

| | |
|-|-|
| warp table ptr | 5697f |
| enemy table ptr | 56983 |
| object table ptr | 56984 |

#### Warp Table

```
[03, 3f, 3b, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 03, 0b, 79]
```

- npc [48, 2, 3, b, 79]

### Room 2B

 ***(5, 3) @ 5698b***

| | |
|-|-|
| warp table ptr | 56994 |
| enemy table ptr | 56998 |
| object table ptr | 56999 |

#### Warp Table

```
[0f, 14, 37, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[00, 46, 4d, 0b, 48, 2a, 80, 00, 46, 61, 00, 49, 51, 0b, 48, 2a, 40, 00, 49, 61]
```

- object 0x4d @ (6,4)
- unknown object 0x0b [48, 2a, 80]
- object 0x61 @ (6,4)
- object 0x51 @ (9,4)
- unknown object 0x0b [48, 2a, 40]
- object 0x61 @ (9,4)

### Room 2C

 ***(5, 4) @ 569ae***

| | |
|-|-|
| warp table ptr | 569b7 |
| enemy table ptr | 569b7 |
| object table ptr | 569b8 |

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

 ***(5, 5) @ 569b9***

| | |
|-|-|
| warp table ptr | 569c2 |
| enemy table ptr | 569c6 |
| object table ptr | 569c7 |

#### Warp Table

```
[03, 01, 34, 24]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 03, 00, 7a]
```

- npc [48, 2, 3, 0, 7a]

### Room 2E

 ***(5, 6) @ 569ce***

| | |
|-|-|
| warp table ptr | 569d7 |
| enemy table ptr | 569db |
| object table ptr | 569dc |

#### Warp Table

```
[03, 17, 78, 04]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[9a, 48, 02, 0b, 2c, 7a]
```

- npc [48, 2, b, 2c, 7a]

### Room 2F

 ***(5, 7) @ 569e3***

| | |
|-|-|
| warp table ptr | 569ec |
| enemy table ptr | 569ec |
| object table ptr | 569ed |

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

 ***(6, 0) @ 569ee***

| | |
|-|-|
| warp table ptr | 569f7 |
| enemy table ptr | 569f7 |
| object table ptr | 569f8 |

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

 ***(6, 1) @ 569f9***

| | |
|-|-|
| warp table ptr | 56a02 |
| enemy table ptr | 56a02 |
| object table ptr | 56a03 |

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

 ***(6, 2) @ 56a04***

| | |
|-|-|
| warp table ptr | 56a0d |
| enemy table ptr | 56a0d |
| object table ptr | 56a0e |

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

 ***(6, 3) @ 56a0f***

| | |
|-|-|
| warp table ptr | 56a18 |
| enemy table ptr | 56a18 |
| object table ptr | 56a19 |

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


### Room 34

 ***(6, 4) @ 56a1a***

| | |
|-|-|
| warp table ptr | 56a23 |
| enemy table ptr | 56a23 |
| object table ptr | 56a24 |

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


### Room 35

 ***(6, 5) @ 56a25***

| | |
|-|-|
| warp table ptr | 56a2e |
| enemy table ptr | 56a2e |
| object table ptr | 56a2f |

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


### Room 36

 ***(6, 6) @ 56a30***

| | |
|-|-|
| warp table ptr | 56a39 |
| enemy table ptr | 56a39 |
| object table ptr | 56a3a |

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


### Room 37

 ***(6, 7) @ 56a3b***

| | |
|-|-|
| warp table ptr | 56a44 |
| enemy table ptr | 56a44 |
| object table ptr | 56a45 |

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

 ***(7, 0) @ 56a46***

| | |
|-|-|
| warp table ptr | 56a4f |
| enemy table ptr | 56a4f |
| object table ptr | 56a50 |

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

 ***(7, 1) @ 56a51***

| | |
|-|-|
| warp table ptr | 56a5a |
| enemy table ptr | 56a5a |
| object table ptr | 56a5b |

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

 ***(7, 2) @ 56a5c***

| | |
|-|-|
| warp table ptr | 56a65 |
| enemy table ptr | 56a65 |
| object table ptr | 56a66 |

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

 ***(7, 3) @ 56a67***

| | |
|-|-|
| warp table ptr | 56a70 |
| enemy table ptr | 56a70 |
| object table ptr | 56a71 |

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

 ***(7, 4) @ 56a72***

| | |
|-|-|
| warp table ptr | 56a7b |
| enemy table ptr | 56a7b |
| object table ptr | 56a7c |

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

 ***(7, 5) @ 56a7d***

| | |
|-|-|
| warp table ptr | 56a86 |
| enemy table ptr | 56a86 |
| object table ptr | 56a87 |

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


### Room 3E

 ***(7, 6) @ 56a88***

| | |
|-|-|
| warp table ptr | 56a91 |
| enemy table ptr | 56a91 |
| object table ptr | 56a92 |

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

 ***(7, 7) @ 56a93***

| | |
|-|-|
| warp table ptr | 56a9c |
| enemy table ptr | 56a9c |
| object table ptr | 56a9d |

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


