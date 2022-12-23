## Web
Chal Name: Dot Dot Slash

![image](https://user-images.githubusercontent.com/23289982/209268037-db474b1f-bf9d-4879-b3ff-006a721c09b2.png)

## Hint
What is [Directory Traversal?](https://portswigger.net/web-security/file-path-traversal)

## Solution
* download source code file yang diberi dan extract
* buka file `setup.sh` terdapat hint flag berada di flag.txt

![image](https://user-images.githubusercontent.com/23289982/209268280-894fe280-23bb-4a2a-a7d6-ebbfffd25169.png)

* buka web tersebut dan aku muiakan directory traversal cmd seperti berikut `/../flag.txt` di url web itu
* dan ini hasil error yang dapat

![image](https://user-images.githubusercontent.com/23289982/209268654-4ea0a3b3-ddae-4edb-957b-e76cf2251772.png)

* mengikut error tersebut kemungkinan `../` sudah ditapis dan tidak dapat pergi
* cara seterusnya aku guna [url encoding](https://www.urlencoder.org) dan encode `../` tersebut
* akan dapat `..%2F` setelah url encoding
* seterusnya kita cuba menggunakan url encoding tersebut
* ini cmd `/..%2Fflag.txt`
* jengjengjeng sudah dapat flag
