# C 語言期中練習題 - 測資總整理 (標準化格式)

這份文件已針對自動化爬蟲優化，所有題目均採用標準表格格式。
**注意**：若 Output 包含 `\n`，請在程式中轉換為實際換行符號。

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

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `1 1 1 1 1 2 2 2 2 2 3 3 3 3 3 4 4 4 4 4 5 5 5 5 5` | `Row totals: 5 10 15 20 25\nColumn totals: 15 15 15 15 15` |
| 2 | `1 0 0 0 0 0 1 0 0 0 0 0 1 0 0 0 0 0 1 0 0 0 0 0 1` | `Row totals: 1 1 1 1 1\nColumn totals: 1 1 1 1 1` |
| 3 | `10 5 8 2 1 3 3 3 3 3 9 1 1 1 1 0 5 5 5 0 2 2 2 2 2` | `Row totals: 26 15 13 15 10\nColumn totals: 24 16 19 13 7` |
| 4 | `5 5 5 5 5 4 4 4 4 4 3 3 3 3 3 2 2 2 2 2 1 1 1 1 1` | `Row totals: 25 20 15 10 5\nColumn totals: 15 15 15 15 15` |
| 5 | `0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0` | `Row totals: 0 0 0 0 0\nColumn totals: 0 0 0 0 0` |
| 6 | `1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5 1 2 3 4 5` | `Row totals: 15 15 15 15 15\nColumn totals: 5 10 15 20 25` |
| 7 | `9 1 1 1 1 1 9 1 1 1 1 1 9 1 1 1 1 1 9 1 1 1 1 1 9` | `Row totals: 13 13 13 13 13\nColumn totals: 13 13 13 13 13` |
| 8 | `2 4 6 8 10 1 3 5 7 9 2 4 6 8 10 1 3 5 7 9 2 4 6 8 10` | `Row totals: 30 25 30 25 30\nColumn totals: 8 18 28 38 48` |
| 9 | `10 10 10 10 10 20 20 20 20 20 5 5 5 5 5 1 1 1 1 1 0 0 0 0 0` | `Row totals: 50 100 25 5 0\nColumn totals: 36 36 36 36 36` |
| 10 | `1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 1` | `Row totals: 3 2 3 2 3\nColumn totals: 3 2 3 2 3` |

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
**格式**: `Message` (空白) `Shift`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `abc 1` | `bcd` |
| 2 | `Hello 13` | `Uryyb` |
| 3 | `Zoo 1` | `App` |
| 4 | `XYZ 3` | `ABC` |
| 5 | `Attack 5` | `Fyyfhp` |
| 6 | `C 2` | `E` |
| 7 | `Caesar 10` | `Mkcckb` |
| 8 | `Secret 25` | `Rdbqds` |
| 9 | `IBM 25` | `HAL` |
| 10 | `A 25` | `Z` |
| 11 | `Encryption 4` | `Irgvctxmsr` |
| 12 | `Linux 7` | `Spube` |
| 13 | `Windows 1` | `Xjoepxt` |
| 14 | `Apple 1` | `Bqqmf` |
| 15 | `Google 1` | `Hpphmf` |
| 16 | `Return 1` | `Sfuvso` |
| 17 | `Go 3` | `Jr` |
| 18 | `Help 5` | `Mjqu` |
| 19 | `Test 2` | `Vguv` |
| 20 | `Final 6` | `Lotgr` |

*(註：為簡化爬蟲邏輯，此題輸入調整為單字+位移，若需完整句子請確保爬蟲能正確切割)*

---

## #05: Anagrams (變位字)
**格式**: `Word1` (空白) `Word2`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `listen\nsilent` | `The words are anagrams.` |
| 2 | `triangle\nintegral` | `The words are anagrams.` |
| 3 | `apple\npapel` | `The words are anagrams.` |
| 4 | `hello\nworld` | `The words are not anagrams.` |
| 5 | `rat\ncar` | `The words are not anagrams.` |
| 6 | `evil\nvile` | `The words are anagrams.` |
| 7 | `book\nkobo` | `The words are anagrams.` |
| 8 | `test\nsett` | `The words are anagrams.` |
| 9 | `abc\nabd` | `The words are not anagrams.` |
| 10 | `dormitory\ndirtyroom` | `The words are anagrams.` |
| 11 | `school\nhools` | `The words are not anagrams.` |
| 12 | `astronomer\nmoonstarrer` | `The words are anagrams.` |
| 13 | `a\na` | `The words are anagrams.` |
| 14 | `a\nb` | `The words are not anagrams.` |
| 15 | `aa\na` | `The words are not anagrams.` |
| 16 | `cinema\niceman` | `The words are anagrams.` |
| 17 | `binary\nbrainy` | `The words are anagrams.` |
| 18 | `adobe\nabode` | `The words are anagrams.` |
| 19 | `logic\nlogin` | `The words are not anagrams.` |
| 20 | `coffee\ntoffee` | `The words are not anagrams.` |

---

## #06: Average (3 numbers)
**格式**: `Num1` `Num2` `Num3`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `1 2 3` | `2.00` |
| 2 | `2 4 6` | `4.00` |
| 3 | `1 1 2` | `1.33` |
| 4 | `10 20 30` | `20.00` |
| 5 | `0 0 0` | `0.00` |
| 6 | `5 5 5` | `5.00` |
| 7 | `1 3 5` | `3.00` |
| 8 | `100 0 0` | `33.33` |
| 9 | `-5 5 0` | `0.00` |
| 10 | `1 1 10` | `4.00` |
| 11 | `2 3 4` | `3.00` |
| 12 | `10 10 11` | `10.33` |
| 13 | `7 8 9` | `8.00` |
| 14 | `2 2 10` | `4.67` |
| 15 | `0 10 20` | `10.00` |
| 16 | `9 9 10` | `9.33` |
| 17 | `15 25 35` | `25.00` |
| 18 | `3 3 4` | `3.33` |
| 19 | `8 2 2` | `4.00` |
| 20 | `50 50 51` | `50.33` |

---

## #07: Max Value (2 numbers)
**格式**: `Num1` `Num2`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `1 2` | `2` |
| 2 | `10 5` | `10` |
| 3 | `-1 -5` | `-1` |
| 4 | `0 10` | `10` |
| 5 | `5 5` | `5` |
| 6 | `100 99` | `100` |
| 7 | `50 1000` | `1000` |
| 8 | `2 1` | `2` |
| 9 | `-10 0` | `0` |
| 10 | `3 7` | `7` |
| 11 | `100 100` | `100` |
| 12 | `-50 -40` | `-40` |
| 13 | `123 456` | `456` |
| 14 | `9 8` | `9` |
| 15 | `101 102` | `102` |
| 16 | `1 0` | `1` |
| 17 | `-1 1` | `1` |
| 18 | `999 1000` | `1000` |
| 19 | `25 20` | `25` |
| 20 | `77 88` | `88` |

---

## #08: Sum of Array
**格式**: `N` `Num1` `Num2`...

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `3 1 2 3` | `6` |
| 2 | `2 10 20` | `30` |
| 3 | `5 1 1 1 1 1` | `5` |
| 4 | `1 100` | `100` |
| 5 | `4 10 -10 5 -5` | `0` |
| 6 | `3 0 0 0` | `0` |
| 7 | `3 5 10 15` | `30` |
| 8 | `2 -5 -5` | `-10` |
| 9 | `4 1 2 3 4` | `10` |
| 10 | `5 2 4 6 8 10` | `30` |
| 11 | `6 1 2 3 4 5 6` | `21` |
| 12 | `3 100 200 300` | `600` |
| 13 | `2 0 1` | `1` |
| 14 | `4 2 2 2 2` | `8` |
| 15 | `5 -1 -2 -3 -4 -5` | `-15` |
| 16 | `1 0` | `0` |
| 17 | `3 33 33 33` | `99` |
| 18 | `2 50 -50` | `0` |
| 19 | `4 1 0 1 0` | `2` |
| 20 | `5 10 1 1 1 1` | `14` |

---

## #09: Square of Asterisks
**格式**: `N` (Output 包含換行符號 `\n`)

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `1` | `*` |
| 2 | `2` | `**\n**` |
| 3 | `3` | `***\n***\n***` |
| 4 | `4` | `****\n****\n****\n****` |
| 5 | `5` | `*****\n*****\n*****\n*****\n*****` |
| 6 | `6` | `******\n******\n******\n******\n******\n******` |
| 7 | `7` | `*******\n*******\n*******\n*******\n*******\n*******\n*******` |
| 8 | `8` | `********\n********\n********\n********\n********\n********\n********\n********` |
| 9 | `9` | `*********\n*********\n*********\n*********\n*********\n*********\n*********\n*********\n*********` |
| 10 | `10` | `**********\n**********\n**********\n**********\n**********\n**********\n**********\n**********\n**********\n**********` |

---

## #10: Max/Min Items (Top 2)
**格式**: `N` `Num1` `Num2`...

| No. | Input | Output |
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
**格式**: `x`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `0` | `-6` |
| 2 | `1` | `0` |
| 3 | `-1` | `-10` |
| 4 | `2` | `88` |
| 5 | `-2` | `-24` |
| 6 | `10` | `314564` |
| 7 | `3` | `675` |
| 8 | `-3` | `453` |
| 9 | `4` | `3270` |
| 10 | `-4` | `-2290` |
| 11 | `5` | `10004` |
| 12 | `-5` | `-7566` |
| 13 | `6` | `24840` |
| 14 | `-6` | `-19740` |
| 15 | `7` | `53502` |
| 16 | `-7` | `-44008` |
| 17 | `8` | `103922` |
| 18 | `-8` | `-87678` |
| 19 | `9` | `186600` |
| 20 | `-9` | `-160530` |

---

## #12: Fibonacci
**格式**: `n`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `0` | `1` |
| 2 | `1` | `1` |
| 3 | `2` | `2` |
| 4 | `3` | `3` |
| 5 | `4` | `5` |
| 6 | `5` | `8` |
| 7 | `6` | `13` |
| 8 | `7` | `21` |
| 9 | `8` | `34` |
| 10 | `9` | `55` |
| 11 | `10` | `89` |
| 12 | `11` | `144` |
| 13 | `12` | `233` |
| 14 | `13` | `377` |
| 15 | `14` | `610` |
| 16 | `15` | `987` |
| 17 | `16` | `1597` |
| 18 | `17` | `2584` |
| 19 | `18` | `4181` |
| 20 | `19` | `6765` |

---

## #13: Guess the Number
**格式**: `Secret` (空格) `Guess1` `Guess2`...

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `500 250 750 500` | `Too-low\nToo-high\nSuccess` |
| 2 | `10 5 10` | `Too-low\nSuccess` |
| 3 | `1 1` | `Success` |
| 4 | `1000 2000 900 1000` | `x\nToo-low\nSuccess` |
| 5 | `50 100 25 50` | `Too-high\nToo-low\nSuccess` |
| 6 | `777 500 800 777` | `Too-low\nToo-high\nSuccess` |
| 7 | `123 100 120 123` | `Too-low\nToo-low\nSuccess` |
| 8 | `999 1000 999` | `Success` |
| 9 | `50 -50 50` | `x\nSuccess` |
| 10 | `2 1 3 2` | `Too-low\nToo-high\nSuccess` |
| 11 | `88 90 80 88` | `Too-high\nToo-low\nSuccess` |
| 12 | `200 100 300 200` | `Too-low\nToo-high\nSuccess` |
| 13 | `555 550 560 555` | `Too-low\nToo-high\nSuccess` |
| 14 | `30 40 30` | `Too-high\nSuccess` |
| 15 | `100 -1 100` | `x\nSuccess` |
| 16 | `10 11 9 10` | `Too-high\nToo-low\nSuccess` |
| 17 | `250 200 250` | `Too-low\nSuccess` |
| 18 | `900 950 900` | `Too-high\nSuccess` |
| 19 | `60 50 70 60` | `Too-low\nToo-high\nSuccess` |
| 20 | `42 40 45 42` | `Too-low\nToo-high\nSuccess` |

---

## #15: Poker Hand Classification
**格式**: `5 Cards`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `2h 3h 4h 5h 6h` | `Type1` |
| 2 | `tc jc qc kc ac` | `Type1` |
| 3 | `5s 5h 5d 5c 9s` | `Type2` |
| 4 | `2h 2d 2s 2c 3h` | `Type2` |
| 5 | `3s 3h 3d 9s 9c` | `Type3` |
| 6 | `ts th td 2s 2c` | `Type3` |
| 7 | `2h 5h 9h jh kh` | `Type4` |
| 8 | `as 3s 5s 7s 9s` | `Type4` |
| 9 | `2s 3h 4d 5c 6s` | `Type5` |
| 10 | `th jd qs kd ac` | `Type5` |
| 11 | `5s 5h 5d 9c 2s` | `Type6` |
| 12 | `kh ks kd 2c 3h` | `Type6` |
| 13 | `5s 5h 9c 9s 2d` | `Type7` |
| 14 | `as ac 2d 2h 5s` | `Type7` |
| 15 | `5s 5h 2d 8c 9s` | `Type8` |
| 16 | `ks kh 2d 3c 4s` | `Type8` |
| 17 | `2h 5s 7d 9c kh` | `Type9` |
| 18 | `as 3h 5d 7c 9h` | `Type9` |
| 19 | `5s 5s 2h 3d 4c` | `Type10` |
| 20 | `1s 2h 3d 4c 5s` | `Type11` |
| 21 | `2x 3h 4d 5c 6s` | `Type11` |

---

## #17: Max_Min Function (10 numbers)
**格式**: `10 Ints`

| No. | Input | Output |
| :--- | :--- | :--- |
| 1 | `34 82 49 102 7 94 23 11 50 31` | `Largest: 102\nSmallest: 7` |
| 2 | `1 2 3 4 5 6 7 8 9 10` | `Largest: 10\nSmallest: 1` |
| 3 | `10 9 8 7 6 5 4 3 2 1` | `Largest: 10\nSmallest: 1` |
| 4 | `0 0 0 0 0 0 0 0 0 0` | `Largest: 0\nSmallest: 0` |
| 5 | `5 5 5 5 5 5 5 5 5 5` | `Largest: 5\nSmallest: 5` |
| 6 | `-1 -2 -3 -4 -5 -6 -7 -8 -9 -10` | `Largest: -1\nSmallest: -10` |
| 7 | `100 -100 50 -50 25 -25 10 -10 5 -5` | `Largest: 100\nSmallest: -100` |
| 8 | `12 56 34 89 10 23 45 67 90 1` | `Largest: 90\nSmallest: 1` |
| 9 | `99 2 45 101 3 8 77 66 55 44` | `Largest: 101\nSmallest: 2` |
| 10 | `5 2 8 1 9 3 7 4 6 0` | `Largest: 9\nSmallest: 0` |
| 11 | `1000 1 1 1 1 1 1 1 1 1` | `Largest: 1000\nSmallest: 1` |
| 12 | `1 1 1 1 1 1 1 1 1 1000` | `Largest: 1000\nSmallest: 1` |
| 13 | `-500 0 0 0 0 0 0 0 0 0` | `Largest: 0\nSmallest: -500` |
| 14 | `0 0 0 0 0 0 0 0 0 -500` | `Largest: 0\nSmallest: -500` |
| 15 | `10 20 30 40 50 10 20 30 40 50` | `Largest: 50\nSmallest: 10` |
| 16 | `3 1 4 1 5 9 2 6 5 3` | `Largest: 9\nSmallest: 1` |
| 17 | `999 -999 888 -888 777 -777 0 0 1 1` | `Largest: 999\nSmallest: -999` |
| 18 | `1 2 3 4 5 5 4 3 2 1` | `Largest: 5\nSmallest: 1` |
| 19 | `42 42 42 42 42 0 42 42 42 42` | `Largest: 42\nSmallest: 0` |
| 20 | `0 0 0 0 0 99 0 0 0 0` | `Largest: 99\nSmallest: 0` |

---

## #18: Reverse Array (Pointer Version)
**格式**: `10 Ints`

| No. | Input | Output |
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