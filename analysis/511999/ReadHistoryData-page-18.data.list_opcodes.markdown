## START analysis/sarak/raw//ReadHistoryData-page-18.data
#### STOPPING DOUBLE NULLS @ 983, found 39 nulls
reading more to debug 0x00
    0000   0x00 0x00                                  ..
              0    0
##### DEBUG HEX
    0000   0x33 0x5e                                  3^
##### DEBUG DECIMAL
             51   94
#### RECORD 0 Bolus 2013-07-27T16:43:23 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x30 0x00 0x30 0x00 0x30 0x00    ..0.0.0.
    decimal
              1    0   48    0   48    0   48    0
    datetime (2013-07-27T16:43:23)
    0000   0x57 0xeb 0x50 0x7b 0x0d                   W.P{.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 1 CalBGForPH 2013-07-27T17:44:53 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 221}
```
    op hex (2)
    0000   0x0a 0xdd                                  ..
    decimal
             10  221
    datetime (2013-07-27T17:44:53)
    0000   0x75 0xec 0x31 0x1b 0x0d                   u.1..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 2 BolusWizard 2013-07-27T17:44:56 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 221,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 5.2,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 6.4,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xdd                                  [.
    decimal
             91  221
    datetime (2013-07-27T17:44:56)
    0000   0x78 0xec 0x11 0x7b 0x0d                   x..{.
    body (15)
    hex
    0000   0x00 0x50 0x00 0x64 0x3c 0x64 0x40 0x00    .P.d<d@.
    0008   0x00 0x00 0x00 0x34 0x00 0x0c 0x78         ...4..x
    decimal
              0   80    0  100   60  100   64    0
              0    0    0   52    0   12  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 3 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 61, 'amount': 1.2, 'curve': 192},
 {'age': 121, 'amount': 1.6, 'curve': 192},
 {'age': 115, 'amount': 2.3, 'curve': 208}]
```
    op hex (11)
    0000   0x5c 0x0b 0x30 0x3d 0xc0 0x40 0x79 0xc0    \.0=.@y.
    0008   0x5c 0x73 0xd0                             \s.
    decimal
             92   11   48   61  192   64  121  192
             92  115  208
    datetime (unknown)

    body (0)

#### RECORD 4 Bolus 2013-07-27T17:44:56 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 1.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x0c 0x00 0x0c 0x00 0x34 0x00    ......4.
    decimal
              1    0   12    0   12    0   52    0
    datetime (2013-07-27T17:44:56)
    0000   0x78 0xec 0x51 0x7b 0x0d                   x.Q{.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 5 CalBGForPH 2013-07-27T19:09:17 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 156}
```
    op hex (2)
    0000   0x0a 0x9c                                  ..
    decimal
             10  156
    datetime (2013-07-27T19:09:17)
    0000   0x51 0xc9 0x33 0x1b 0x0d                   Q.3..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 6 CalBGForPH 2013-07-27T19:52:55 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 124}
```
    op hex (2)
    0000   0x0a 0x7c                                  .|
    decimal
             10  124
    datetime (2013-07-27T19:52:55)
    0000   0x77 0xf4 0x33 0x1b 0x0d                   w.3..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 7 BolusWizard 2013-07-27T19:53:02 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 124,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.4,
 'carb_input': 29,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 116}
```
    op hex (2)
    0000   0x5b 0x7c                                  [|
    decimal
             91  124
    datetime (2013-07-27T19:53:02)
    0000   0x42 0xf5 0x13 0x7b 0x0d                   B..{.
    body (15)
    hex
    0000   0x1d 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x74 0x00 0x00 0x04 0x00 0x74 0x78         t....tx
    decimal
             29   80    0  100   60  100    0    0
            116    0    0    4    0  116  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 8 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 130, 'amount': 0.3, 'curve': 192},
 {'age': 190, 'amount': 1.2, 'curve': 192},
 {'age': 250, 'amount': 1.6, 'curve': 192}]
```
    op hex (11)
    0000   0x5c 0x0b 0x0c 0x82 0xc0 0x30 0xbe 0xc0    \....0..
    0008   0x40 0xfa 0xc0                             @..
    decimal
             92   11   12  130  192   48  190  192
             64  250  192
    datetime (unknown)

    body (0)

#### RECORD 9 Bolus 2013-07-27T19:53:03 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 11.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x74 0x00 0x74 0x00 0x04 0x00    ..t.t...
    decimal
              1    0  116    0  116    0    4    0
    datetime (2013-07-27T19:53:03)
    0000   0x43 0xf5 0x53 0x7b 0x0d                   C.S{.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 10 CalBGForPH 2013-07-27T22:36:45 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 116}
```
    op hex (2)
    0000   0x0a 0x74                                  .t
    decimal
             10  116
    datetime (2013-07-27T22:36:45)
    0000   0x6d 0xe4 0x36 0x1b 0x0d                   m.6..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 11 BolusWizard 2013-07-27T22:36:52 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 116,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 1.2,
 'carb_input': 18,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 72}
```
    op hex (2)
    0000   0x5b 0x74                                  [t
    decimal
             91  116
    datetime (2013-07-27T22:36:52)
    0000   0x74 0xe4 0x16 0x7b 0x0d                   t..{.
    body (15)
    hex
    0000   0x12 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x48 0x00 0x00 0x0c 0x00 0x48 0x78         H....Hx
    decimal
             18   80    0  100   60  100    0    0
             72    0    0   12    0   72  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 12 UnabsorbedInsulinBolus unknown head[14], body[0] op[0x5c]
###### DECODED
```python
[{'age': 163, 'amount': 2.9, 'curve': 192},
 {'age': 37, 'amount': 0.3, 'curve': 208},
 {'age': 97, 'amount': 1.2, 'curve': 208},
 {'age': 157, 'amount': 1.6, 'curve': 208}]
```
    op hex (14)
    0000   0x5c 0x0e 0x74 0xa3 0xc0 0x0c 0x25 0xd0    \.t...%.
    0008   0x30 0x61 0xd0 0x40 0x9d 0xd0              0a.@..
    decimal
             92   14  116  163  192   12   37  208
             48   97  208   64  157  208
    datetime (unknown)

    body (0)

#### RECORD 13 Bolus 2013-07-27T22:36:52 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 7.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x48 0x00 0x48 0x00 0x0c 0x00    ..H.H...
    decimal
              1    0   72    0   72    0   12    0
    datetime (2013-07-27T22:36:52)
    0000   0x74 0xe4 0x56 0x7b 0x0d                   t.V{.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 14 BasalProfileStart 2013-07-28T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-07-28T00:00:00)
    0000   0x40 0xc0 0x00 0x1c 0x0d                   @....
    body (3)
    hex
    0000   0x00 0x1d 0x00                             ...
    decimal
              0   29    0
    HOUR BITS: [1, 1, 0]
#### RECORD 15 MResultTotals 2013-07-28T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xa0                   .....
    decimal
              7    0    0    4  160
    datetime (2013-07-28T00:00:00)
    0000   0x7b 0x8d                                  {.
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0
    HOUR BITS: [1, 0, 0]
#### RECORD 16 Sara6E 2013-07-28T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2013-07-28T00:00:00)
    0000   0x7b 0x8d                                  {.
    body (49)
    hex
    0000   0x05 0x00 0x87 0x00 0x00 0x08 0x00 0x00    ........
    0008   0x04 0xa0 0x02 0xdc 0x3e 0x01 0xc4 0x26    ....>..&
    0010   0x00 0x70 0x01 0x88 0x00 0x0c 0x00 0x30    .p.....0
    0018   0x00 0x00 0x05 0x01 0x01 0x00 0x00 0x00    ........
    0020   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x67    .......g
    0028   0xdd 0x00 0x00 0x00 0x00 0x00 0x00 0x00    ........
    0030   0x00                                       .
    decimal
              5    0  135    0    0    8    0    0
              4  160    2  220   62    1  196   38
              0  112    1  136    0   12    0   48
              0    0    5    1    1    0    0    0
              0    0    0    0    0    0    0  103
            221    0    0    0    0    0    0    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 17 BasalProfileStart 2013-07-28T04:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2013-07-28T04:00:00)
    0000   0x40 0xc0 0x04 0x1c 0x0d                   @....
    body (3)
    hex
    0000   0x08 0x21 0x00                             .!.
    decimal
              8   33    0
    HOUR BITS: [1, 1, 0]
#### RECORD 18 BasalProfileStart 2013-07-28T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2013-07-28T08:00:00)
    0000   0x40 0xc0 0x08 0x1c 0x0d                   @....
    body (3)
    hex
    0000   0x10 0x22 0x00                             .".
    decimal
             16   34    0
    HOUR BITS: [1, 1, 0]
#### RECORD 19 CalBGForPH 2013-07-28T08:18:42 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 346}
```
    op hex (2)
    0000   0x0a 0x5a                                  .Z
    decimal
             10   90
    datetime (2013-07-28T08:18:42)
    0000   0x6a 0xd2 0x28 0x1c 0x8d                   j.(..
    body (0)
    HOUR BITS: [1, 1, 0] YEAR BITS: [1, 0, 0, 0]
#### RECORD 20 BolusWizard 2013-07-28T08:18:44 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 346,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 14.8,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0x5a                                  [Z
    decimal
             91   90
    datetime (2013-07-28T08:18:44)
    0000   0x6c 0xd2 0x08 0x7c 0x0d                   l..|.
    body (15)
    hex
    0000   0x00 0x51 0x00 0x78 0x3c 0x64 0x94 0x00    .Q.x<d..
    0008   0x00 0x00 0x00 0x00 0x00 0x94 0x78         ......x
    decimal
              0   81    0  120   60  100  148    0
              0    0    0    0    0  148  120
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 21 Bolus 2013-07-28T08:18:44 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 14.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x94 0x00 0x94 0x00 0x00 0x00    ........
    decimal
              1    0  148    0  148    0    0    0
    datetime (2013-07-28T08:18:44)
    0000   0x6c 0xd2 0x48 0x7c 0x0d                   l.H|.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 22 CalBGForPH 2013-07-28T09:37:38 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 131}
```
    op hex (2)
    0000   0x0a 0x83                                  ..
    decimal
             10  131
    datetime (2013-07-28T09:37:38)
    0000   0x66 0xe5 0x29 0x1c 0x0d                   f.)..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 23 BolusWizard 2013-07-28T09:37:44 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 131,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 7.6,
 'carb_input': 28,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.4,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 92}
```
    op hex (2)
    0000   0x5b 0x83                                  [.
    decimal
             91  131
    datetime (2013-07-28T09:37:44)
    0000   0x6c 0xe5 0x09 0x7c 0x0d                   l..|.
    body (15)
    hex
    0000   0x1c 0x50 0x00 0x78 0x3c 0x64 0x04 0x00    .P.x<d..
    0008   0x5c 0x00 0x00 0x4c 0x00 0x5c 0x78         \..L.\x
    decimal
             28   80    0  120   60  100    4    0
             92    0    0   76    0   92  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 24 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 84, 'amount': 3.7, 'curve': 192}]
```
    op hex (5)
    0000   0x5c 0x05 0x94 0x54 0xc0                   \..T.
    decimal
             92    5  148   84  192
    datetime (unknown)

    body (0)

#### RECORD 25 Bolus 2013-07-28T09:37:44 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 9.2, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x5c 0x00 0x5c 0x00 0x4c 0x00    ..\.\.L.
    decimal
              1    0   92    0   92    0   76    0
    datetime (2013-07-28T09:37:44)
    0000   0x6c 0xe5 0x49 0x7c 0x0d                   l.I|.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 26 BasalProfileStart 2013-07-28T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2013-07-28T12:00:00)
    0000   0x40 0xc0 0x0c 0x1c 0x0d                   @....
    body (3)
    hex
    0000   0x18 0x1d 0x00                             ...
    decimal
             24   29    0
    HOUR BITS: [1, 1, 0]
#### RECORD 27 CalBGForPH 2013-07-28T14:55:08 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 176}
```
    op hex (2)
    0000   0x0a 0xb0                                  ..
    decimal
             10  176
    datetime (2013-07-28T14:55:08)
    0000   0x48 0xf7 0x2e 0x1c 0x0d                   H....
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 28 BolusWizard 2013-07-28T14:55:18 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 176,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 26,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 3.6,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 84}
```
    op hex (2)
    0000   0x5b 0xb0                                  [.
    decimal
             91  176
    datetime (2013-07-28T14:55:18)
    0000   0x52 0xf7 0x0e 0x7c 0x0d                   R..|.
    body (15)
    hex
    0000   0x1a 0x50 0x00 0x78 0x3c 0x64 0x24 0x00    .P.x<d$.
    0008   0x54 0x00 0x00 0x00 0x00 0x78 0x78         T....xx
    decimal
             26   80    0  120   60  100   36    0
             84    0    0    0    0  120  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 29 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 66, 'amount': 2.3, 'curve': 208},
 {'age': 146, 'amount': 3.7, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x5c 0x42 0xd0 0x94 0x92 0xd0    \.\B....
    decimal
             92    8   92   66  208  148  146  208
    datetime (unknown)

    body (0)

#### RECORD 30 Bolus 2013-07-28T14:55:18 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 12.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x78 0x00 0x78 0x00 0x00 0x00    ..x.x...
    decimal
              1    0  120    0  120    0    0    0
    datetime (2013-07-28T14:55:18)
    0000   0x52 0xf7 0x4e 0x7c 0x0d                   R.N|.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 31 CalBGForPH 2013-07-28T19:16:59 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 226}
```
    op hex (2)
    0000   0x0a 0xe2                                  ..
    decimal
             10  226
    datetime (2013-07-28T19:16:59)
    0000   0x7b 0xd0 0x33 0x1c 0x0d                   {.3..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 32 BolusWizard 2013-07-28T19:17:01 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 226,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 6.8,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xe2                                  [.
    decimal
             91  226
    datetime (2013-07-28T19:17:01)
    0000   0x41 0xd1 0x13 0x7c 0x0d                   A..|.
    body (15)
    hex
    0000   0x00 0x50 0x00 0x64 0x3c 0x64 0x44 0x00    .P.d<dD.
    0008   0x00 0x00 0x00 0x00 0x00 0x44 0x78         .....Dx
    decimal
              0   80    0  100   60  100   68    0
              0    0    0    0    0   68  120
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 33 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 8, 'amount': 3.0, 'curve': 208}]
```
    op hex (5)
    0000   0x5c 0x05 0x78 0x08 0xd0                   \.x..
    decimal
             92    5  120    8  208
    datetime (unknown)

    body (0)

#### RECORD 34 Bolus 2013-07-28T19:17:01 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x44 0x00 0x44 0x00 0x00 0x00    ..D.D...
    decimal
              1    0   68    0   68    0    0    0
    datetime (2013-07-28T19:17:01)
    0000   0x41 0xd1 0x53 0x7c 0x0d                   A.S|.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 35 CalBGForPH 2013-07-28T20:41:43 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 123}
```
    op hex (2)
    0000   0x0a 0x7b                                  .{
    decimal
             10  123
    datetime (2013-07-28T20:41:43)
    0000   0x6b 0xe9 0x34 0x1c 0x0d                   k.4..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 36 BolusWizard 2013-07-28T20:41:51 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 123,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 3.6,
 'carb_input': 25,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 100}
```
    op hex (2)
    0000   0x5b 0x7b                                  [{
    decimal
             91  123
    datetime (2013-07-28T20:41:51)
    0000   0x73 0xe9 0x14 0x7c 0x0d                   s..|.
    body (15)
    hex
    0000   0x19 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x64 0x00 0x00 0x24 0x00 0x64 0x78         d..$.dx
    decimal
             25   80    0  100   60  100    0    0
            100    0    0   36    0  100  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 37 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 88, 'amount': 1.7, 'curve': 192},
 {'age': 92, 'amount': 3.0, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x44 0x58 0xc0 0x78 0x5c 0xd0    \.DX.x\.
    decimal
             92    8   68   88  192  120   92  208
    datetime (unknown)

    body (0)

#### RECORD 38 Bolus 2013-07-28T20:41:51 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 10.0, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x64 0x00 0x64 0x00 0x24 0x00    ..d.d.$.
    decimal
              1    0  100    0  100    0   36    0
    datetime (2013-07-28T20:41:51)
    0000   0x73 0xe9 0x54 0x7c 0x0d                   s.T|.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 39 BasalProfileStart 2013-07-29T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-07-29T00:00:00)
    0000   0x40 0xc0 0x00 0x1d 0x0d                   @....
    body (3)
    hex
    0000   0x00 0x1d 0x00                             ...
    decimal
              0   29    0
    HOUR BITS: [1, 1, 0]
#### RECORD 40 MResultTotals 2013-07-29T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xec                   .....
    decimal
              7    0    0    4  236
    datetime (2013-07-29T00:00:00)
    0000   0x7c 0x8d                                  |.
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0
    HOUR BITS: [1, 0, 0]
#### RECORD 41 Sara6E 2013-07-29T00:00:00 head[1], body[49] op[0x6e]

    op hex (1)
    0000   0x6e                                       n
    decimal
            110
    datetime (2013-07-29T00:00:00)
    0000   0x7c 0x8d                                  |.
    body (49)
    hex
    0000   0x05 0x00 0xc8 0x00 0x00 0x05 0x00 0x00    ........
    0008   0x04 0xec 0x02 0xdc 0x3a 0x02 0x10 0x2a    ....:..*
    0010   0x00 0x4f 0x00 0xc0 0x00 0xd8 0x00 0x78    .O.....x
    0018   0x00 0x00 0x02 0x02 0x01 0x00 0x04 0x00    ........
    0020   0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x7b    .......{
    0028   0x5a 0x00 0x00 0x00 0x00 0x00 0x00 0x00    Z.......
    0030   0x00                                       .
    decimal
              5    0  200    0    0    5    0    0
              4  236    2  220   58    2   16   42
              0   79    0  192    0  216    0  120
              0    0    2    2    1    0    4    0
              0    0    0    0    0    0    0  123
             90    0    0    0    0    0    0    0
              0
    HOUR BITS: [1, 0, 0]
#### RECORD 42 CalBGForPH 2013-07-29T00:20:51 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 236}
```
    op hex (2)
    0000   0x0a 0xec                                  ..
    decimal
             10  236
    datetime (2013-07-29T00:20:51)
    0000   0x73 0xd4 0x20 0x1d 0x0d                   s. ..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 43 BolusWizard 2013-07-29T00:20:58 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 110,
 '_byte[7]': 0,
 'bg': 236,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 1.4,
 'food_estimate': 6.8,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xec                                  [.
    decimal
             91  236
    datetime (2013-07-29T00:20:58)
    0000   0x7a 0xd4 0x00 0x7d 0x0d                   z..}.
    body (15)
    hex
    0000   0x00 0x50 0x00 0x78 0x3c 0x6e 0x44 0x00    .P.x<nD.
    0008   0x00 0x00 0x00 0x00 0x00 0x44 0x82         .....D.
    decimal
              0   80    0  120   60  110   68    0
              0    0    0    0    0   68  130
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 44 UnabsorbedInsulinBolus unknown head[11], body[0] op[0x5c]
###### DECODED
```python
[{'age': 217, 'amount': 0.75, 'curve': 192},
 {'age': 227, 'amount': 1.75, 'curve': 192},
 {'age': 51, 'amount': 1.7, 'curve': 208}]
```
    op hex (11)
    0000   0x5c 0x0b 0x1e 0xd9 0xc0 0x46 0xe3 0xc0    \....F..
    0008   0x44 0x33 0xd0                             D3.
    decimal
             92   11   30  217  192   70  227  192
             68   51  208
    datetime (unknown)

    body (0)

#### RECORD 45 Bolus 2013-07-29T00:20:58 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 6.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x44 0x00 0x44 0x00 0x00 0x00    ..D.D...
    decimal
              1    0   68    0   68    0    0    0
    datetime (2013-07-29T00:20:58)
    0000   0x7a 0xd4 0x40 0x7d 0x0d                   z.@}.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 46 BasalProfileStart 2013-07-29T04:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x01                                  {.
    decimal
            123    1
    datetime (2013-07-29T04:00:00)
    0000   0x40 0xc0 0x04 0x1d 0x0d                   @....
    body (3)
    hex
    0000   0x08 0x21 0x00                             .!.
    decimal
              8   33    0
    HOUR BITS: [1, 1, 0]
#### RECORD 47 BasalProfileStart 2013-07-29T08:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x02                                  {.
    decimal
            123    2
    datetime (2013-07-29T08:00:00)
    0000   0x40 0xc0 0x08 0x1d 0x0d                   @....
    body (3)
    hex
    0000   0x10 0x22 0x00                             .".
    decimal
             16   34    0
    HOUR BITS: [1, 1, 0]
#### RECORD 48 CalBGForPH 2013-07-29T08:59:30 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 171}
```
    op hex (2)
    0000   0x0a 0xab                                  ..
    decimal
             10  171
    datetime (2013-07-29T08:59:30)
    0000   0x5e 0xfb 0x28 0x1d 0x0d                   ^.(..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 49 BolusWizard 2013-07-29T08:59:43 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 171,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 20,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 3.2,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 64}
```
    op hex (2)
    0000   0x5b 0xab                                  [.
    decimal
             91  171
    datetime (2013-07-29T08:59:43)
    0000   0x6b 0xfb 0x08 0x7d 0x0d                   k..}.
    body (15)
    hex
    0000   0x14 0x50 0x00 0x78 0x3c 0x64 0x20 0x00    .P.x<d .
    0008   0x40 0x00 0x00 0x00 0x00 0x60 0x78         @....`x
    decimal
             20   80    0  120   60  100   32    0
             64    0    0    0    0   96  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 50 Bolus 2013-07-29T08:59:43 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 9.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x60 0x00 0x60 0x00 0x00 0x00    ..`.`...
    decimal
              1    0   96    0   96    0    0    0
    datetime (2013-07-29T08:59:43)
    0000   0x6b 0xfb 0x48 0x7d 0x0d                   k.H}.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 51 CalBGForPH 2013-07-29T11:25:59 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 120}
```
    op hex (2)
    0000   0x0a 0x78                                  .x
    decimal
             10  120
    datetime (2013-07-29T11:25:59)
    0000   0x7b 0xd9 0x2b 0x1d 0x0d                   {.+..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 52 BolusWizard 2013-07-29T11:26:06 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 120,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 1.2,
 'carb_input': 15,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 48}
```
    op hex (2)
    0000   0x5b 0x78                                  [x
    decimal
             91  120
    datetime (2013-07-29T11:26:06)
    0000   0x46 0xda 0x0b 0x7d 0x0d                   F..}.
    body (15)
    hex
    0000   0x0f 0x50 0x00 0x78 0x3c 0x64 0x00 0x00    .P.x<d..
    0008   0x30 0x00 0x00 0x0c 0x00 0x30 0x78         0....0x
    decimal
             15   80    0  120   60  100    0    0
             48    0    0   12    0   48  120
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 53 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 153, 'amount': 2.4, 'curve': 192}]
```
    op hex (5)
    0000   0x5c 0x05 0x60 0x99 0xc0                   \.`..
    decimal
             92    5   96  153  192
    datetime (unknown)

    body (0)

#### RECORD 54 Bolus 2013-07-29T11:26:06 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.8, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x30 0x00 0x30 0x00 0x0c 0x00    ..0.0...
    decimal
              1    0   48    0   48    0   12    0
    datetime (2013-07-29T11:26:06)
    0000   0x46 0xda 0x4b 0x7d 0x0d                   F.K}.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 55 BasalProfileStart 2013-07-29T12:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x03                                  {.
    decimal
            123    3
    datetime (2013-07-29T12:00:00)
    0000   0x40 0xc0 0x0c 0x1d 0x0d                   @....
    body (3)
    hex
    0000   0x18 0x1d 0x00                             ...
    decimal
             24   29    0
    HOUR BITS: [1, 1, 0]
#### RECORD 56 CalBGForPH 2013-07-29T12:26:22 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 131}
```
    op hex (2)
    0000   0x0a 0x83                                  ..
    decimal
             10  131
    datetime (2013-07-29T12:26:22)
    0000   0x56 0xda 0x2c 0x1d 0x0d                   V.,..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 57 BolusWizard 2013-07-29T12:26:32 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 131,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 3.6,
 'carb_input': 32,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.4,
 'sensitivity': 120,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 104}
```
    op hex (2)
    0000   0x5b 0x83                                  [.
    decimal
             91  131
    datetime (2013-07-29T12:26:32)
    0000   0x60 0xda 0x0c 0x7d 0x0d                   `..}.
    body (15)
    hex
    0000   0x20 0x50 0x00 0x78 0x3c 0x64 0x04 0x00     P.x<d..
    0008   0x68 0x00 0x00 0x24 0x00 0x68 0x78         h..$.hx
    decimal
             32   80    0  120   60  100    4    0
            104    0    0   36    0  104  120
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 58 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 63, 'amount': 1.2, 'curve': 192},
 {'age': 213, 'amount': 2.4, 'curve': 192}]
```
    op hex (8)
    0000   0x5c 0x08 0x30 0x3f 0xc0 0x60 0xd5 0xc0    \.0?.`..
    decimal
             92    8   48   63  192   96  213  192
    datetime (unknown)

    body (0)

#### RECORD 59 Bolus 2013-07-29T12:26:32 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 10.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x68 0x00 0x68 0x00 0x24 0x00    ..h.h.$.
    decimal
              1    0  104    0  104    0   36    0
    datetime (2013-07-29T12:26:32)
    0000   0x60 0xda 0x4c 0x7d 0x0d                   `.L}.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 60 CalBGForPH 2013-07-29T17:52:04 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 190}
```
    op hex (2)
    0000   0x0a 0xbe                                  ..
    decimal
             10  190
    datetime (2013-07-29T17:52:04)
    0000   0x44 0xf4 0x31 0x1d 0x0d                   D.1..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 61 BolusWizard 2013-07-29T17:52:12 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 190,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 0,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 4.4,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 0}
```
    op hex (2)
    0000   0x5b 0xbe                                  [.
    decimal
             91  190
    datetime (2013-07-29T17:52:12)
    0000   0x4c 0xf4 0x11 0x7d 0x0d                   L..}.
    body (15)
    hex
    0000   0x00 0x50 0x00 0x64 0x3c 0x64 0x2c 0x00    .P.d<d,.
    0008   0x00 0x00 0x00 0x00 0x00 0x2c 0x78         .....,x
    decimal
              0   80    0  100   60  100   44    0
              0    0    0    0    0   44  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 62 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 73, 'amount': 2.6, 'curve': 208},
 {'age': 133, 'amount': 1.2, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x68 0x49 0xd0 0x30 0x85 0xd0    \.hI.0..
    decimal
             92    8  104   73  208   48  133  208
    datetime (unknown)

    body (0)

#### RECORD 63 Bolus 2013-07-29T17:52:12 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x2c 0x00 0x2c 0x00 0x00 0x00    ..,.,...
    decimal
              1    0   44    0   44    0    0    0
    datetime (2013-07-29T17:52:12)
    0000   0x4c 0xf4 0x51 0x7d 0x0d                   L.Q}.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 64 CalBGForPH 2013-07-29T22:16:26 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 129}
```
    op hex (2)
    0000   0x0a 0x81                                  ..
    decimal
             10  129
    datetime (2013-07-29T22:16:26)
    0000   0x5a 0xd0 0x36 0x1d 0x0d                   Z.6..
    body (0)
    HOUR BITS: [1, 1, 0]
#### RECORD 65 BolusWizard 2013-07-29T22:16:32 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 129,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 0.0,
 'carb_input': 18,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.4,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 72}
```
    op hex (2)
    0000   0x5b 0x81                                  [.
    decimal
             91  129
    datetime (2013-07-29T22:16:32)
    0000   0x60 0xd0 0x16 0x7d 0x0d                   `..}.
    body (15)
    hex
    0000   0x12 0x50 0x00 0x64 0x3c 0x64 0x04 0x00    .P.d<d..
    0008   0x48 0x00 0x00 0x00 0x00 0x4c 0x78         H....Lx
    decimal
             18   80    0  100   60  100    4    0
             72    0    0    0    0   76  120
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 66 UnabsorbedInsulinBolus unknown head[5], body[0] op[0x5c]
###### DECODED
```python
[{'age': 17, 'amount': 1.1, 'curve': 208}]
```
    op hex (5)
    0000   0x5c 0x05 0x2c 0x11 0xd0                   \.,..
    decimal
             92    5   44   17  208
    datetime (unknown)

    body (0)

#### RECORD 67 Bolus 2013-07-29T22:16:32 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 7.6, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x4c 0x00 0x4c 0x00 0x00 0x00    ..L.L...
    decimal
              1    0   76    0   76    0    0    0
    datetime (2013-07-29T22:16:32)
    0000   0x60 0xd0 0x56 0x7d 0x0d                   `.V}.
    body (0)
    HOUR BITS: [1, 1, 0] DAY BITS: [0, 1, 1]
#### RECORD 68 CalBGForPH 2013-07-29T22:33:34 head[2], body[0] op[0x0a]
###### DECODED
```python
{'amount': 107}
```
    op hex (2)
    0000   0x0a 0x6b                                  .k
    decimal
             10  107
    datetime (2013-07-29T22:33:34)
    0000   0x62 0xe1 0x36 0x1d 0x0d                   b.6..
    body (0)
    HOUR BITS: [1, 1, 1]
#### RECORD 69 BolusWizard 2013-07-29T22:33:38 head[2], body[15] op[0x5b]
###### DECODED
```python
{'_byte[5]': 100,
 '_byte[7]': 0,
 'bg': 107,
 'bg_target_high': 0,
 'bg_target_low': 60,
 'bolus_estimate': 7.6,
 'carb_input': 11,
 'carb_ratio': 0,
 'correction_estimate': 0.4,
 'food_estimate': 0.0,
 'sensitivity': 100,
 'unabsorbed_insulin_count': '??',
 'unabsorbed_insulin_total': 0.0,
 'unknown_byte[10]': 0,
 'unknown_byte[8]': 44}
```
    op hex (2)
    0000   0x5b 0x6b                                  [k
    decimal
             91  107
    datetime (2013-07-29T22:33:38)
    0000   0x66 0xe1 0x16 0x7d 0x0d                   f..}.
    body (15)
    hex
    0000   0x0b 0x50 0x00 0x64 0x3c 0x64 0x00 0x00    .P.d<d..
    0008   0x2c 0x00 0x00 0x4c 0x00 0x2c 0x78         ,..L.,x
    decimal
             11   80    0  100   60  100    0    0
             44    0    0   76    0   44  120
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 70 UnabsorbedInsulinBolus unknown head[8], body[0] op[0x5c]
###### DECODED
```python
[{'age': 20, 'amount': 1.9, 'curve': 192},
 {'age': 34, 'amount': 1.1, 'curve': 208}]
```
    op hex (8)
    0000   0x5c 0x08 0x4c 0x14 0xc0 0x2c 0x22 0xd0    \.L..,".
    decimal
             92    8   76   20  192   44   34  208
    datetime (unknown)

    body (0)

#### RECORD 71 Bolus 2013-07-29T22:33:38 head[8], body[0] op[0x01]
###### DECODED
```python
{'amount': 0.0, 'dual_component': '??', 'programmed': 4.4, 'type': '??'}
```
    op hex (8)
    0000   0x01 0x00 0x2c 0x00 0x2c 0x00 0x4c 0x00    ..,.,.L.
    decimal
              1    0   44    0   44    0   76    0
    datetime (2013-07-29T22:33:38)
    0000   0x66 0xe1 0x56 0x7d 0x0d                   f.V}.
    body (0)
    HOUR BITS: [1, 1, 1] DAY BITS: [0, 1, 1]
#### RECORD 72 BasalProfileStart 2013-07-30T00:00:00 head[2], body[3] op[0x7b]

    op hex (2)
    0000   0x7b 0x00                                  {.
    decimal
            123    0
    datetime (2013-07-30T00:00:00)
    0000   0x40 0xc0 0x00 0x1e 0x0d                   @....
    body (3)
    hex
    0000   0x00 0x1d 0x00                             ...
    decimal
              0   29    0
    HOUR BITS: [1, 1, 0]
#### RECORD 73 MResultTotals 2013-07-30T00:00:00 head[5], body[3] op[0x07]

    op hex (5)
    0000   0x07 0x00 0x00 0x04 0xbc                   .....
    decimal
              7    0    0    4  188
    datetime (2013-07-30T00:00:00)
    0000   0x7d 0x8d                                  }.
    body (3)
    hex
    0000   0x00 0x00 0x00                             ...
    decimal
              0    0    0
    HOUR BITS: [1, 0, 0]
`end analysis/sarak/raw//ReadHistoryData-page-18.data: 74 records`
