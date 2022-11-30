## Forensics
Chal Name: Corrupted Image

![image](https://user-images.githubusercontent.com/23289982/204716896-a1f71ea7-6fcd-4cc6-b052-92c5b6e060f1.png)

## Hint
what needs a signature

## Solution
* buka file corrupted image melalui [HxD Hex Editor](https://mh-nexus.de/en/hxd/)

![image](https://user-images.githubusercontent.com/23289982/204717545-dc15101a-7320-46a7-93e9-c13ecabde074.png)

* kita dapat tahu bahawa header dia ialah `SKR`
* apa yang kita nak buat ialah tukar header tersebut dengan `png`
* kita google sahaja `png hex file signature` seperti gambar di bawah

![image](https://user-images.githubusercontent.com/23289982/204718022-7e4f0395-3c83-47ce-87b5-3cea4a4ff798.png)

* kita tukar sahaja kepada hex png menggunakan hex editor dan save menggunakan extension `.png`
* setelah selesai save `.png` tersebut dan buka gambar terdapat satu puisi yang perlu di decode

![edit hex](https://user-images.githubusercontent.com/23289982/204718874-7af4db60-d4db-46a4-9c62-99fadeeb855f.png)

* hanya mengambil semua huruf besar dan cantumkan
* dan jengjengjeng dapat Flag
