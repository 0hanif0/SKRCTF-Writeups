## Steganography
Chal Name: A Thousand Words

![image](https://user-images.githubusercontent.com/23289982/208281547-ef3ec681-da17-4a4b-a081-a73de414c86a.png)

## Hint
Did you try "strings"? Or open in a hex editor?

## Solution
* download jpg
* strings jpg itu untuk lihat strings tersebut
* akan dapat 1 hint `/Hong5489/SKRCTF/blob/master/flag.jpg`
* gambar tersebut ialah github dan hint itu merujuk kepada link kepada github
* kita buka github tersebut dan akan bawa kesini

![image](https://user-images.githubusercontent.com/23289982/208281654-8054444b-3056-4af6-aff0-a2df6e6de90b.png)

* download gambar tersebut untuk lihat hint seterusnya
* strings gambar itu dan akan jumpa 1 code base64 `VlRCMFUyVXhUakJOTW1SMVRVZGtlVTVJUW05bFZqaDRUbFk1YWsxRVFuTkpXREJMQ2c9PQo=`
* base64 itu perlu decode [base64 decoder](https://www.base64decode.org) sebanyak 3 kali untuk dapat flag
* jengjengjeng dapat flag
