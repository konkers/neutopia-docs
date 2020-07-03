# Area 2

## Overview

| | |
|-|-|
| Area data table pointer | 51326 |
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

 ***(0, 0) @ 513e6***

| | |
|-|-|
| warp table ptr | 513ef |
| enemy table ptr | 513f3 |
| object table ptr | 513f4 |

#### Warp Table

```
[09, 3d, 9d, 0a]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[0b, 4f, 2e, 00, 03, 66, 81]
```

- unknown object 0x0b [4f, 2e, 0]
- enemy gated door 0x66
- falcon boots needed

### Room 01

 ***(0, 1) @ 513fc***

| | |
|-|-|
| warp table ptr | 51405 |
| enemy table ptr | 51409 |
| object table ptr | 51413 |

#### Warp Table

```
[0e, 00, 98, 10]
```

#### Enemy Table

```
[ab, 54, 02, ab, 5b, 02, b2, 61, 02]
```

#### Object Table

```
[00, 47, 35, 00, 48, 34, 06, 67, 24]
```

- object 0x35 @ (7,4)
- object 0x34 @ (8,4)
- push block gated object 0x24 @ (7,6)

### Room 02

 ***(0, 2) @ 5141d***

| | |
|-|-|
| warp table ptr | 51426 |
| enemy table ptr | 5142a |
| object table ptr | 51437 |

#### Warp Table

```
[0e, 01, 98, 18]
```

#### Enemy Table

```
[b1, 84, 00, b1, 8b, 02, af, 88, 02, b2, 7e, 02]
```

#### Object Table

```
[]
```


### Room 03

 ***(0, 3) @ 51438***

| | |
|-|-|
| warp table ptr | 51441 |
| enemy table ptr | 51445 |
| object table ptr | 5144c |

#### Warp Table

```
[0e, 02, 98, 10]
```

#### Enemy Table

```
[ae, 3a, 02, ae, 35, 02]
```

#### Object Table

```
[00, 58, 35, 06, 55, 24]
```

- object 0x35 @ (8,5)
- push block gated object 0x24 @ (5,5)

### Room 04

 ***(0, 4) @ 51453***

| | |
|-|-|
| warp table ptr | 5145c |
| enemy table ptr | 51460 |
| object table ptr | 51467 |

#### Warp Table

```
[0e, 32, 98, 10]
```

#### Enemy Table

```
[af, 66, 01, b2, 6a, 03]
```

#### Object Table

```
[07, 8d, 24]
```

- enemy gated object 0x24 @ (13,8)

### Room 05

 ***(0, 5) @ 5146b***

| | |
|-|-|
| warp table ptr | 51474 |
| enemy table ptr | 51478 |
| object table ptr | 5147f |

#### Warp Table

```
[0e, 04, 98, 10]
```

#### Enemy Table

```
[af, 6a, 03, b2, 66, 01]
```

#### Object Table

```
[]
```


### Room 06

 ***(0, 6) @ 51480***

| | |
|-|-|
| warp table ptr | 51489 |
| enemy table ptr | 51489 |
| object table ptr | 51493 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ad, 36, 02, ad, 53, 02, ad, 59, 02]
```

#### Object Table

```
[00, 56, 33]
```

- object 0x33 @ (6,5)

### Room 07

 ***(0, 7) @ 51497***

| | |
|-|-|
| warp table ptr | 514a0 |
| enemy table ptr | 514a4 |
| object table ptr | 514c0 |

#### Warp Table

```
[02, 3f, 67, 3c]
```

#### Enemy Table

```
[b1, 35, 01, b1, 59, 01, b1, 37, 00, b1, 39, 03, b1, 55, 03, b1, 75, 01, b1, 87, 02, b1, 79, 03, b2, 1e, 02]
```

#### Object Table

```
[]
```


### Room 08

 ***(1, 0) @ 514c1***

| | |
|-|-|
| warp table ptr | 514ca |
| enemy table ptr | 514ca |
| object table ptr | 514d4 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ed, 37, 02, b2, 42, 01, b2, 4c, 03]
```

#### Object Table

```
[]
```


### Room 09

 ***(1, 1) @ 514d5***

| | |
|-|-|
| warp table ptr | 514de |
| enemy table ptr | 514e2 |
| object table ptr | 514ef |

#### Warp Table

```
[0e, 05, 98, 10]
```

#### Enemy Table

```
[ac, 64, 02, ac, 6b, 02, b2, 12, 01, b2, 1d, 03]
```

#### Object Table

```
[0c, 89, 05, 00, 86, 41]
```

- burnable 0x05 @ (9,8)
- object 0x41 @ (6,8)

### Room 0A

 ***(1, 2) @ 514f6***

| | |
|-|-|
| warp table ptr | 514ff |
| enemy table ptr | 51503 |
| object table ptr | 51510 |

#### Warp Table

```
[0e, 06, 98, 18]
```

#### Enemy Table

```
[ae, 98, 01, ae, 4b, 02, ae, 43, 02, b2, 61, 02]
```

#### Object Table

```
[]
```


### Room 0B

 ***(1, 3) @ 51511***

| | |
|-|-|
| warp table ptr | 5151a |
| enemy table ptr | 5151e |
| object table ptr | 51528 |

#### Warp Table

```
[0e, 07, 98, 10]
```

#### Enemy Table

```
[b0, 5a, 02, b0, 55, 02, b0, 78, 02]
```

#### Object Table

```
[0c, 4c, 04, 00, 48, 40]
```

- burnable 0x04 @ (12,4)
- object 0x40 @ (8,4)

### Room 0C

 ***(1, 4) @ 5152f***

| | |
|-|-|
| warp table ptr | 51538 |
| enemy table ptr | 5153c |
| object table ptr | 51546 |

#### Warp Table

```
[0e, 08, 98, 18]
```

#### Enemy Table

```
[af, 54, 02, af, 5a, 02, b2, 17, 02]
```

#### Object Table

```
[]
```


### Room 0D

 ***(1, 5) @ 51547***

| | |
|-|-|
| warp table ptr | 51550 |
| enemy table ptr | 51554 |
| object table ptr | 5155b |

#### Warp Table

```
[0e, 09, 98, 18]
```

#### Enemy Table

```
[b0, 66, 01, b2, 17, 03]
```

#### Object Table

```
[0c, 0b, 00, 00, 45, 33, 00, 4b, 33, 00, 75, 33, 00, 7b, 33]
```

- burnable 0x00 @ (11,0)
- object 0x33 @ (5,4)
- object 0x33 @ (11,4)
- object 0x33 @ (5,7)
- object 0x33 @ (11,7)

### Room 0E

 ***(1, 6) @ 5156b***

| | |
|-|-|
| warp table ptr | 51574 |
| enemy table ptr | 51578 |
| object table ptr | 51582 |

#### Warp Table

```
[0e, 0a, 98, 18]
```

#### Enemy Table

```
[ae, 65, 01, ae, 89, 03, ae, 6a, 03]
```

#### Object Table

```
[]
```


### Room 0F

 ***(1, 7) @ 51583***

| | |
|-|-|
| warp table ptr | 5158c |
| enemy table ptr | 5158c |
| object table ptr | 51593 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ab, 48, 03, b2, 14, 01]
```

#### Object Table

```
[00, 53, 40, 00, 54, 40, 00, 55, 40, 00, 56, 40, 00, 57, 40, 00, 58, 40, 00, 59, 40, 00, 5a, 40]
```

- object 0x40 @ (3,5)
- object 0x40 @ (4,5)
- object 0x40 @ (5,5)
- object 0x40 @ (6,5)
- object 0x40 @ (7,5)
- object 0x40 @ (8,5)
- object 0x40 @ (9,5)
- object 0x40 @ (10,5)

### Room 10

 ***(2, 0) @ 515ac***

| | |
|-|-|
| warp table ptr | 515b5 |
| enemy table ptr | 515b9 |
| object table ptr | 515c9 |

#### Warp Table

```
[0e, 0b, 98, 18]
```

#### Enemy Table

```
[b0, 37, 02, b0, 67, 02, b0, 56, 02, b0, 58, 02, b2, 81, 01]
```

#### Object Table

```
[00, 47, 40]
```

- object 0x40 @ (7,4)

### Room 11

 ***(2, 1) @ 515cd***

| | |
|-|-|
| warp table ptr | 515d6 |
| enemy table ptr | 515da |
| object table ptr | 515e7 |

#### Warp Table

```
[0e, 33, 98, 10]
```

#### Enemy Table

```
[ad, 54, 02, ad, 5b, 02, b2, 61, 02, b2, ac, 03]
```

#### Object Table

```
[07, 53, 24]
```

- enemy gated object 0x24 @ (3,5)

### Room 12

 ***(2, 2) @ 515eb***

| | |
|-|-|
| warp table ptr | 515f4 |
| enemy table ptr | 515f8 |
| object table ptr | 51602 |

#### Warp Table

```
[0e, 0c, 98, 18]
```

#### Enemy Table

```
[af, 54, 01, af, 97, 00, b2, 77, 02]
```

#### Object Table

```
[00, 6b, 30]
```

- object 0x30 @ (11,6)

### Room 13

 ***(2, 3) @ 51606***

| | |
|-|-|
| warp table ptr | 5160f |
| enemy table ptr | 51613 |
| object table ptr | 5161d |

#### Warp Table

```
[0e, 0d, 98, 18]
```

#### Enemy Table

```
[ac, 49, 02, ac, 89, 02, b2, 25, 02]
```

#### Object Table

```
[0c, 06, 00]
```

- burnable 0x00 @ (6,0)

### Room 14

 ***(2, 4) @ 51621***

| | |
|-|-|
| warp table ptr | 5162a |
| enemy table ptr | 5162e |
| object table ptr | 5163b |

#### Warp Table

```
[0e, 0e, 98, 18]
```

#### Enemy Table

```
[ad, 48, 02, ad, 85, 01, ad, 8b, 03, b2, 25, 02]
```

#### Object Table

```
[0c, 04, 00]
```

- burnable 0x00 @ (4,0)

### Room 15

 ***(2, 5) @ 5163f***

| | |
|-|-|
| warp table ptr | 51648 |
| enemy table ptr | 51648 |
| object table ptr | 51652 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ab, 47, 02, ab, 73, 02, ab, 7a, 02]
```

#### Object Table

```
[]
```


### Room 16

 ***(2, 6) @ 51653***

| | |
|-|-|
| warp table ptr | 5165c |
| enemy table ptr | 51660 |
| object table ptr | 5166a |

#### Warp Table

```
[0e, 0f, 98, 10]
```

#### Enemy Table

```
[ed, 64, 02, ed, 6a, 02, b2, 7f, 02]
```

#### Object Table

```
[0c, 57, 02]
```

- burnable 0x02 @ (7,5)

### Room 17

 ***(2, 7) @ 5166e***

| | |
|-|-|
| warp table ptr | 51677 |
| enemy table ptr | 5167b |
| object table ptr | 51688 |

#### Warp Table

```
[0e, 10, 98, 18]
```

#### Enemy Table

```
[b1, 6a, 02, ed, 68, 03, b1, 66, 00, b2, 7e, 02]
```

#### Object Table

```
[0c, 14, 00]
```

- burnable 0x00 @ (4,1)

### Room 18

 ***(3, 0) @ 5168c***

| | |
|-|-|
| warp table ptr | 51695 |
| enemy table ptr | 51699 |
| object table ptr | 516a9 |

#### Warp Table

```
[08, 28, 9d, 08]
```

#### Enemy Table

```
[b0, 62, 02, b0, 66, 02, ab, 39, 01, ab, 89, 01, b2, 88, 00]
```

#### Object Table

```
[0c, 44, 00]
```

- burnable 0x00 @ (4,4)

### Room 19

 ***(3, 1) @ 516ad***

| | |
|-|-|
| warp table ptr | 516b6 |
| enemy table ptr | 516b6 |
| object table ptr | 516c0 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b0, 74, 00, ab, 6c, 03, b2, 69, 00]
```

#### Object Table

```
[]
```


### Room 1A

 ***(3, 2) @ 516c1***

| | |
|-|-|
| warp table ptr | 516ca |
| enemy table ptr | 516ce |
| object table ptr | 516e1 |

#### Warp Table

```
[0e, 12, 98, 10]
```

#### Enemy Table

```
[ac, 7a, 02, ac, 37, 02, ac, 74, 02, ed, 55, 02, ed, 59, 02, b2, 15, 01]
```

#### Object Table

```
[07, 57, 24]
```

- enemy gated object 0x24 @ (7,5)

### Room 1B

 ***(3, 3) @ 516e5***

| | |
|-|-|
| warp table ptr | 516ee |
| enemy table ptr | 516f2 |
| object table ptr | 516ff |

#### Warp Table

```
[0e, 13, 98, 18]
```

#### Enemy Table

```
[ae, 55, 01, ae, 58, 03, ae, 5a, 03, b2, 97, 00]
```

#### Object Table

```
[0c, 1b, 00]
```

- burnable 0x00 @ (11,1)

### Room 1C

 ***(3, 4) @ 51703***

| | |
|-|-|
| warp table ptr | 5170c |
| enemy table ptr | 51710 |
| object table ptr | 51717 |

#### Warp Table

```
[0e, 14, 98, 18]
```

#### Enemy Table

```
[b0, 7a, 02, b0, 75, 02]
```

#### Object Table

```
[00, 55, 30, 00, 5a, 30]
```

- object 0x30 @ (5,5)
- object 0x30 @ (10,5)

### Room 1D

 ***(3, 5) @ 5171e***

| | |
|-|-|
| warp table ptr | 51727 |
| enemy table ptr | 5172b |
| object table ptr | 51735 |

#### Warp Table

```
[0e, 15, 98, 10]
```

#### Enemy Table

```
[af, 37, 02, af, 84, 01, af, 8b, 03]
```

#### Object Table

```
[0c, 57, 03]
```

- burnable 0x03 @ (7,5)

### Room 1E

 ***(3, 6) @ 51739***

| | |
|-|-|
| warp table ptr | 51742 |
| enemy table ptr | 51746 |
| object table ptr | 5174d |

#### Warp Table

```
[0e, 16, 98, 10]
```

#### Enemy Table

```
[ab, 35, 01, ab, 86, 01]
```

#### Object Table

```
[0c, 07, 03]
```

- burnable 0x03 @ (7,0)

### Room 1F

 ***(3, 7) @ 51751***

| | |
|-|-|
| warp table ptr | 5175a |
| enemy table ptr | 5175e |
| object table ptr | 51768 |

#### Warp Table

```
[0e, 17, 98, 18]
```

#### Enemy Table

```
[ae, 6a, 03, ae, 73, 01, b2, 5e, 02]
```

#### Object Table

```
[]
```


### Room 20

 ***(4, 0) @ 51769***

| | |
|-|-|
| warp table ptr | 51772 |
| enemy table ptr | 51776 |
| object table ptr | 51780 |

#### Warp Table

```
[0e, 18, 98, 18]
```

#### Enemy Table

```
[ac, 45, 02, ac, 85, 02, b2, 61, 01]
```

#### Object Table

```
[0c, 29, 00]
```

- burnable 0x00 @ (9,2)

### Room 21

 ***(4, 1) @ 51784***

| | |
|-|-|
| warp table ptr | 5178d |
| enemy table ptr | 51791 |
| object table ptr | 5179e |

#### Warp Table

```
[0e, 19, 98, 10]
```

#### Enemy Table

```
[b1, 65, 02, b1, 66, 00, b1, 68, 00, b1, 69, 02]
```

#### Object Table

```
[0c, 57, 03]
```

- burnable 0x03 @ (7,5)

### Room 22

 ***(4, 2) @ 517a2***

| | |
|-|-|
| warp table ptr | 517ab |
| enemy table ptr | 517ab |
| object table ptr | 517b5 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ab, 7b, 03, ab, 74, 01, b2, 1b, 01]
```

#### Object Table

```
[]
```


### Room 23

 ***(4, 3) @ 517b6***

| | |
|-|-|
| warp table ptr | 517bf |
| enemy table ptr | 517c3 |
| object table ptr | 517ca |

#### Warp Table

```
[0e, 1a, 98, 18]
```

#### Enemy Table

```
[af, 77, 02, af, 7b, 02]
```

#### Object Table

```
[0c, 25, 00, 00, 84, 3c, 00, 85, 3c]
```

- burnable 0x00 @ (5,2)
- object 0x3c @ (4,8)
- object 0x3c @ (5,8)

### Room 24

 ***(4, 4) @ 517d4***

| | |
|-|-|
| warp table ptr | 517dd |
| enemy table ptr | 517e1 |
| object table ptr | 517eb |

#### Warp Table

```
[0e, 1b, 98, 10]
```

#### Enemy Table

```
[ad, 37, 02, ad, 95, 02, b2, 17, 01]
```

#### Object Table

```
[0c, 68, 02]
```

- burnable 0x02 @ (8,6)

### Room 25

 ***(4, 5) @ 517ef***

| | |
|-|-|
| warp table ptr | 517f8 |
| enemy table ptr | 517fc |
| object table ptr | 51809 |

#### Warp Table

```
[0e, 1c, 98, 18]
```

#### Enemy Table

```
[ab, 64, 01, ab, 8a, 01, ab, 4a, 01, b2, 2e, 01]
```

#### Object Table

```
[00, 6b, 31]
```

- object 0x31 @ (11,6)

### Room 26

 ***(4, 6) @ 5180d***

| | |
|-|-|
| warp table ptr | 51816 |
| enemy table ptr | 5181a |
| object table ptr | 5181b |

#### Warp Table

```
[0c, 00, 7b, 08]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[]
```


### Room 27

 ***(4, 7) @ 5181c***

| | |
|-|-|
| warp table ptr | 51825 |
| enemy table ptr | 51829 |
| object table ptr | 51830 |

#### Warp Table

```
[0e, 1d, 98, 10]
```

#### Enemy Table

```
[b1, 69, 00, b2, 6e, 03]
```

#### Object Table

```
[00, 66, 24, 00, 57, 3c, 00, 58, 3c]
```

- object 0x24 @ (6,6)
- object 0x3c @ (7,5)
- object 0x3c @ (8,5)

### Room 28

 ***(5, 0) @ 5183a***

| | |
|-|-|
| warp table ptr | 51843 |
| enemy table ptr | 51847 |
| object table ptr | 51854 |

#### Warp Table

```
[0e, 1e, 98, 10]
```

#### Enemy Table

```
[b1, 74, 02, b1, 76, 02, ac, 45, 02, ac, 6a, 02]
```

#### Object Table

```
[00, 75, 32, 06, 84, 24]
```

- object 0x32 @ (5,7)
- push block gated object 0x24 @ (4,8)

### Room 29

 ***(5, 1) @ 5185b***

| | |
|-|-|
| warp table ptr | 51864 |
| enemy table ptr | 51868 |
| object table ptr | 51878 |

#### Warp Table

```
[0e, 1f, 98, 10]
```

#### Enemy Table

```
[ed, 65, 02, ed, 6a, 02, ed, 37, 02, ed, 38, 02, ad, 8a, 03]
```

#### Object Table

```
[00, 66, 30, 00, 69, 32, 06, 67, 24]
```

- object 0x30 @ (6,6)
- object 0x32 @ (9,6)
- push block gated object 0x24 @ (7,6)

### Room 2A

 ***(5, 2) @ 51882***

| | |
|-|-|
| warp table ptr | 5188b |
| enemy table ptr | 5188f |
| object table ptr | 5189c |

#### Warp Table

```
[0e, 20, 98, 18]
```

#### Enemy Table

```
[b1, 67, 02, b1, 68, 02, ad, 48, 03, ad, 98, 01]
```

#### Object Table

```
[00, 55, 30, 00, 5a, 30, 00, 75, 30, 00, 7a, 30]
```

- object 0x30 @ (5,5)
- object 0x30 @ (10,5)
- object 0x30 @ (5,7)
- object 0x30 @ (10,7)

### Room 2B

 ***(5, 3) @ 518a9***

| | |
|-|-|
| warp table ptr | 518b2 |
| enemy table ptr | 518b6 |
| object table ptr | 518c6 |

#### Warp Table

```
[0e, 21, 98, 10]
```

#### Enemy Table

```
[ab, 33, 02, ab, 6d, 03, b1, 74, 02, b1, 7b, 02, b2, ad, 03]
```

#### Object Table

```
[0c, 38, 03]
```

- burnable 0x03 @ (8,3)

### Room 2C

 ***(5, 4) @ 518ca***

| | |
|-|-|
| warp table ptr | 518d3 |
| enemy table ptr | 518d7 |
| object table ptr | 518e1 |

#### Warp Table

```
[0e, 22, 98, 18]
```

#### Enemy Table

```
[ac, 47, 02, ac, 77, 02, b2, 61, 02]
```

#### Object Table

```
[0c, 13, 00, 00, 55, 30, 00, 59, 30, 00, 75, 30, 00, 79, 30]
```

- burnable 0x00 @ (3,1)
- object 0x30 @ (5,5)
- object 0x30 @ (9,5)
- object 0x30 @ (5,7)
- object 0x30 @ (9,7)

### Room 2D

 ***(5, 5) @ 518f1***

| | |
|-|-|
| warp table ptr | 518fa |
| enemy table ptr | 518fe |
| object table ptr | 51908 |

#### Warp Table

```
[0e, 23, 98, 18]
```

#### Enemy Table

```
[af, 59, 01, af, 87, 00, af, 55, 03]
```

#### Object Table

```
[0c, 13, 00]
```

- burnable 0x00 @ (3,1)

### Room 2E

 ***(5, 6) @ 5190c***

| | |
|-|-|
| warp table ptr | 51915 |
| enemy table ptr | 51915 |
| object table ptr | 5191f |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ad, 78, 02, ad, 38, 02, b2, 17, 02]
```

#### Object Table

```
[00, 46, 3c]
```

- object 0x3c @ (6,4)

### Room 2F

 ***(5, 7) @ 51923***

| | |
|-|-|
| warp table ptr | 5192c |
| enemy table ptr | 51930 |
| object table ptr | 5193a |

#### Warp Table

```
[0e, 25, 98, 10]
```

#### Enemy Table

```
[b1, 54, 02, ed, 5a, 02, b2, 77, 00]
```

#### Object Table

```
[00, 53, 3d, 0c, 5b, 03]
```

- object 0x3d @ (3,5)
- burnable 0x03 @ (11,5)

### Room 30

 ***(6, 0) @ 51941***

| | |
|-|-|
| warp table ptr | 5194a |
| enemy table ptr | 5194e |
| object table ptr | 5194f |

#### Warp Table

```
[08, 3c, 9d, 0a]
```

#### Enemy Table

```
[]
```

#### Object Table

```
[0b, 47, 2a, 80, 00, 36, 80]
```

- unknown object 0x0b [47, 2a, 80]
- object 0x80 @ (6,3)

### Room 31

 ***(6, 1) @ 51957***

| | |
|-|-|
| warp table ptr | 51960 |
| enemy table ptr | 51964 |
| object table ptr | 51974 |

#### Warp Table

```
[0e, 26, 98, 18]
```

#### Enemy Table

```
[b1, 6d, 02, af, 47, 03, af, 87, 03, af, 63, 01, b2, 61, 02]
```

#### Object Table

```
[0c, 1d, 00]
```

- burnable 0x00 @ (13,1)

### Room 32

 ***(6, 2) @ 51978***

| | |
|-|-|
| warp table ptr | 51981 |
| enemy table ptr | 51985 |
| object table ptr | 51995 |

#### Warp Table

```
[0e, 31, 98, 18]
```

#### Enemy Table

```
[b0, 68, 02, b0, 6c, 02, b1, 46, 02, b1, 86, 00, b2, 6e, 02]
```

#### Object Table

```
[0c, 15, 00]
```

- burnable 0x00 @ (5,1)

### Room 33

 ***(6, 3) @ 51999***

| | |
|-|-|
| warp table ptr | 519a2 |
| enemy table ptr | 519a2 |
| object table ptr | 519b2 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ed, 73, 02, b1, 2b, 02, ab, 42, 01, ab, 78, 01, b2, 75, 02]
```

#### Object Table

```
[]
```


### Room 34

 ***(6, 4) @ 519b3***

| | |
|-|-|
| warp table ptr | 519bc |
| enemy table ptr | 519c0 |
| object table ptr | 519cd |

#### Warp Table

```
[0e, 27, 98, 10]
```

#### Enemy Table

```
[b1, 79, 02, ab, 25, 02, ed, 75, 02, b2, 57, 02]
```

#### Object Table

```
[00, 2d, 24]
```

- object 0x24 @ (13,2)

### Room 35

 ***(6, 5) @ 519d1***

| | |
|-|-|
| warp table ptr | 519da |
| enemy table ptr | 519de |
| object table ptr | 519ee |

#### Warp Table

```
[0e, 28, 98, 18]
```

#### Enemy Table

```
[b0, 87, 02, b0, 88, 02, ae, 84, 01, ae, 8b, 03, b2, 41, 02]
```

#### Object Table

```
[0c, 38, 00]
```

- burnable 0x00 @ (8,3)

### Room 36

 ***(6, 6) @ 519f2***

| | |
|-|-|
| warp table ptr | 519fb |
| enemy table ptr | 519ff |
| object table ptr | 51a12 |

#### Warp Table

```
[0e, 29, 98, 18]
```

#### Enemy Table

```
[b1, 58, 02, b1, 59, 02, b1, 5a, 02, b1, 68, 02, b1, 69, 02, b1, 6a, 02]
```

#### Object Table

```
[0c, 1b, 00]
```

- burnable 0x00 @ (11,1)

### Room 37

 ***(6, 7) @ 51a16***

| | |
|-|-|
| warp table ptr | 51a1f |
| enemy table ptr | 51a23 |
| object table ptr | 51a36 |

#### Warp Table

```
[0e, 2a, 98, 10]
```

#### Enemy Table

```
[b1, 55, 02, b1, 65, 02, b1, 5a, 02, b1, 6a, 02, b2, 17, 02, b2, 6f, 03]
```

#### Object Table

```
[00, 45, 31, 00, 4a, 31, 00, 75, 32, 00, 7a, 31, 06, 58, 24]
```

- object 0x31 @ (5,4)
- object 0x31 @ (10,4)
- object 0x32 @ (5,7)
- object 0x31 @ (10,7)
- push block gated object 0x24 @ (8,5)

### Room 38

 ***(7, 0) @ 51a46***

| | |
|-|-|
| warp table ptr | 51a4f |
| enemy table ptr | 51a53 |
| object table ptr | 51a63 |

#### Warp Table

```
[0e, 2b, 98, 18]
```

#### Enemy Table

```
[b0, 46, 02, b0, 57, 02, b0, 47, 02, b0, 48, 02, b2, a7, 00]
```

#### Object Table

```
[]
```


### Room 39

 ***(7, 1) @ 51a64***

| | |
|-|-|
| warp table ptr | 51a6d |
| enemy table ptr | 51a71 |
| object table ptr | 51a7e |

#### Warp Table

```
[0e, 2c, 98, 18]
```

#### Enemy Table

```
[ab, 54, 03, ab, 56, 03, ab, 78, 03, b2, 94, 00]
```

#### Object Table

```
[]
```


### Room 3A

 ***(7, 2) @ 51a7f***

| | |
|-|-|
| warp table ptr | 51a88 |
| enemy table ptr | 51a8c |
| object table ptr | 51a99 |

#### Warp Table

```
[0e, 2d, 98, 18]
```

#### Enemy Table

```
[ac, 64, 02, ac, 69, 02, ed, 7c, 02, b2, ae, 00]
```

#### Object Table

```
[]
```


### Room 3B

 ***(7, 3) @ 51a9a***

| | |
|-|-|
| warp table ptr | 51aa3 |
| enemy table ptr | 51aa3 |
| object table ptr | 51ab0 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[b1, 5d, 02, ed, 82, 02, ab, 9b, 01, b2, 56, 02]
```

#### Object Table

```
[]
```


### Room 3C

 ***(7, 4) @ 51ab1***

| | |
|-|-|
| warp table ptr | 51aba |
| enemy table ptr | 51abe |
| object table ptr | 51acb |

#### Warp Table

```
[0e, 2e, 98, 18]
```

#### Enemy Table

```
[b0, 33, 02, b1, 38, 02, ab, 87, 01, b2, 5a, 02]
```

#### Object Table

```
[0c, 11, 00]
```

- burnable 0x00 @ (1,1)

### Room 3D

 ***(7, 5) @ 51acf***

| | |
|-|-|
| warp table ptr | 51ad8 |
| enemy table ptr | 51ad8 |
| object table ptr | 51ae5 |

#### Warp Table

```
[]
```

#### Enemy Table

```
[ac, 77, 02, ed, 47, 02, b2, 9c, 02, b2, 31, 02]
```

#### Object Table

```
[00, 36, 3c]
```

- object 0x3c @ (6,3)

### Room 3E

 ***(7, 6) @ 51ae9***

| | |
|-|-|
| warp table ptr | 51af2 |
| enemy table ptr | 51af6 |
| object table ptr | 51b06 |

#### Warp Table

```
[0e, 2f, 98, 18]
```

#### Enemy Table

```
[b1, 67, 02, b1, 68, 02, ab, 65, 02, ab, 6a, 02, b2, a8, 03]
```

#### Object Table

```
[0c, 16, 00]
```

- burnable 0x00 @ (6,1)

### Room 3F

 ***(7, 7) @ 51b0a***

| | |
|-|-|
| warp table ptr | 51b13 |
| enemy table ptr | 51b17 |
| object table ptr | 51b2d |

#### Warp Table

```
[02, 07, 67, 3c]
```

#### Enemy Table

```
[ed, 35, 01, ed, 59, 01, ed, 39, 03, ed, 55, 03, ed, 75, 01, ed, 79, 03, b2, 6e, 00]
```

#### Object Table

```
[]
```


