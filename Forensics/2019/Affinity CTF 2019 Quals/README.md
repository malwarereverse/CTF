# Affinity CTF 2019 Quals - Notes 

## Reflection
> Description:
>
> 沒描述

直接用 binwalk 可以看到裡面藏有東西

```
root@lubun1604:/tmp/p# binwalk task.gif

DECIMAL       HEXADECIMAL     DESCRIPTION
--------------------------------------------------------------------------------
0             0x0             GIF image data, version "89a", 480 x 480
285539        0x45B63         gzip compressed data, from Unix, NULL date (1970-01-01 00:00:00)
285695        0x45BFF         GIF image data, version "89a", 540 x 283
491472        0x77FD0         gzip compressed data, from Unix, NULL date (1970-01-01 00:00:00)

```

直接用 binwalk 拉
```
$ binwalk -e task.gif
```

會得到 tar 壓縮檔 ，解壓縮就是答案


## Man In the Middle
> Description:
>
> Note: put flag into AFFCTF{} format.







## Pharmacist Nightmare
> Description:
>
> Our malware intercepted traffic from one of drugstore computers. Can you find prescription?

---
> Hint:
>
> ... i need your signature Sir..... here under prescription please...



## Falling into Spiral
> Description:
>
> no

## Stegoego
> Description:
>
> no

## Alphinity
> Description:
>
> Welcome


## XY_FUN
> Description:
>
> Note: put flag into AFFCTF{} format



## sQRt(follow the white rabbit)
> Description:
>
> no

## Intensity Overload
> Description:
>
> https://www.youtube.com/watch?v=7xxgRUyzgs0

> Note: put flag into AFFCTF{} format.









