# Area 1

## Overview

| | |
|-|-|
| Area data table pointer | 50bf9 |
| Room order table pointer | 50066 |

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
| 7 | [38](#room-38) | [39](#room-39) | [3a](#room-3a) | [3b](#room-3b) | [3c](#room-3c) | [3d](#room-3d) | [3e](#room-3e) | [3f](#room-3f) |## Rooms

### Room 00

 ***(0, 0) @ 50cb9***

| | |
|-|-|
| warp table ptr | 50cc2 |
| enemy table ptr | 50cc6 |
| object table ptr | 50cca |

#### Warp Table

```
[06, 3c, a7, 0a]
```

#### Enemy Table

```
[9f, 88, 00]
```

#### Object Table

```
[]
```


### Room 01

 ***(0, 1) @ 50ccb***

| | |
|-|-|
| warp table ptr | 50cd4 |
| enemy table ptr | 50cd8 |
| object table ptr | 50cdf |

#### Warp Table

```
[0d, 09, 98, 10]
```

#### Enemy Table

```
[9b, 88, 00, 9b, 6a, 00]
```

#### Object Table

```
[00, 49, 3c, 0c, 46, 02]
```

- object 0x3c @ (9,4)
- burnable 0x02 @ (6,4)

### Room 02

 ***(0, 2) @ 50ce6***

| | |
|-|-|
| warp table ptr | 50cef |
| enemy table ptr | 50cf3 |
| object table ptr | 50cfd |

#### Warp Table

```
[0d, 00, 98, 18]
```

#### Enemy Table

```
[9f, 48, 00, 9e, 68, 00, 9e, 67, 00]
```

#### Object Table

```
[]
```


### Room 03

 ***(0, 3) @ 50cfe***

| | |
|-|-|
| warp table ptr | 50d07 |
| enemy table ptr | 50d0b |
| object table ptr | 50d0f |

#### Warp Table

```
[0d, 21, 98, 18]
```

#### Enemy Table

```
[9c, 88, 00]
```

#### Object Table

```
[]
```


### Room 04

 ***(0, 4) @ 50d10***

| | |
|-|-|
| warp table ptr | 50d19 |
| enemy table ptr | 50d1d |
| object table ptr | 50d27 |

#### Warp Table

```
[0d, 0a, 98, 10]
```

#### Enemy Table

```
[a2, 88, 00, a2, 64, 00, a2, 69, 00]
```

#### Object Table

```
[00, 45, 3c, 0c, 4a, 02]
```

- object 0x3c @ (5,4)
- burnable 0x02 @ (10,4)

### Room 05

 ***(0, 5) @ 50d2e***

| | |
|-|-|
| warp table ptr | 50d37 |
| enemy table ptr | 50d3b |
| object table ptr | 50d42 |

#### Warp Table

```
[0d, 0b, 98, 18]
```

#### Enemy Table

```
[a1, 88, 00, a1, 6d, 03]
```

#### Object Table

```
[0c, 07, 00]
```

- burnable 0x00 @ (7,0)

### Room 06

 ***(0, 6) @ 50d46***

| | |
|-|-|
| warp table ptr | 50d4f |
| enemy table ptr | 50d53 |
| object table ptr | 50d57 |

#### Warp Table

```
[0d, 0c, 98, 10]
```

#### Enemy Table

```
[a0, 88, 00]
```

#### Object Table

```
[00, 5c, 35, 06, 53, 24]
```

- object 0x35 @ (12,5)
- push block gated object 0x24 @ (3,5)

### Room 07

 ***(0, 7) @ 50d5e***

| | |
|-|-|
| warp table ptr | 50d67 |
| enemy table ptr | 50d67 |
| object table ptr | 50d6b |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 87, 00]
```

#### Object Table

```
[00, 37, 34, 00, 77, 34]
```

- object 0x34 @ (7,3)
- object 0x34 @ (7,7)

### Room 08

 ***(1, 0) @ 50d72***

| | |
|-|-|
| warp table ptr | 50d7b |
| enemy table ptr | 50d7f |
| object table ptr | 50d8c |

#### Warp Table

```
[0d, 0d, 98, 18]
```

#### Enemy Table

```
[9f, 53, 00, 9f, 5b, 02, 9f, 73, 02, 9f, 7b, 03]
```

#### Object Table

```
[]
```


### Room 09

 ***(1, 1) @ 50d8d***

| | |
|-|-|
| warp table ptr | 50d96 |
| enemy table ptr | 50d9a |
| object table ptr | 50da4 |

#### Warp Table

```
[0d, 0e, 98, 18]
```

#### Enemy Table

```
[a0, 33, 00, a0, 4a, 00, a0, 88, 00]
```

#### Object Table

```
[0c, 03, 00]
```

- burnable 0x00 @ (3,0)

### Room 0A

 ***(1, 2) @ 50da8***

| | |
|-|-|
| warp table ptr | 50db1 |
| enemy table ptr | 50db1 |
| object table ptr | 50dbb |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 46, 00, 9b, 67, 00, 9d, 6f, 00]
```

#### Object Table

```
[]
```


### Room 0B

 ***(1, 3) @ 50dbc***

| | |
|-|-|
| warp table ptr | 50dc5 |
| enemy table ptr | 50dc9 |
| object table ptr | 50dd6 |

#### Warp Table

```
[0d, 0f, 98, 18]
```

#### Enemy Table

```
[9e, 57, 00, 9e, 66, 00, 9e, 68, 00, 9e, 77, 00]
```

#### Object Table

```
[00, 64, 33, 00, 6b, 33]
```

- object 0x33 @ (4,6)
- object 0x33 @ (11,6)

### Room 0C

 ***(1, 4) @ 50ddd***

| | |
|-|-|
| warp table ptr | 50de6 |
| enemy table ptr | 50de6 |
| object table ptr | 50df0 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a2, 65, 00, a2, 67, 00, a2, 69, 00]
```

#### Object Table

```
[00, 34, 40, 00, 3b, 40, 00, 74, 40, 00, 7b, 40]
```

- object 0x40 @ (4,3)
- object 0x40 @ (11,3)
- object 0x40 @ (4,7)
- object 0x40 @ (11,7)

### Room 0D

 ***(1, 5) @ 50dfd***

| | |
|-|-|
| warp table ptr | 50e06 |
| enemy table ptr | 50e06 |
| object table ptr | 50e0d |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 64, 00, 9c, 6b, 00]
```

#### Object Table

```
[]
```


### Room 0E

 ***(1, 6) @ 50e0e***

| | |
|-|-|
| warp table ptr | 50e17 |
| enemy table ptr | 50e1b |
| object table ptr | 50e25 |

#### Warp Table

```
[0d, 10, 98, 18]
```

#### Enemy Table

```
[a1, 22, 00, a1, 67, 00, a1, 88, 00]
```

#### Object Table

```
[0c, 0c, 00, 00, 58, 40]
```

- burnable 0x00 @ (12,0)
- object 0x40 @ (8,5)

### Room 0F

 ***(1, 7) @ 50e2c***

| | |
|-|-|
| warp table ptr | 50e35 |
| enemy table ptr | 50e35 |
| object table ptr | 50e3c |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9c, 64, 00, 9c, 6b, 00]
```

#### Object Table

```
[00, 55, 33, 00, 5a, 33]
```

- object 0x33 @ (5,5)
- object 0x33 @ (10,5)

### Room 10

 ***(2, 0) @ 50e43***

| | |
|-|-|
| warp table ptr | 50e4c |
| enemy table ptr | 50e50 |
| object table ptr | 50e5a |

#### Warp Table

```
[0d, 1e, 98, 10]
```

#### Enemy Table

```
[9e, 38, 00, 9e, 48, 00, 9e, 58, 00]
```

#### Object Table

```
[00, 44, 24]
```

- object 0x24 @ (4,4)

### Room 11

 ***(2, 1) @ 50e5e***

| | |
|-|-|
| warp table ptr | 50e67 |
| enemy table ptr | 50e67 |
| object table ptr | 50e6e |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9f, 88, 00, 9f, 48, 00]
```

#### Object Table

```
[00, 57, 3c, 00, 58, 3c, 00, 59, 3c]
```

- object 0x3c @ (7,5)
- object 0x3c @ (8,5)
- object 0x3c @ (9,5)

### Room 12

 ***(2, 2) @ 50e78***

| | |
|-|-|
| warp table ptr | 50e81 |
| enemy table ptr | 50e85 |
| object table ptr | 50e92 |

#### Warp Table

```
[0d, 11, 98, 10]
```

#### Enemy Table

```
[9b, 44, 00, 9b, a8, 00, 9b, 6b, 00, 9d, 6e, 00]
```

#### Object Table

```
[00, 57, 3c, 0c, 58, 02]
```

- object 0x3c @ (7,5)
- burnable 0x02 @ (8,5)

### Room 13

 ***(2, 3) @ 50e99***

| | |
|-|-|
| warp table ptr | 50ea2 |
| enemy table ptr | 50ea2 |
| object table ptr | 50eac |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a0, 55, 00, a0, 77, 00, a0, 6b, 00]
```

#### Object Table

```
[]
```


### Room 14

 ***(2, 4) @ 50ead***

| | |
|-|-|
| warp table ptr | 50eb6 |
| enemy table ptr | 50eba |
| object table ptr | 50ec1 |

#### Warp Table

```
[0d, 12, 98, 10]
```

#### Enemy Table

```
[9c, 55, 00, 9c, 67, 00]
```

#### Object Table

```
[00, 57, 35, 06, 32, 24]
```

- object 0x35 @ (7,5)
- push block gated object 0x24 @ (2,3)

### Room 15

 ***(2, 5) @ 50ec8***

| | |
|-|-|
| warp table ptr | 50ed1 |
| enemy table ptr | 50ed5 |
| object table ptr | 50edf |

#### Warp Table

```
[0d, 13, 98, 18]
```

#### Enemy Table

```
[9e, 58, 02, 9e, 56, 02, 9e, 5a, 02]
```

#### Object Table

```
[0c, 08, 00]
```

- burnable 0x00 @ (8,0)

### Room 16

 ***(2, 6) @ 50ee3***

| | |
|-|-|
| warp table ptr | 50eec |
| enemy table ptr | 50ef0 |
| object table ptr | 50ef4 |

#### Warp Table

```
[0d, 01, 98, 10]
```

#### Enemy Table

```
[9c, 37, 00]
```

#### Object Table

```
[0c, 88, 04]
```

- burnable 0x04 @ (8,8)

### Room 17

 ***(2, 7) @ 50ef8***

| | |
|-|-|
| warp table ptr | 50f01 |
| enemy table ptr | 50f01 |
| object table ptr | 50f02 |

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
[00, 8a, 40]
```

- object 0x40 @ (10,8)

### Room 18

 ***(3, 0) @ 50f06***

| | |
|-|-|
| warp table ptr | 50f0f |
| enemy table ptr | 50f0f |
| object table ptr | 50f13 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9e, 67, 00]
```

#### Object Table

```
[00, 77, 3c, 00, 78, 3c, 00, 79, 3c, 00, 4b, 3c, 00, 4c, 3c]
```

- object 0x3c @ (7,7)
- object 0x3c @ (8,7)
- object 0x3c @ (9,7)
- object 0x3c @ (11,4)
- object 0x3c @ (12,4)

### Room 19

 ***(3, 1) @ 50f23***

| | |
|-|-|
| warp table ptr | 50f2c |
| enemy table ptr | 50f2c |
| object table ptr | 50f39 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a0, 45, 00, a0, 4a, 00, a0, 75, 00, a0, 7a, 00]
```

#### Object Table

```
[00, 4b, 3c, 00, 7b, 3c]
```

- object 0x3c @ (11,4)
- object 0x3c @ (11,7)

### Room 1A

 ***(3, 2) @ 50f40***

| | |
|-|-|
| warp table ptr | 50f49 |
| enemy table ptr | 50f49 |
| object table ptr | 50f50 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 66, 00, 9d, ab, 00]
```

#### Object Table

```
[]
```


### Room 1B

 ***(3, 3) @ 50f51***

| | |
|-|-|
| warp table ptr | 50f5a |
| enemy table ptr | 50f5e |
| object table ptr | 50f68 |

#### Warp Table

```
[0d, 02, 98, 10]
```

#### Enemy Table

```
[a1, 65, 00, a1, 75, 00, a1, 86, 00]
```

#### Object Table

```
[00, 58, 35, 00, 5c, 33, 06, 2e, 24, 00, 09, 41]
```

- object 0x35 @ (8,5)
- object 0x33 @ (12,5)
- push block gated object 0x24 @ (14,2)
- object 0x41 @ (9,0)

### Room 1C

 ***(3, 4) @ 50f75***

| | |
|-|-|
| warp table ptr | 50f7e |
| enemy table ptr | 50f82 |
| object table ptr | 50f89 |

#### Warp Table

```
[0d, 03, 98, 10]
```

#### Enemy Table

```
[9c, 67, 00, 9c, 69, 00]
```

#### Object Table

```
[0c, 43, 04]
```

- burnable 0x04 @ (3,4)

### Room 1D

 ***(3, 5) @ 50f8d***

| | |
|-|-|
| warp table ptr | 50f96 |
| enemy table ptr | 50f9a |
| object table ptr | 50fa1 |

#### Warp Table

```
[0d, 14, 98, 10]
```

#### Enemy Table

```
[9f, 34, 00, a0, 88, 00]
```

#### Object Table

```
[00, 47, 40, 0c, 48, 04, 00, 49, 40]
```

- object 0x40 @ (7,4)
- burnable 0x04 @ (8,4)
- object 0x40 @ (9,4)

### Room 1E

 ***(3, 6) @ 50fab***

| | |
|-|-|
| warp table ptr | 50fb4 |
| enemy table ptr | 50fb4 |
| object table ptr | 50fbb |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a0, 45, 00, a0, 7a, 00]
```

#### Object Table

```
[00, 45, 40, 00, 46, 40, 00, 49, 40, 00, 4a, 40]
```

- object 0x40 @ (5,4)
- object 0x40 @ (6,4)
- object 0x40 @ (9,4)
- object 0x40 @ (10,4)

### Room 1F

 ***(3, 7) @ 50fc8***

| | |
|-|-|
| warp table ptr | 50fd1 |
| enemy table ptr | 50fd1 |
| object table ptr | 50fdb |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9f, 66, 00, 9f, 68, 00, 9c, 67, 02]
```

#### Object Table

```
[00, 45, 33, 00, 4a, 33, 00, 85, 33, 00, 8a, 33]
```

- object 0x33 @ (5,4)
- object 0x33 @ (10,4)
- object 0x33 @ (5,8)
- object 0x33 @ (10,8)

### Room 20

 ***(4, 0) @ 50fe8***

| | |
|-|-|
| warp table ptr | 50ff1 |
| enemy table ptr | 50ff1 |
| object table ptr | 50ff8 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9c, 65, 00, 9c, 6a, 02]
```

#### Object Table

```
[00, 57, 3c, 00, 58, 3c]
```

- object 0x3c @ (7,5)
- object 0x3c @ (8,5)

### Room 21

 ***(4, 1) @ 50fff***

| | |
|-|-|
| warp table ptr | 51008 |
| enemy table ptr | 5100c |
| object table ptr | 51010 |

#### Warp Table

```
[0d, 15, 98, 10]
```

#### Enemy Table

```
[9e, 5a, 02]
```

#### Object Table

```
[00, 54, 32, 06, 23, 24]
```

- object 0x32 @ (4,5)
- push block gated object 0x24 @ (3,2)

### Room 22

 ***(4, 2) @ 51017***

| | |
|-|-|
| warp table ptr | 51020 |
| enemy table ptr | 51020 |
| object table ptr | 5102a |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9f, 45, 00, 9f, 75, 00, 9d, 2a, 00]
```

#### Object Table

```
[]
```


### Room 23

 ***(4, 3) @ 5102b***

| | |
|-|-|
| warp table ptr | 51034 |
| enemy table ptr | 51038 |
| object table ptr | 5103f |

#### Warp Table

```
[0d, 16, 98, 10]
```

#### Enemy Table

```
[9b, 57, 00, 9d, 17, 00]
```

#### Object Table

```
[0c, 6a, 04]
```

- burnable 0x04 @ (10,6)

### Room 24

 ***(4, 4) @ 51043***

| | |
|-|-|
| warp table ptr | 5104c |
| enemy table ptr | 51050 |
| object table ptr | 51057 |

#### Warp Table

```
[0d, 1f, 98, 10]
```

#### Enemy Table

```
[9d, 13, 00, 9d, 6b, 00]
```

#### Object Table

```
[00, 65, 24]
```

- object 0x24 @ (5,6)

### Room 25

 ***(4, 5) @ 5105b***

| | |
|-|-|
| warp table ptr | 51064 |
| enemy table ptr | 51068 |
| object table ptr | 51069 |

#### Warp Table

```
[0d, 04, 98, 18]
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

 ***(4, 6) @ 5106a***

| | |
|-|-|
| warp table ptr | 51073 |
| enemy table ptr | 51073 |
| object table ptr | 5107d |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a0, 45, 00, a0, 49, 00, a0, 77, 00]
```

#### Object Table

```
[]
```


### Room 27

 ***(4, 7) @ 5107e***

| | |
|-|-|
| warp table ptr | 51087 |
| enemy table ptr | 51087 |
| object table ptr | 51094 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a1, 45, 00, a1, 4a, 00, a1, 75, 00, a1, 7a, 00]
```

#### Object Table

```
[00, 58, 40]
```

- object 0x40 @ (8,5)

### Room 28

 ***(5, 0) @ 51098***

| | |
|-|-|
| warp table ptr | 510a1 |
| enemy table ptr | 510a5 |
| object table ptr | 510b8 |

#### Warp Table

```
[0d, 23, 98, 10]
```

#### Enemy Table

```
[9e, 65, 00, 9e, 6a, 00, 9e, 46, 00, 9e, 49, 00, 9e, 86, 00, 9e, 89, 00]
```

#### Object Table

```
[07, 67, 24]
```

- enemy gated object 0x24 @ (7,6)

### Room 29

 ***(5, 1) @ 510bc***

| | |
|-|-|
| warp table ptr | 510c5 |
| enemy table ptr | 510c9 |
| object table ptr | 510d6 |

#### Warp Table

```
[0d, 05, 98, 10]
```

#### Enemy Table

```
[a0, 45, 00, a0, 5b, 00, a0, 83, 00, a0, 79, 00]
```

#### Object Table

```
[00, 1b, 3d, 00, 1c, 3d]
```

- object 0x3d @ (11,1)
- object 0x3d @ (12,1)

### Room 2A

 ***(5, 2) @ 510dd***

| | |
|-|-|
| warp table ptr | 510e6 |
| enemy table ptr | 510ea |
| object table ptr | 510f7 |

#### Warp Table

```
[0d, 22, 98, 10]
```

#### Enemy Table

```
[a2, 44, 00, a2, 83, 00, a2, 5a, 00, a2, 79, 00]
```

#### Object Table

```
[00, 68, 32, 06, 66, 24]
```

- object 0x32 @ (8,6)
- push block gated object 0x24 @ (6,6)

### Room 2B

 ***(5, 3) @ 510fe***

| | |
|-|-|
| warp table ptr | 51107 |
| enemy table ptr | 51107 |
| object table ptr | 51114 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 48, 00, 9b, 8c, 00, 9c, 4c, 00, 9c, 9b, 00]
```

#### Object Table

```
[]
```


### Room 2C

 ***(5, 4) @ 51115***

| | |
|-|-|
| warp table ptr | 5111e |
| enemy table ptr | 5111e |
| object table ptr | 51128 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9c, 87, 00, 9c, 88, 00, 9b, 55, 00]
```

#### Object Table

```
[]
```


### Room 2D

 ***(5, 5) @ 51129***

| | |
|-|-|
| warp table ptr | 51132 |
| enemy table ptr | 51136 |
| object table ptr | 51137 |

#### Warp Table

```
[07, 3b, a7, 0a]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 2E

 ***(5, 6) @ 51138***

| | |
|-|-|
| warp table ptr | 51141 |
| enemy table ptr | 51145 |
| object table ptr | 51152 |

#### Warp Table

```
[0d, 17, 98, 18]
```

#### Enemy Table

```
[9f, 66, 00, 9f, 67, 00, 9f, 68, 00, 9f, 69, 00]
```

#### Object Table

```
[]
```


### Room 2F

 ***(5, 7) @ 51153***

| | |
|-|-|
| warp table ptr | 5115c |
| enemy table ptr | 5115c |
| object table ptr | 51166 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a1, 33, 00, a1, 4b, 00, a1, 89, 00]
```

#### Object Table

```
[00, 64, 33, 00, 55, 33, 00, 65, 33, 00, 75, 33, 00, 46, 33, 00, 66, 33, 00, 86, 33, 00, 67, 33, 00, 68, 33, 00, 69, 33]
```

- object 0x33 @ (4,6)
- object 0x33 @ (5,5)
- object 0x33 @ (5,6)
- object 0x33 @ (5,7)
- object 0x33 @ (6,4)
- object 0x33 @ (6,6)
- object 0x33 @ (6,8)
- object 0x33 @ (7,6)
- object 0x33 @ (8,6)
- object 0x33 @ (9,6)

### Room 30

 ***(6, 0) @ 51185***

| | |
|-|-|
| warp table ptr | 5118e |
| enemy table ptr | 51192 |
| object table ptr | 5119f |

#### Warp Table

```
[0d, 06, 98, 10]
```

#### Enemy Table

```
[a1, 44, 00, a1, 69, 00, 9f, 65, 00, 9d, 61, 00]
```

#### Object Table

```
[0c, 1c, 03]
```

- burnable 0x03 @ (12,1)

### Room 31

 ***(6, 1) @ 511a3***

| | |
|-|-|
| warp table ptr | 511ac |
| enemy table ptr | 511b0 |
| object table ptr | 511bd |

#### Warp Table

```
[0d, 07, 98, 10]
```

#### Enemy Table

```
[9b, 66, 00, 9b, 67, 00, 9b, 68, 00, 9b, 69, 00]
```

#### Object Table

```
[]
```


### Room 32

 ***(6, 2) @ 511be***

| | |
|-|-|
| warp table ptr | 511c7 |
| enemy table ptr | 511cb |
| object table ptr | 511cc |

#### Warp Table

```
[0c, 00, 73, 08]
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

 ***(6, 3) @ 511cd***

| | |
|-|-|
| warp table ptr | 511d6 |
| enemy table ptr | 511d6 |
| object table ptr | 511e9 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a2, 63, 00, 9c, 42, 00, 9c, 83, 00, 9c, 68, 00, 9c, 3b, 00, 9d, 55, 00]
```

#### Object Table

```
[]
```


### Room 34

 ***(6, 4) @ 511ea***

| | |
|-|-|
| warp table ptr | 511f3 |
| enemy table ptr | 511f7 |
| object table ptr | 511fe |

#### Warp Table

```
[0d, 18, 98, 18]
```

#### Enemy Table

```
[a2, 56, 00, a2, 7b, 00]
```

#### Object Table

```
[0c, 19, 00, 00, 74, 33, 00, 7a, 33]
```

- burnable 0x00 @ (9,1)
- object 0x33 @ (4,7)
- object 0x33 @ (10,7)

### Room 35

 ***(6, 5) @ 51208***

| | |
|-|-|
| warp table ptr | 51211 |
| enemy table ptr | 51219 |
| object table ptr | 5121a |

#### Warp Table

```
[0d, 08, 98, 18, 0d, 1d, 98, 10]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[09, 00, 5b, 33, 00, 73, 33, 00, 7b, 33, 00, 53, 35, 06, 3c, 25]
```

- dark room
- object 0x33 @ (11,5)
- object 0x33 @ (3,7)
- object 0x33 @ (11,7)
- object 0x35 @ (3,5)
- push block gated object 0x25 @ (12,3)

### Room 36

 ***(6, 6) @ 5122b***

| | |
|-|-|
| warp table ptr | 51234 |
| enemy table ptr | 51234 |
| object table ptr | 5123e |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 52, 00, 9b, 85, 00, a2, 68, 00]
```

#### Object Table

```
[00, 78, 40]
```

- object 0x40 @ (8,7)

### Room 37

 ***(6, 7) @ 51242***

| | |
|-|-|
| warp table ptr | 5124b |
| enemy table ptr | 5124f |
| object table ptr | 51259 |

#### Warp Table

```
[0d, 19, 98, 10]
```

#### Enemy Table

```
[a0, 34, 00, a0, 3a, 00, a0, 85, 00]
```

#### Object Table

```
[00, 65, 35, 06, 6a, 24]
```

- object 0x35 @ (5,6)
- push block gated object 0x24 @ (10,6)

### Room 38

 ***(7, 0) @ 51260***

| | |
|-|-|
| warp table ptr | 51269 |
| enemy table ptr | 5126d |
| object table ptr | 51274 |

#### Warp Table

```
[0d, 1a, 98, 10]
```

#### Enemy Table

```
[9f, 64, 01, 9f, 6b, 03]
```

#### Object Table

```
[09, 00, 69, 32, 06, a4, 24]
```

- dark room
- object 0x32 @ (9,6)
- push block gated object 0x24 @ (4,10)

### Room 39

 ***(7, 1) @ 5127c***

| | |
|-|-|
| warp table ptr | 51285 |
| enemy table ptr | 51285 |
| object table ptr | 51292 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9e, 2c, 00, 9e, 3c, 00, 9e, 4c, 00, 9e, 5c, 00]
```

#### Object Table

```
[]
```


### Room 3A

 ***(7, 2) @ 51293***

| | |
|-|-|
| warp table ptr | 5129c |
| enemy table ptr | 5129c |
| object table ptr | 512a6 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a1, 23, 00, a1, 4b, 00, 9d, a8, 00]
```

#### Object Table

```
[]
```


### Room 3B

 ***(7, 3) @ 512a7***

| | |
|-|-|
| warp table ptr | 512b0 |
| enemy table ptr | 512b4 |
| object table ptr | 512be |

#### Warp Table

```
[0d, 1b, 98, 10]
```

#### Enemy Table

```
[9e, 59, 00, 9d, 75, 00, 9d, 34, 00]
```

#### Object Table

```
[00, 59, 24]
```

- object 0x24 @ (9,5)

### Room 3C

 ***(7, 4) @ 512c2***

| | |
|-|-|
| warp table ptr | 512cb |
| enemy table ptr | 512cf |
| object table ptr | 512d9 |

#### Warp Table

```
[0d, 24, 98, 10]
```

#### Enemy Table

```
[9b, 34, 00, 9b, 4a, 00, 9b, 66, 02]
```

#### Object Table

```
[00, 48, 35, 06, 46, 24]
```

- object 0x35 @ (8,4)
- push block gated object 0x24 @ (6,4)

### Room 3D

 ***(7, 5) @ 512e0***

| | |
|-|-|
| warp table ptr | 512e9 |
| enemy table ptr | 512e9 |
| object table ptr | 512f3 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[a2, 64, 01, a2, 57, 02, a2, 6b, 03]
```

#### Object Table

```
[]
```


### Room 3E

 ***(7, 6) @ 512f4***

| | |
|-|-|
| warp table ptr | 512fd |
| enemy table ptr | 512fd |
| object table ptr | 51307 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[9b, 56, 00, 9b, 58, 00, a0, 76, 00]
```

#### Object Table

```
[]
```


### Room 3F

 ***(7, 7) @ 51308***

| | |
|-|-|
| warp table ptr | 51311 |
| enemy table ptr | 51315 |
| object table ptr | 51322 |

#### Warp Table

```
[0d, 1c, 98, 10]
```

#### Enemy Table

```
[9e, 5a, 03, a1, 73, 00, 9d, 4e, 00, 9d, 9f, 00]
```

#### Object Table

```
[00, 5a, 24]
```

- object 0x24 @ (10,5)

