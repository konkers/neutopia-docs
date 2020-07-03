# Area 0

## Overview

| | |
|-|-|
| Area data table pointer | 5054e |
| Room order table pointer | 50066 |
| Chest table pointer | 5044e |

## Room Map/Order

|   | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 |
  |---|---|---|---|---|---|---|---|---|
| 0 | [00](#room-00) | [01](#room-01) | [02](#room-02) | [03](#room-03) | [04](#room-04) | [05](#room-05) | [06](#room-06) | [07](#room-07) |
| 1 | [08](#room-08) | [09](#room-09) | [0a](#room-0a) | [0b](#room-0b) | [0c](#room-0c) | [0d](#room-0d) | [0e](#room-0e) | [0f](#room-0f) |
| 2 | [10](#room-10) | [11](#room-11) | [12](#room-12) | [13](#room-13) | [14](#room-14) | [15](#room-15) | [16](#room-16) | [17](#room-17) |
| 3 | [18](#room-18) | [19](#room-19) | [1a](#room-1a) | [1b](#room-1b) | [1c](#room-1c) | [1d](#room-1d) | [1e](#room-1e) | [1f](#room-1f) |
| 4 | [20](#room-20) | [21](#room-21) | [22](#room-22) | [23](#room-23) | [24](#room-24) | [25](#room-25) | [26](#room-26) | [27](#room-27) |
| 5 | [28](#room-28) | [29](#room-29) | [2a](#room-2a) | [2b](#room-2b) | [2c](#room-2c) | [2d](#room-2d) | [2e](#room-2e) | [2f](#room-2f) |
| 6 | [30](#room-30) | [31](#room-31) | [32](#room-32) | [33](#room-33) | [34](#room-34) | [35](#room-35) | [36](#room-36) | [37](#room-37) |
| 7 | [38](#room-38) | [39](#room-39) | [3a](#room-3a) | [3b](#room-3b) | [3c](#room-3c) | [3d](#room-3d) | [3e](#room-3e) | [3f](#room-3f) |
## Chests

| index | item id | arg | text | ?? |
|-------|---------|-----|------|----|
| 0 | 11 | 01 | 85 | 41 |
| 1 | 10 | 01 | 8b | 41 |
| 2 | 09 | 02 | 91 | 41 |
| 3 | 12 | 01 | 97 | 41 |
| 4 | 00 | 04 | a3 | 41 |
| 5 | 00 | 04 | 15 | 43 |
| 6 | 11 | 01 | 85 | 41 |
| 7 | 08 | 02 | 9d | 41 |
## Rooms

### Room 00

 ***(0, 0) @ 5060e***

| | |
|-|-|
| warp table ptr | 50617 |
| enemy table ptr | 5061b |
| object table ptr | 50622 |

#### Warp Table

```
[0c, 02, 98, 10]
```

#### Enemy Table

```
[82, 3c, 00, 82, 83, 00]
```

#### Object Table

```
[07, 5c, 24]
```

- enemy gated object 0x24 @ (12,5)

### Room 01

 ***(0, 1) @ 50626***

| | |
|-|-|
| warp table ptr | 5062f |
| enemy table ptr | 50633 |
| object table ptr | 50637 |

#### Warp Table

```
[04, 3b, a7, 0a]
```

#### Enemy Table

```
[81, 66, 03]
```

#### Object Table

```
[]
```


### Room 02

 ***(0, 2) @ 50638***

| | |
|-|-|
| warp table ptr | 50641 |
| enemy table ptr | 50641 |
| object table ptr | 5064b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[81, 33, 03, 81, 64, 00, 81, 3b, 02]
```

#### Object Table

```
[]
```


### Room 03

 ***(0, 3) @ 5064c***

| | |
|-|-|
| warp table ptr | 50655 |
| enemy table ptr | 50659 |
| object table ptr | 5065d |

#### Warp Table

```
[0c, 0e, 98, 10]
```

#### Enemy Table

```
[87, 58, 02]
```

#### Object Table

```
[0c, 47, 02]
```

- burnable 0x02 @ (7,4)

### Room 04

 ***(0, 4) @ 50661***

| | |
|-|-|
| warp table ptr | 5066a |
| enemy table ptr | 5066e |
| object table ptr | 50675 |

#### Warp Table

```
[0c, 26, 98, 10]
```

#### Enemy Table

```
[87, 38, 02, 88, 77, 02]
```

#### Object Table

```
[07, 7a, 24]
```

- enemy gated object 0x24 @ (10,7)

### Room 05

 ***(0, 5) @ 50679***

| | |
|-|-|
| warp table ptr | 50682 |
| enemy table ptr | 50686 |
| object table ptr | 50690 |

#### Warp Table

```
[0c, 13, 98, 10]
```

#### Enemy Table

```
[83, 53, 00, 83, 57, 00, 83, 7d, 00]
```

#### Object Table

```
[0c, 34, 04]
```

- burnable 0x04 @ (4,3)

### Room 06

 ***(0, 6) @ 50694***

| | |
|-|-|
| warp table ptr | 5069d |
| enemy table ptr | 506a1 |
| object table ptr | 506a8 |

#### Warp Table

```
[0c, 14, 98, 18]
```

#### Enemy Table

```
[82, 54, 00, 82, 6c, 00]
```

#### Object Table

```
[0c, 27, 00]
```

- burnable 0x00 @ (7,2)

### Room 07

 ***(0, 7) @ 506ac***

| | |
|-|-|
| warp table ptr | 506b5 |
| enemy table ptr | 506b9 |
| object table ptr | 506c3 |

#### Warp Table

```
[0c, 15, 98, 10]
```

#### Enemy Table

```
[83, 58, 02, 83, 84, 00, 83, 34, 02]
```

#### Object Table

```
[00, 59, 35, 06, 55, 24]
```

- object 0x35 @ (9,5)
- push block gated object 0x24 @ (5,5)

### Room 08

 ***(1, 0) @ 506ca***

| | |
|-|-|
| warp table ptr | 506d3 |
| enemy table ptr | 506d7 |
| object table ptr | 506e1 |

#### Warp Table

```
[0c, 27, 98, 18]
```

#### Enemy Table

```
[83, 54, 00, 83, 77, 00, 83, 9a, 00]
```

#### Object Table

```
[]
```


### Room 09

 ***(1, 1) @ 506e2***

| | |
|-|-|
| warp table ptr | 506eb |
| enemy table ptr | 506ef |
| object table ptr | 506f3 |

#### Warp Table

```
[0c, 03, 98, 18]
```

#### Enemy Table

```
[82, 78, 00]
```

#### Object Table

```
[0c, 08, 00]
```

- burnable 0x00 @ (8,0)

### Room 0A

 ***(1, 2) @ 506f7***

| | |
|-|-|
| warp table ptr | 50700 |
| enemy table ptr | 50704 |
| object table ptr | 50711 |

#### Warp Table

```
[0c, 04, 98, 18]
```

#### Enemy Table

```
[83, 87, 02, 83, 89, 02, 83, 72, 02, 83, 7c, 02]
```

#### Object Table

```
[0c, 13, 00]
```

- burnable 0x00 @ (3,1)

### Room 0B

 ***(1, 3) @ 50715***

| | |
|-|-|
| warp table ptr | 5071e |
| enemy table ptr | 5071e |
| object table ptr | 50728 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[86, 73, 00, 86, 77, 00, 86, 7b, 00]
```

#### Object Table

```
[]
```


### Room 0C

 ***(1, 4) @ 50729***

| | |
|-|-|
| warp table ptr | 50732 |
| enemy table ptr | 50736 |
| object table ptr | 50740 |

#### Warp Table

```
[0c, 0b, 98, 18]
```

#### Enemy Table

```
[80, 54, 00, 80, 7c, 00, 88, 1b, 02]
```

#### Object Table

```
[]
```


### Room 0D

 ***(1, 5) @ 50741***

| | |
|-|-|
| warp table ptr | 5074a |
| enemy table ptr | 5074a |
| object table ptr | 50754 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[80, 5b, 02, 80, 54, 02, 88, 1a, 02]
```

#### Object Table

```
[]
```


### Room 0E

 ***(1, 6) @ 50755***

| | |
|-|-|
| warp table ptr | 5075e |
| enemy table ptr | 50762 |
| object table ptr | 5076f |

#### Warp Table

```
[0c, 2a, 98, 10]
```

#### Enemy Table

```
[82, 44, 00, 82, 66, 00, 82, 78, 00, 82, 9c, 00]
```

#### Object Table

```
[00, 53, 33, 00, 5c, 35, 06, 58, 24]
```

- object 0x33 @ (3,5)
- object 0x35 @ (12,5)
- push block gated object 0x24 @ (8,5)

### Room 0F

 ***(1, 7) @ 50779***

| | |
|-|-|
| warp table ptr | 50782 |
| enemy table ptr | 50786 |
| object table ptr | 5078d |

#### Warp Table

```
[0c, 17, 98, 18]
```

#### Enemy Table

```
[83, 83, 00, 83, 8c, 00]
```

#### Object Table

```
[00, 68, 40, 00, 69, 40, 0c, 29, 00]
```

- object 0x40 @ (8,6)
- object 0x40 @ (9,6)
- burnable 0x00 @ (9,2)

### Room 10

 ***(2, 0) @ 50797***

| | |
|-|-|
| warp table ptr | 507a0 |
| enemy table ptr | 507a4 |
| object table ptr | 507ab |

#### Warp Table

```
[0c, 05, 98, 18]
```

#### Enemy Table

```
[83, 48, 00, 83, 98, 00]
```

#### Object Table

```
[]
```


### Room 11

 ***(2, 1) @ 507ac***

| | |
|-|-|
| warp table ptr | 507b5 |
| enemy table ptr | 507b9 |
| object table ptr | 507c6 |

#### Warp Table

```
[0c, 16, 98, 18]
```

#### Enemy Table

```
[82, 44, 00, 82, 4a, 00, 82, 84, 00, 82, 8a, 00]
```

#### Object Table

```
[0c, 0a, 00]
```

- burnable 0x00 @ (10,0)

### Room 12

 ***(2, 2) @ 507ca***

| | |
|-|-|
| warp table ptr | 507d3 |
| enemy table ptr | 507d7 |
| object table ptr | 507de |

#### Warp Table

```
[0c, 18, 98, 10]
```

#### Enemy Table

```
[87, 69, 02, 87, 66, 00]
```

#### Object Table

```
[0c, 55, 02]
```

- burnable 0x02 @ (5,5)

### Room 13

 ***(2, 3) @ 507e2***

| | |
|-|-|
| warp table ptr | 507eb |
| enemy table ptr | 507eb |
| object table ptr | 507f5 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[86, 34, 00, 86, 67, 00, 86, 3d, 00]
```

#### Object Table

```
[]
```


### Room 14

 ***(2, 4) @ 507f6***

| | |
|-|-|
| warp table ptr | 507ff |
| enemy table ptr | 50803 |
| object table ptr | 50810 |

#### Warp Table

```
[0c, 19, 98, 18]
```

#### Enemy Table

```
[85, 43, 00, 85, 4c, 00, 85, 83, 00, 85, 8c, 00]
```

#### Object Table

```
[]
```


### Room 15

 ***(2, 5) @ 50811***

| | |
|-|-|
| warp table ptr | 5081a |
| enemy table ptr | 5081e |
| object table ptr | 50825 |

#### Warp Table

```
[0c, 0c, 98, 18]
```

#### Enemy Table

```
[85, 76, 02, 88, 6c, 00]
```

#### Object Table

```
[]
```


### Room 16

 ***(2, 6) @ 50826***

| | |
|-|-|
| warp table ptr | 5082f |
| enemy table ptr | 50833 |
| object table ptr | 5083d |

#### Warp Table

```
[0c, 1a, 98, 10]
```

#### Enemy Table

```
[80, 33, 01, 80, 82, 01, 80, 5d, 03]
```

#### Object Table

```
[07, 55, 24]
```

- enemy gated object 0x24 @ (5,5)

### Room 17

 ***(2, 7) @ 50841***

| | |
|-|-|
| warp table ptr | 5084a |
| enemy table ptr | 5084e |
| object table ptr | 50855 |

#### Warp Table

```
[05, 2c, a7, 0a]
```

#### Enemy Table

```
[80, 65, 02, 80, 6b, 02]
```

#### Object Table

```
[]
```


### Room 18

 ***(3, 0) @ 50856***

| | |
|-|-|
| warp table ptr | 5085f |
| enemy table ptr | 5085f |
| object table ptr | 50869 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[83, 66, 00, 83, 78, 00, 83, 8a, 00]
```

#### Object Table

```
[]
```


### Room 19

 ***(3, 1) @ 5086a***

| | |
|-|-|
| warp table ptr | 50873 |
| enemy table ptr | 50877 |
| object table ptr | 50881 |

#### Warp Table

```
[0c, 1b, 98, 18]
```

#### Enemy Table

```
[82, 45, 00, 82, 67, 00, 82, 79, 00]
```

#### Object Table

```
[0c, 11, 00]
```

- burnable 0x00 @ (1,1)

### Room 1A

 ***(3, 2) @ 50885***

| | |
|-|-|
| warp table ptr | 5088e |
| enemy table ptr | 5088e |
| object table ptr | 50898 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[86, 55, 00, 86, 77, 00, 86, 99, 00]
```

#### Object Table

```
[]
```


### Room 1B

 ***(3, 3) @ 50899***

| | |
|-|-|
| warp table ptr | 508a2 |
| enemy table ptr | 508a2 |
| object table ptr | 508a9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[85, 55, 02, 85, 5a, 02]
```

#### Object Table

```
[00, 68, 3c]
```

- object 0x3c @ (8,6)

### Room 1C

 ***(3, 4) @ 508ad***

| | |
|-|-|
| warp table ptr | 508b6 |
| enemy table ptr | 508ba |
| object table ptr | 508c7 |

#### Warp Table

```
[0c, 1c, 98, 10]
```

#### Enemy Table

```
[81, 44, 01, 81, 4a, 01, 81, 84, 03, 81, 8a, 03]
```

#### Object Table

```
[0c, 78, 03]
```

- burnable 0x03 @ (8,7)

### Room 1D

 ***(3, 5) @ 508cb***

| | |
|-|-|
| warp table ptr | 508d4 |
| enemy table ptr | 508d4 |
| object table ptr | 508db |

#### Warp Table

```
[]
```

#### Enemy Table

```
[86, 67, 02, 88, 3d, 00]
```

#### Object Table

```
[]
```


### Room 1E

 ***(3, 6) @ 508dc***

| | |
|-|-|
| warp table ptr | 508e5 |
| enemy table ptr | 508e9 |
| object table ptr | 508f0 |

#### Warp Table

```
[0c, 0d, 98, 18]
```

#### Enemy Table

```
[80, 7a, 02, 88, 77, 02]
```

#### Object Table

```
[]
```


### Room 1F

 ***(3, 7) @ 508f1***

| | |
|-|-|
| warp table ptr | 508fa |
| enemy table ptr | 508fa |
| object table ptr | 50907 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[80, 44, 03, 80, 66, 00, 80, 99, 02, 88, 7e, 03]
```

#### Object Table

```
[]
```


### Room 20

 ***(4, 0) @ 50908***

| | |
|-|-|
| warp table ptr | 50911 |
| enemy table ptr | 50911 |
| object table ptr | 5091b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[83, 25, 00, 83, 69, 00, 83, a7, 00]
```

#### Object Table

```
[]
```


### Room 21

 ***(4, 1) @ 5091c***

| | |
|-|-|
| warp table ptr | 50925 |
| enemy table ptr | 50929 |
| object table ptr | 50930 |

#### Warp Table

```
[0c, 06, 98, 18]
```

#### Enemy Table

```
[83, 65, 00, 83, 8b, 00]
```

#### Object Table

```
[]
```


### Room 22

 ***(4, 2) @ 50931***

| | |
|-|-|
| warp table ptr | 5093a |
| enemy table ptr | 5093e |
| object table ptr | 50945 |

#### Warp Table

```
[0c, 0f, 98, 18]
```

#### Enemy Table

```
[85, 78, 03, 85, 9a, 00]
```

#### Object Table

```
[00, 26, 3c, 00, 27, 3c, 00, 28, 3c]
```

- object 0x3c @ (6,2)
- object 0x3c @ (7,2)
- object 0x3c @ (8,2)

### Room 23

 ***(4, 3) @ 5094f***

| | |
|-|-|
| warp table ptr | 50958 |
| enemy table ptr | 50958 |
| object table ptr | 50962 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[80, 46, 02, 80, 6a, 01, 80, 8a, 00]
```

#### Object Table

```
[]
```


### Room 24

 ***(4, 4) @ 50963***

| | |
|-|-|
| warp table ptr | 5096c |
| enemy table ptr | 5096c |
| object table ptr | 50976 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 54, 01, 82, 39, 03, 82, 89, 03]
```

#### Object Table

```
[]
```


### Room 25

 ***(4, 5) @ 50977***

| | |
|-|-|
| warp table ptr | 50980 |
| enemy table ptr | 50980 |
| object table ptr | 5098a |

#### Warp Table

```
[]
```

#### Enemy Table

```
[86, 65, 00, 86, 78, 00, 86, 8b, 00]
```

#### Object Table

```
[]
```


### Room 26

 ***(4, 6) @ 5098b***

| | |
|-|-|
| warp table ptr | 50994 |
| enemy table ptr | 50994 |
| object table ptr | 509a1 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[85, 5b, 03, 84, 33, 02, 84, 73, 00, 88, 78, 00]
```

#### Object Table

```
[]
```


### Room 27

 ***(4, 7) @ 509a2***

| | |
|-|-|
| warp table ptr | 509ab |
| enemy table ptr | 509af |
| object table ptr | 509b9 |

#### Warp Table

```
[0c, 28, 98, 10]
```

#### Enemy Table

```
[88, a7, 00, 85, 59, 02, 88, 4e, 03]
```

#### Object Table

```
[0c, 37, 02]
```

- burnable 0x02 @ (7,3)

### Room 28

 ***(5, 0) @ 509bd***

| | |
|-|-|
| warp table ptr | 509c6 |
| enemy table ptr | 509c6 |
| object table ptr | 509d3 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 45, 02, 82, 4b, 02, 82, 85, 00, 82, 89, 00]
```

#### Object Table

```
[]
```


### Room 29

 ***(5, 1) @ 509d4***

| | |
|-|-|
| warp table ptr | 509dd |
| enemy table ptr | 509e1 |
| object table ptr | 509e8 |

#### Warp Table

```
[0c, 1e, 98, 10]
```

#### Enemy Table

```
[82, 73, 01, 84, 7c, 01]
```

#### Object Table

```
[00, 58, 24]
```

- object 0x24 @ (8,5)

### Room 2A

 ***(5, 2) @ 509ec***

| | |
|-|-|
| warp table ptr | 509f5 |
| enemy table ptr | 509f9 |
| object table ptr | 50a03 |

#### Warp Table

```
[0c, 1f, 98, 10]
```

#### Enemy Table

```
[82, 6b, 01, 82, 47, 03, 82, 87, 03]
```

#### Object Table

```
[00, 69, 24]
```

- object 0x24 @ (9,6)

### Room 2B

 ***(5, 3) @ 50a07***

| | |
|-|-|
| warp table ptr | 50a10 |
| enemy table ptr | 50a10 |
| object table ptr | 50a17 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[84, 48, 03, 84, 88, 03]
```

#### Object Table

```
[]
```


### Room 2C

 ***(5, 4) @ 50a18***

| | |
|-|-|
| warp table ptr | 50a21 |
| enemy table ptr | 50a25 |
| object table ptr | 50a2c |

#### Warp Table

```
[0c, 07, 98, 10]
```

#### Enemy Table

```
[86, 45, 00, 86, 7a, 00]
```

#### Object Table

```
[00, 59, 24]
```

- object 0x24 @ (9,5)

### Room 2D

 ***(5, 5) @ 50a30***

| | |
|-|-|
| warp table ptr | 50a39 |
| enemy table ptr | 50a3d |
| object table ptr | 50a47 |

#### Warp Table

```
[0c, 20, 98, 10]
```

#### Enemy Table

```
[87, 64, 03, 87, 47, 03, 87, 87, 03]
```

#### Object Table

```
[0c, 55, 02]
```

- burnable 0x02 @ (5,5)

### Room 2E

 ***(5, 6) @ 50a4b***

| | |
|-|-|
| warp table ptr | 50a54 |
| enemy table ptr | 50a58 |
| object table ptr | 50a5f |

#### Warp Table

```
[0c, 1d, 98, 10]
```

#### Enemy Table

```
[82, 37, 00, 82, 78, 00]
```

#### Object Table

```
[00, 55, 3c, 0c, 56, 02]
```

- object 0x3c @ (5,5)
- burnable 0x02 @ (6,5)

### Room 2F

 ***(5, 7) @ 50a66***

| | |
|-|-|
| warp table ptr | 50a6f |
| enemy table ptr | 50a73 |
| object table ptr | 50a77 |

#### Warp Table

```
[0c, 21, 98, 10]
```

#### Enemy Table

```
[84, 74, 00]
```

#### Object Table

```
[00, 59, 32, 06, 77, 24]
```

- object 0x32 @ (9,5)
- push block gated object 0x24 @ (7,7)

### Room 30

 ***(6, 0) @ 50a7e***

| | |
|-|-|
| warp table ptr | 50a87 |
| enemy table ptr | 50a8b |
| object table ptr | 50a92 |

#### Warp Table

```
[0c, 22, 98, 10]
```

#### Enemy Table

```
[82, 57, 02, 82, 98, 02]
```

#### Object Table

```
[0c, 6e, 04]
```

- burnable 0x04 @ (14,6)

### Room 31

 ***(6, 1) @ 50a96***

| | |
|-|-|
| warp table ptr | 50a9f |
| enemy table ptr | 50a9f |
| object table ptr | 50aa9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 44, 00, 84, 3b, 00, 84, 7a, 00]
```

#### Object Table

```
[]
```


### Room 32

 ***(6, 2) @ 50aaa***

| | |
|-|-|
| warp table ptr | 50ab3 |
| enemy table ptr | 50ab7 |
| object table ptr | 50ac1 |

#### Warp Table

```
[0c, 24, 98, 10]
```

#### Enemy Table

```
[84, 34, 02, 84, 3a, 02, 84, 87, 02]
```

#### Object Table

```
[]
```


### Room 33

 ***(6, 3) @ 50ac2***

| | |
|-|-|
| warp table ptr | 50acb |
| enemy table ptr | 50acf |
| object table ptr | 50ad0 |

#### Warp Table

```
[0c, 08, 98, 18]
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

 ***(6, 4) @ 50ad1***

| | |
|-|-|
| warp table ptr | 50ada |
| enemy table ptr | 50ada |
| object table ptr | 50aed |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 64, 03, 82, 6b, 01, 84, 46, 02, 84, 49, 02, 84, 86, 00, 84, 89, 00]
```

#### Object Table

```
[]
```


### Room 35

 ***(6, 5) @ 50aee***

| | |
|-|-|
| warp table ptr | 50af7 |
| enemy table ptr | 50afb |
| object table ptr | 50b05 |

#### Warp Table

```
[0c, 0a, 98, 10]
```

#### Enemy Table

```
[87, 69, 01, 87, 47, 03, 87, 87, 03]
```

#### Object Table

```
[]
```


### Room 36

 ***(6, 6) @ 50b06***

| | |
|-|-|
| warp table ptr | 50b0f |
| enemy table ptr | 50b17 |
| object table ptr | 50b1b |

#### Warp Table

```
[0c, 23, 98, 10, 0c, 29, 98, 10]
```

#### Enemy Table

```
[87, 47, 00]
```

#### Object Table

```
[00, 56, 32, 00, 59, 31, 00, 76, 31, 00, 79, 31, 00, 2c, 24, 06, 23, 25]
```

- object 0x32 @ (6,5)
- object 0x31 @ (9,5)
- object 0x31 @ (6,7)
- object 0x31 @ (9,7)
- object 0x24 @ (12,2)
- push block gated object 0x25 @ (3,2)

### Room 37

 ***(6, 7) @ 50b2e***

| | |
|-|-|
| warp table ptr | 50b37 |
| enemy table ptr | 50b37 |
| object table ptr | 50b41 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 44, 00, 82, 85, 02, 88, 2e, 03]
```

#### Object Table

```
[00, 54, 31, 00, 5b, 31]
```

- object 0x31 @ (4,5)
- object 0x31 @ (11,5)

### Room 38

 ***(7, 0) @ 50b48***

| | |
|-|-|
| warp table ptr | 50b51 |
| enemy table ptr | 50b51 |
| object table ptr | 50b58 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 46, 02, 82, 69, 02]
```

#### Object Table

```
[]
```


### Room 39

 ***(7, 1) @ 50b59***

| | |
|-|-|
| warp table ptr | 50b62 |
| enemy table ptr | 50b66 |
| object table ptr | 50b6d |

#### Warp Table

```
[0c, 10, 98, 18]
```

#### Enemy Table

```
[84, 6a, 02, 82, 53, 03]
```

#### Object Table

```
[]
```


### Room 3A

 ***(7, 2) @ 50b6e***

| | |
|-|-|
| warp table ptr | 50b77 |
| enemy table ptr | 50b7b |
| object table ptr | 50b85 |

#### Warp Table

```
[0c, 11, 98, 18]
```

#### Enemy Table

```
[84, 54, 03, 84, 57, 02, 84, 7a, 00]
```

#### Object Table

```
[]
```


### Room 3B

 ***(7, 3) @ 50b86***

| | |
|-|-|
| warp table ptr | 50b8f |
| enemy table ptr | 50b93 |
| object table ptr | 50b9a |

#### Warp Table

```
[0c, 09, 98, 10]
```

#### Enemy Table

```
[84, 64, 03, 84, 6b, 02]
```

#### Object Table

```
[00, 49, 24]
```

- object 0x24 @ (9,4)

### Room 3C

 ***(7, 4) @ 50b9e***

| | |
|-|-|
| warp table ptr | 50ba7 |
| enemy table ptr | 50bab |
| object table ptr | 50bb5 |

#### Warp Table

```
[0c, 12, 98, 18]
```

#### Enemy Table

```
[84, 47, 03, 84, 74, 02, 84, 6b, 02]
```

#### Object Table

```
[]
```


### Room 3D

 ***(7, 5) @ 50bb6***

| | |
|-|-|
| warp table ptr | 50bbf |
| enemy table ptr | 50bbf |
| object table ptr | 50bc9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[82, 65, 03, 82, 59, 02, 82, 6a, 02]
```

#### Object Table

```
[]
```


### Room 3E

 ***(7, 6) @ 50bca***

| | |
|-|-|
| warp table ptr | 50bd3 |
| enemy table ptr | 50bd3 |
| object table ptr | 50bdd |

#### Warp Table

```
[]
```

#### Enemy Table

```
[84, 37, 03, 84, 64, 02, 84, 6b, 02]
```

#### Object Table

```
[]
```


### Room 3F

 ***(7, 7) @ 50bde***

| | |
|-|-|
| warp table ptr | 50be7 |
| enemy table ptr | 50beb |
| object table ptr | 50bf5 |

#### Warp Table

```
[0c, 25, 98, 10]
```

#### Enemy Table

```
[84, 54, 02, 84, 36, 02, 88, 2e, 02]
```

#### Object Table

```
[0c, 48, 02]
```

- burnable 0x02 @ (8,4)

