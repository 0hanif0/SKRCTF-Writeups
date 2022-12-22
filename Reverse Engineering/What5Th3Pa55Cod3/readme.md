## Reverse Engineering
Chal Name: What5Th3Pa55Cod3

![image](https://user-images.githubusercontent.com/23289982/209090405-53ddf416-bb4e-46fa-9e3b-3a52ae1e8346.png)

## Hint
* You need a apk decompiler
* Whats the opposite of “Compile” ?

## Solution
* first download apk
* berdasarkan hint diberi ia memerlukan decompiler so aku pakai [jadx - Dex to Java decompiler](https://github.com/skylot/jadx)
* buka apk menggunakan decompiler tersebut
* di bawah adalah paparan decompiler tersebut

![image](https://user-images.githubusercontent.com/23289982/209092125-bc50266a-93b9-4f97-a767-6f6616e66cfc.png)

* pergi ke source code > com > kukigodam.secret > MainActivity
* kita boleh lihat `passcode` tersebut ialah `6666`
* kemudian kita pergi ke `Main2Activity` untuk lihat `birthcode`

![image](https://user-images.githubusercontent.com/23289982/209093078-450722ec-431d-48b0-b0cf-4e0392ebdea5.png)

* kita boleh lihat `birthcode` tersebut ialah `19971025`
* seterusnya kita perlu run apk tersebut untuk mengetahui kandungan secret
* aku menggunakan android emulator [LD Player](https://www.ldplayer.net) dan terpulang kepada korang nak run macam mana apk tersebut
* seterusnya aku buka apk tersebut

![image](https://user-images.githubusercontent.com/23289982/209093991-3b5529d2-5464-4d15-a89d-b2aab4a52520.png)

* letak `passcode` dan `birthcode` yang kita dapat tadi

![image](https://user-images.githubusercontent.com/23289982/209094192-3e15af50-1a43-43c8-8d26-5df927ac1fcf.png)

* jengjengjeng korang dah dapat buka secret apk tersebut

![image](https://user-images.githubusercontent.com/23289982/209094469-462bf9e4-19c8-4406-a91f-8e86803cdac4.png)
