## Web
Chal Name : Forgot Password 2

![image](https://user-images.githubusercontent.com/23289982/205421356-e5b16d2a-f73b-41ee-974c-be856d6dd86d.png)

## Hint
What is [Password Hashing?](https://www.theguardian.com/technology/2016/dec/15/passwords-hacking-hashing-salting-sha-2)

## Solution
* view page source, 
* pergi ke `static/login.js`
* login credentials `if (user == "godam" && MD5(pass) == "6a6360e517586fee8d2efc01ec9fd801") `
* tapi password hash kena guna [crackstation](https://crackstation.net)

