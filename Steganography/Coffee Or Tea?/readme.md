## Steganography
Chal Name: Coffee Or Tea?
 
![image](https://user-images.githubusercontent.com/23289982/209130886-57cfd40f-211a-4f42-b542-20e38abd9bda.png)

## Hint
* True or false is the key to find the flag
* Can text be written in number format?

## Solution
* download file zip tersebut dan dalam file tersebut terdapat hints
* berdasarkan hints tersebut kemungkinan binary
* di gambar tersebut terdapat beberapa gambar yang kecil dan susunan ayat yang tidak lengkap
* susunan gambar kecil itu disusun mengikut 8 gambar secara rapat
* ini kemungkinan binary 8 bit

![image](https://user-images.githubusercontent.com/23289982/209132083-b69eba19-bf8a-4570-8235-8f8c36d3a6cf.png)

* seterusnya aku zoom dan kenal pasti kesemua gambar tersebut ialah coffee atau tea
* aku membuat formula `coffee = 1 dan tea = 0`
* setelah decode ini hasilnya `SKR{I_w 00110000 01110101 01001100 01000100 _pRe 01100110 00110011 01110010 _c 00110000 01000110 01000110 01000101 01000101 ee}`
* binary tersebut aku convert kepada text guna [convert](https://www.rapidtables.com/convert/number/binary-to-ascii.html)
* jengjengjeng dah dapat flag
