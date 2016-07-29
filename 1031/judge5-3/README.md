﻿# NCNU Programming 1031 Judge 5–3

設計一個 function 來計算出 1-2+3-4… … +n，並印出過程。可愛又可口的煉乳剛上暨大資管系，程式設計課的老師是俞旭昇老師，是學長姐口中有名又可怕的大刀，老師在跨年前出了一個題目，叫同學們回去做。

聰明的 Mirase 為了解救煉乳的跨年作業，決定出手相助!!!

題目是這樣的：
設計一個 function 來計算出 1-2+3-4... ... +n,並印出過程。

## 輸入

輸入一整數為 n，n 需大於 0。

## 輸出

印出計算過程與結果。

## 要求

程式請遵照以下格式，以遞迴方式實作

```
int func(int curr, int n) { // curr 為目前計算到的值，n 為輸入值
    if(…) //終止條件
}

int main(){
}
```

### Sample 1

```
4
```

```
1 - 2 + 3 - 4  = -2
```

### Sample 2

```
10
```

```
1 - 2 + 3 - 4 + 5 - 6 + 7 - 8 + 9 - 10  = -5
```