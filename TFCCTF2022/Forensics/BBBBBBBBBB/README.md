## BBBBBBBBBB

![Challenge Picture](./attachments/BBBBBBBBBB.png)

## Overview & Description

Author : hofill

Points : 50

BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB BBBBBBBBBB 

[chall.jpg](https://ctf.thefewchosen.com/attachments/2fa2dd09-9aba-4d41-a4a1-7bd6e4988111.jpg)

## Hints


## Step by Step

1. Diberikan sebuah image bernama chall.jpg, saat dibuka akan muncul error

![error](./attachments/error.png)

2. Buka menggunakan hex editor, disini saya menggunakan bless


3. Saat dibuka, saya berinisiatif mengecek SOI (Start of Image), dan EOI (End of Image), namun keduanya tidak salah

![bless](./attachments/bless.png)

4. Namun saya menyadari bahwa, ada string aneh yaitu "BBBBBBBBBB", disini saya langsung saja mengganti string tersebut dengan string kosong ("")

![replace](./attachments/replace.png)

5. Setelah di save, lalu saya membuka image tersebut, dan didapati flag didalam gambar tersebut
 
![flag](./attachments/flag.png)


## Flag

`TFCCTF{the_fl4g_1s_th3_w4y}`