# C 語言期中練習題 - 測資總整理

這份文件包含了從 #01 到 #18 題的測資。
每題均包含 10~20 組測試案例，方便除錯與驗證程式邏輯。

---

## #01: B1FF Filter
**規則**: 轉大寫, A->4, B->8, E->3, I->1, O->0, S->5, 句尾加 10 個驚嘆號。

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `Hello World` | `H3LL0 W0RLD!!!!!!!!!!` |
| 2 | `C programming is fun` | `C PR0GR4MM1NG 15 FUN!!!!!!!!!!` |
| 3 | `Be seeing you` | `83 5331NG Y0U!!!!!!!!!!` |
| 4 | `As soon as possible` | `45 500N 45 P05518L3!!!!!!!!!!` |
| 5 | `I like big buffers` | `1 L1K3 81G 8UFF3R5!!!!!!!!!!` |
| 6 | `She sells sea shells` | `5H3 53LL5 534 5H3LL5!!!!!!!!!!` |
| 7 | `Objective C is old` | `08J3CT1V3 C 15 0LD!!!!!!!!!!` |
| 8 | `Pointer arithmetic` | `P01NT3R 4R1THM3T1C!!!!!!!!!!` |
| 9 | `Segmentation fault` | `53GM3NT4T10N F4ULT!!!!!!!!!!` |
| 10 | `Stack overflow` | `5T4CK 0V3RFL0W!!!!!!!!!!` |
| 11 | `Base case recursion` | `8453 C453 R3CUR510N!!!!!!!!!!` |
| 12 | `Binary search tree` | `81N4RY 534RCH TR33!!!!!!!!!!` |
| 13 | `Boolean logic` | `800L34N L0G1C!!!!!!!!!!` |
| 14 | `Access denied` | `4CC355 D3N13D!!!!!!!!!!` |
| 15 | `System failure` | `5Y5T3M F41LUR3!!!!!!!!!!` |
| 16 | `Please reboot now` | `PL3453 R3800T N0W!!!!!!!!!!` |
| 17 | `Save your code` | `54V3 Y0UR C0D3!!!!!!!!!!` |
| 18 | `Debug looks good` | `D38UG L00K5 G00D!!!!!!!!!!` |
| 19 | `Create a list` | `CR34T3 4 L15T!!!!!!!!!!` |
| 20 | `Submit assignment` | `5U8M1T 4551GNM3NT!!!!!!!!!!` |

---

## #02: 5x5 Array Sums
**格式**: `Input (25個整數)` -> `Output (Row totals / Col totals)`

1. **In:** `1 1 1 1 1 2 2 2 2 2 3 3 3 3 3 4 4 4 4 4 5 5 5 5 5`
   **Out:** Rows: `5 10 15 20 25` | Cols: `15 15 15 15 15`
2. **In:** `1 0 0 0 0 0 1 0 0 0 0 0 1 0 0 0 0 0 1 0 0 0 0 0 1`
   **Out:** Rows: `1 1 1 1 1` | Cols: `1 1 1 1 1`
3. **In:** `10 5 8 2 1 3 3 3 3 3 9 1 1 1 1 0 5 5 5 0 2 2 2 2 2`
   **Out:** Rows: `26 15 13 15 10` | Cols: `24 16 19 13 7`
4. **In:** `5 5 5 5 5 4 4 4 4 4 3 3 3 3 3 2 2 2 2 2 1 1 1 1 1`
   **Out:** Rows: `25 20 15 10 5` | Cols: `15 15 15 15 15`
5. **In:** `0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0`
   **Out:** Rows: `0 0 0 0 0` | Cols: `0 0 0 0 0`
6. **In:** `1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5`
   **Out:** Rows: `15 15 15 15 15` | Cols: `5 10 15 20 25`
7. **In:** `9 1 1 1 1 1 9 1 1 1 1 1 9 1 1 1 1 1 9 1 1 1 1 1 9`
   **Out:** Rows: `13 13 13 13 13` | Cols: `13 13 13 13 13`
8. **In:** `2 4 6 8 10 1 3 5 7 9 2 4 6 8 10 1 3 5 7 9 2 4 6 8 10`
   **Out:** Rows: `30 25 30 25 30` | Cols: `8 18 28 38 48`
9. **In:** `10 10 10 10 10 20 20 20 20 20 5 5 5 5 5 1 1 1 1 1 0 0 0 0 0`
   **Out:** Rows: `50 100 25 5 0` | Cols: `36 36 36 36 36`
10. **In:** `1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1`
    **Out:** Rows: `3 2 3 2 3` | Cols: `3 2 3 2 3`

---

## #03: Reverse Words
**規則**: 翻轉單字，標點符號保留。

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `Hello world!` | `world Hello!` |
| 2 | `This is a test.` | `test a is This.` |
| 3 | `C is powerful.` | `powerful is C.` |
| 4 | `Do not panic!` | `panic not Do!` |
| 5 | `I love coding?` | `coding love I?` |
| 6 | `One two three four.` | `four three two One.` |
| 7 | `A B C D E.` | `E D C B A.` |
| 8 | `Keep it simple stupid.` | `stupid simple it Keep.` |
| 9 | `To be or not to be?` | `be to not or be To?` |
| 10 | `May the force be with you.` | `you with be force the May.` |
| 11 | `Winter is coming.` | `coming is Winter.` |
| 12 | `I have a dream.` | `dream a have I.` |
| 13 | `Just do it!` | `it do Just!` |
| 14 | `Show me the money.` | `money the me Show.` |
| 15 | `Houston we have a problem.` | `problem a have we Houston.` |
| 16 | `Life is short.` | `short is Life.` |
| 17 | `Time flies fast.` | `fast flies Time.` |
| 18 | `Never give up!` | `up give Never!` |
| 19 | `Knowledge is power.` | `power is Knowledge.` |
| 20 | `Coding requires logic.` | `logic requires Coding.` |

---

## #04: Caesar Cipher (凱撒密碼)
**格式**: `Message` + `Shift` -> `Encrypted`

| No. | Input Message | Shift | Output |
| :--- | :--- | :--- | :--- |
| 1 | `abc` | `1` | `bcd` |
| 2 | `Hello` | `13` | `Uryyb` |
| 3 | `Zoo` | `1` | `App` |
| 4 | `XYZ` | `3` | `ABC` |
| 5 | `Attack at dawn` | `5` | `Fyyfhp fy ifbs` |
| 6 | `C programming` | `2` | `E rtqitcookpi` |
| 7 | `Caesar` | `10` | `Mkcckb` |
| 8 | `Secret` | `25` | `Rdbqds` |
| 9 | `IBM` | `25` | `HAL` |
| 10 | `A` | `25` | `Z` |
| 11 | `Encryption` | `4` | `Irgvctxmsr` |
| 12 | `Linux` | `7` | `Spube` |
| 13 | `Windows` | `1` | `Xjoepxt` |
| 14 | `Apple` | `1` | `Bqqmf` |
| 15 | `Google` | `1` | `Hpphmf` |
| 16 | `Return 0` | `1` | `Sfuvso 0` |
| 17 | `Go back` | `3` | `Jr edfn` |
| 18 | `Help me` | `5` | `Mjqu rj` |
| 19 | `Test case` | `2` | `Vguv ecug` |
| 20 | `Final one` | `6` | `Lotgr utk` |

---

## #05: Anagrams (變位字)
**Output**: Yes / No

| No. | Input 1 | Input 2 | Output |
| :--- | :--- | :--- | :--- |
| 1 | `listen` | `silent` | **Yes** |
| 2 | `triangle` | `integral` | **Yes** |
| 3 | `apple` | `papel` | **Yes** |
| 4 | `hello` | `world` | **No** |
| 5 | `rat` | `car` | **No** |
| 6 | `evil` | `vile` | **Yes** |
| 7 | `book` | `kobo` | **Yes** |
| 8 | `test` | `sett` | **Yes** |
| 9 | `abc` | `abd` | **No** |
| 10 | `dormitory` | `dirtyroom` | **Yes** |
| 11 | `school` | `hools` | **No** |
| 12 | `astronomer` | `moonstarrer` | **Yes** |
| 13 | `a` | `a` | **Yes** |
| 14 | `a` | `b` | **No** |
| 15 | `aa` | `a` | **No** |
| 16 | `cinema` | `iceman` | **Yes** |
| 17 | `binary` | `brainy` | **Yes** |
| 18 | `adobe` | `abode` | **Yes** |
| 19 | `logic` | `login` | **No** |
| 20 | `coffee` | `toffee` | **No** |

---

## #06: Average (3 numbers)
**Output**: 2 decimal places

| Input | Output |
| :--- | :--- |
| `1 2 3` | `2.00` |
| `2 4 6` | `4.00` |
| `1 1 2` | `1.33` |
| `10 20 30` | `20.00` |
| `0 0 0` | `0.00` |
| `5 5 5` | `5.00` |
| `1 3 5` | `3.00` |
| `100 0 0` | `33.33` |
| `-5 5 0` | `0.00` |
| `1 1 10` | `4.00` |
| `2 3 4` | `3.00` |
| `10 10 11` | `10.33` |
| `7 8 9` | `8.00` |
| `2 2 10` | `4.67` |
| `0 10 20` | `10.00` |
| `9 9 10` | `9.33` |
| `15 25 35` | `25.00` |
| `3 3 4` | `3.33` |
| `8 2 2` | `4.00` |
| `50 50 51` | `50.33` |

---

## #07: Max Value (2 numbers)

| Input | Output |
| :--- | :--- |
| `1 2` | `2` |
| `10 5` | `10` |
| `-1 -5` | `-1` |
| `0 10` | `10` |
| `5 5` | `5` |
| `100 99` | `100` |
| `50 1000` | `1000` |
| `2 1` | `2` |
| `-10 0` | `0` |
| `3 7` | `7` |
| `100 100` | `100` |
| `-50 -40` | `-40` |
| `123 456` | `456` |
| `9 8` | `9` |
| `101 102` | `102` |
| `1 0` | `1` |
| `-1 1` | `1` |
| `999 1000` | `1000` |
| `25 20` | `25` |
| `77 88` | `88` |

---

## #08: Sum of Array
**格式**: `N` (count), then `N` numbers -> `Sum`

| N | Numbers | Output (Sum) |
| :--- | :--- | :--- |
| 3 | `1 2 3` | `6` |
| 2 | `10 20` | `30` |
| 5 | `1 1 1 1 1` | `5` |
| 1 | `100` | `100` |
| 4 | `10 -10 5 -5` | `0` |
| 3 | `0 0 0` | `0` |
| 3 | `5 10 15` | `30` |
| 2 | `-5 -5` | `-10` |
| 4 | `1 2 3 4` | `10` |
| 5 | `2 4 6 8 10` | `30` |
| 6 | `1 2 3 4 5 6` | `21` |
| 3 | `100 200 300` | `600` |
| 2 | `0 1` | `1` |
| 4 | `2 2 2 2` | `8` |
| 5 | `-1 -2 -3 -4 -5` | `-15` |
| 1 | `0` | `0` |
| 3 | `33 33 33` | `99` |
| 2 | `50 -50` | `0` |
| 4 | `1 0 1 0` | `2` |
| 5 | `10 1 1 1 1` | `14` |

---

## #09: Square of Asterisks
**規則**: 輸入整數 n，輸出 n 行，每行 n 個 `*`。

**(注意: 請複製以下區塊內的內容以保持格式)**

**Input: `1`**
```text
*
```

**Input: `2`**
```text
**
**
```

**Input: `3`**
```text
***
***
***
```

**Input: `4`**
```text
****
****
****
****
```

**Input: `5`**
```text
*****
*****
*****
*****
*****
```

**Input: `6`**
```text
******
******
******
******
******
******
```

**Input: `7`**
```text
*******
*******
*******
*******
*******
*******
*******
```

**Input: `8`**
```text
********
********
********
********
********
********
********
********
```

**Input: `9`**
```text
*********
*********
*********
*********
*********
*********
*********
*********
*********
```

**Input: `10`**
```text
**********
**********
**********
**********
**********
**********
**********
**********
**********
**********
```

---

## #10: Max/Min Items (Top 2)
**規則**: 若 N<=4 輸出 Max Min；若 N>4 輸出 Max1 Max2 Min1 Min2。

| No. | Input (Total + Array) | Output |
| :--- | :--- | :--- |
| 1 | `5 1 2 3 4 5` | `5 4 1 2` |
| 2 | `4 1 2 3 4` | `4 1` |
| 3 | `6 10 1 9 2 8 3` | `10 9 1 2` |
| 4 | `3 5 1 9` | `9 1` |
| 5 | `5 -5 -1 -4 -2 -3` | `-1 -2 -5 -4` |
| 6 | `2 10 20` | `20 10` |
| 7 | `5 0 0 0 0 0` | `0 0 0 0` |
| 8 | `6 1 1 1 2 2 2` | `2 2 1 1` |
| 9 | `7 100 50 1 2 3 4 5` | `100 50 1 2` |
| 10 | `1 5` | `5 5` |
| 11 | `8 1 2 3 4 5 6 7 8` | `8 7 1 2` |
| 12 | `5 10 20 30 40 50` | `50 40 10 20` |
| 13 | `3 1 1 1` | `1 1` |
| 14 | `4 2 4 6 8` | `8 2` |
| 15 | `5 100 -100 50 -50 0` | `100 50 -100 -50` |
| 16 | `2 1 2` | `2 1` |
| 17 | `6 5 4 3 2 1 0` | `5 4 0 1` |
| 18 | `4 0 0 0 1` | `1 0` |
| 19 | `5 1 2 1 2 1` | `2 2 1 1` |
| 20 | `3 10 5 20` | `20 5` |

---

## #11: Polynomial
**公式**: `3x^5 + 2x^4 - 5x^3 - x^2 + 7x - 6`

| Input (x) | Output |
| :--- | :--- |
| `0` | `-6` |
| `1` | `0` |
| `-1` | `-10` |
| `2` | `88` |
| `-2` | `-24` |
| `10` | `314564` |
| `3` | `675` |
| `-3` | `453` |
| `4` | `3270` |
| `-4` | `-2290` |
| `5` | `10004` |
| `-5` | `-7566` |
| `6` | `24840` |
| `-6` | `-19740` |
| `7` | `53502` |
| `-7` | `-44008` |
| `8` | `103922` |
| `-8` | `-87678` |
| `9` | `186600` |
| `-9` | `-160530` |

---

## #12: Fibonacci
**Output**: Fn

| Input (n) | Output (Fn) |
| :--- | :--- |
| `0` | `1` |
| `1` | `1` |
| `2` | `2` |
| `3` | `3` |
| `4` | `5` |
| `5` | `8` |
| `6` | `13` |
| `7` | `21` |
| `8` | `34` |
| `9` | `55` |
| `10` | `89` |
| `11` | `144` |
| `12` | `233` |
| `13` | `377` |
| `14` | `610` |
| `15` | `987` |
| `16` | `1597` |
| `17` | `2584` |
| `18` | `4181` |
| `19` | `6765` |

---

## #13: Guess the Number
**格式**: `Secret` | `Guesses` | `Responses`

| Secret | Guesses Sequence | Responses Sequence |
| :--- | :--- | :--- |
| `500` | `250, 750, 500` | `Too-low, Too-high, Success` |
| `10` | `5, 10` | `Too-low, Success` |
| `1` | `1` | `Success` |
| `1000` | `2000, 900, 1000` | `x, Too-low, Success` |
| `50` | `100, 25, 50` | `Too-high, Too-low, Success` |
| `777` | `500, 800, 777` | `Too-low, Too-high, Success` |
| `123` | `100, 120, 123` | `Too-low, Too-low, Success` |
| `999` | `1000, 999` | `Success` |
| `50` | `x, 50` | `x, Success` |
| `2` | `1, 3, 2` | `Too-low, Too-high, Success` |
| `88` | `90, 80, 88` | `Too-high, Too-low, Success` |
| `200` | `100, 300, 200` | `Too-low, Too-high, Success` |
| `555` | `550, 560, 555` | `Too-low, Too-high, Success` |
| `30` | `40, 30` | `Too-high, Success` |
| `100` | `-1, 100` | `x, Success` |
| `10` | `11, 9, 10` | `Too-high, Too-low, Success` |
| `250` | `200, 250` | `Too-low, Success` |
| `900` | `950, 900` | `Too-high, Success` |
| `60` | `50, 70, 60` | `Too-low, Too-high, Success` |
| `42` | `40, 45, 42` | `Too-low, Too-high, Success` |

---

## #15: Poker Hand Classification
**Input**: 5 張牌 -> **Output**: Type

| No. | Input | Output (Type) | 說明 |
| :--- | :--- | :--- | :--- |
| 1 | `2h 3h 4h 5h 6h` | `Type1` | Straight Flush |
| 2 | `tc jc qc kc ac` | `Type1` | Straight Flush |
| 3 | `5s 5h 5d 5c 9s` | `Type2` | Four of a Kind |
| 4 | `2h 2d 2s 2c 3h` | `Type2` | Four of a Kind |
| 5 | `3s 3h 3d 9s 9c` | `Type3` | Full House |
| 6 | `ts th td 2s 2c` | `Type3` | Full House |
| 7 | `2h 5h 9h jh kh` | `Type4` | Flush |
| 8 | `as 3s 5s 7s 9s` | `Type4` | Flush |
| 9 | `2s 3h 4d 5c 6s` | `Type5` | Straight |
| 10 | `th jd qs kd ac` | `Type5` | Straight |
| 11 | `5s 5h 5d 9c 2s` | `Type6` | Three of a Kind |
| 12 | `kh ks kd 2c 3h` | `Type6` | Three of a Kind |
| 13 | `5s 5h 9c 9s 2d` | `Type7` | Two Pairs |
| 14 | `as ac 2d 2h 5s` | `Type7` | Two Pairs |
| 15 | `5s 5h 2d 8c 9s` | `Type8` | Pair |
| 16 | `ks kh 2d 3c 4s` | `Type8` | Pair |
| 17 | `2h 5s 7d 9c kh` | `Type9` | High Card |
| 18 | `as 3h 5d 7c 9h` | `Type9` | High Card |
| 19 | `5s 5s 2h 3d 4c` | `Type10` | Duplicate Card |
| 20 | `1s 2h 3d 4c 5s` | `Type11` | Bad Card (1s invalid) |
| 21 | `2x 3h 4d 5c 6s` | `Type11` | Bad Card (2x invalid) |

---

## #17: Max_Min Function (10 numbers)
**Output**: Max, Min

| No. | Input Sequence | Output |
| :--- | :--- | :--- |
| 1 | `34 82 49 102 7 94 23 11 50 31` | `Largest: 102`<br>`Smallest: 7` |
| 2 | `1 2 3 4 5 6 7 8 9 10` | `Largest: 10`<br>`Smallest: 1` |
| 3 | `10 9 8 7 6 5 4 3 2 1` | `Largest: 10`<br>`Smallest: 1` |
| 4 | `0 0 0 0 0 0 0 0 0 0` | `Largest: 0`<br>`Smallest: 0` |
| 5 | `5 5 5 5 5 5 5 5 5 5` | `Largest: 5`<br>`Smallest: 5` |
| 6 | `-1 -2 -3 -4 -5 -6 -7 -8 -9 -10` | `Largest: -1`<br>`Smallest: -10` |
| 7 | `100 -100 50 -50 25 -25 10 -10 5 -5` | `Largest: 100`<br>`Smallest: -100` |
| 8 | `12 56 34 89 10 23 45 67 90 1` | `Largest: 90`<br>`Smallest: 1` |
| 9 | `99 2 45 101 3 8 77 66 55 44` | `Largest: 101`<br>`Smallest: 2` |
| 10 | `5 2 8 1 9 3 7 4 6 0` | `Largest: 9`<br>`Smallest: 0` |
| 11 | `1000 1 1 1 1 1 1 1 1 1` | `Largest: 1000`<br>`Smallest: 1` |
| 12 | `1 1 1 1 1 1 1 1 1 1000` | `Largest: 1000`<br>`Smallest: 1` |
| 13 | `-500 0 0 0 0 0 0 0 0 0` | `Largest: 0`<br>`Smallest: -500` |
| 14 | `0 0 0 0 0 0 0 0 0 -500` | `Largest: 0`<br>`Smallest: -500` |
| 15 | `10 20 30 40 50 10 20 30 40 50` | `Largest: 50`<br>`Smallest: 10` |
| 16 | `3 1 4 1 5 9 2 6 5 3` | `Largest: 9`<br>`Smallest: 1` |
| 17 | `999 -999 888 -888 777 -777 0 0 1 1` | `Largest: 999`<br>`Smallest: -999` |
| 18 | `1 2 3 4 5 5 4 3 2 1` | `Largest: 5`<br>`Smallest: 1` |
| 19 | `42 42 42 42 42 0 42 42 42 42` | `Largest: 42`<br>`Smallest: 0` |
| 20 | `0 0 0 0 0 99 0 0 0 0` | `Largest: 99`<br>`Smallest: 0` |

---

## #18: Reverse Array (Pointer Version)
**Output**: In reverse order

| No. | Input Sequence | Output (Reverse Order) |
| :--- | :--- | :--- |
| 1 | `9283 -12 0 4444 823 1 99999 -55 3 2025` | `2025 3 -55 99999 1 823 4444 0 -12 9283` |
| 2 | `2147483647 -2147483648 0 1000000 999 1 -1 5566 7788 123` | `123 7788 5566 -1 1 999 1000000 0 -2147483648 2147483647` |
| 3 | `10 -10 20 -20 30 -30 40 -40 50 -50` | `-50 50 -40 40 -30 30 -20 20 -10 10` |
| 4 | `404 503 1337 42 666 888 777 9487 520 1314` | `1314 520 9487 777 888 666 42 1337 503 404` |
| 5 | `0 1 10 11 100 101 110 111 1000 1001` | `1001 1000 111 110 101 100 11 10 1 0` |
| 6 | `7 7 7 7 7 999 7 7 7 7` | `7 7 7 7 999 7 7 7 7 7` |
| 7 | `-1 -11 -111 -1111 -12345 -54321 -9 -99 -999 -9999` | `-9999 -999 -99 -9 -54321 -12345 -1111 -111 -11 -1` |
| 8 | `1 100 5 500 2 2000 9 90000 3 33` | `33 3 90000 9 2000 2 500 5 100 1` |
| 9 | `121 12321 55 88 1001 2002 303 404 11 22` | `22 11 404 303 2002 1001 88 55 12321 121` |
| 10 | `834 2 19 -4 0 91238 43 21 11 9` | `9 11 21 43 91238 0 -4 19 2 834` |