# Trend Micro CTF 2019 - Notes

## 100


> Category: Mobile
> Points: 100
> Unlock My Phone

> My phone was remotely attacked and locked by a ransomware because of the opening ADB port, Can you unlock the device by analyzing Pcap that contains the attack traffic.

> Download the file
> Extract the downloaded file by using the following password.
> Optional: Check integrity of 7z file by comparing file SHA256 checksum.
> Command to check SHA256 checksum:
> Linux: sha256sum filename.7z
> Windows: certUtil -hashfile filename.7z SHA256


> Password: RGq6b7Mzia908Do1L9ax
> SHA256 Checksum: 8b0a7238ca653be9d5471f9890faa704a7e846a3c7972c5c20c00507651c1b1b


## 200

> Category: Mobile
> Points: 200
> Layers of Bug

> we got hacked

> we forgot important information on our server, we were able to get these binaries before we got disconnected

> case of two apk:

> browser.apk - you probably know there is hidden flag, but you don't have the updated version it is only on the server
> truead.apk - some unknown binary that you found on server
> The 2 apps are running now, device is not debug-enabled, not rooted, we know the device IP, but we have no physical interaction

> can you help us to retrieve the information back?

---

> For this challenge - you will be testing another important skill set for researchers - your ability to do technical write-ups of your work.

> Specifically - to obtain the flag, you will need to put together a detailed write-up of how you would need to solve the challenge (txt, Word, PDF, etc.) and submit it to us via email at the following address for validation: ctf2019mobile200@trendmicro.com and please remember to include your team name in the email for tracking purposes.

> Please note any additional attachments (up to 5MB total) should be zipped with a password shared in the email. Any attachments larger than 5MB total should be shared via a public cloud storage or file sharing solution of your choice.

> If your write-up is correct, you will receive the final correct flag via email reply that will need to be entered into the score server to obtain points.

---

> Correct examples of a valid solution would include (but not limited to):

> nc DeviceIP 9999
> or

> python exp.py Device_IP 9999
> Wrong example:

> Any physical interactions with the target device, including but not limited to eye-sight, sound, hand-touch, just because we can not
> Download the file
> Extract the downloaded file by using the following password.
> Optional: Check integrity of 7z file by comparing file SHA256 checksum.
> Command to check SHA256 checksum:
> Linux: sha256sum filename.7z
> Windows: certUtil -hashfile filename.7z SHA256


> Password: 61madWcc3nH6OczEvtDc
> SHA256 Checksum: 277475dad31fd6fbf8677f1ca0a7a7238e7f12bd69cd114794ed03995931f338



## 300


> Category: Mobile
> Points: 300
> Mommy, where is my key?

> Hey my friends, please help me to find my key.

> Download the file
> Extract the downloaded file by using the following password.
> Optional: Check integrity of 7z file by comparing file SHA256 checksum.
> Command to check SHA256 checksum:
> Linux: sha256sum filename.7z
> Windows: certUtil -hashfile filename.7z SHA256


> Password: 4QBZRfhTZ6NIqXhxpM2r
> SHA256 Checksum: bb5a54b6db7800d1ec58ff42079d6686e274af78cea82493af66b345a1b27769

## 400

> Category: Mobile
> Points: 400
> qemu-system-aarch64 runs in the linux x64 enviroment.

---

> Similar to the earlier Mobile 200 challenge, this challenge also requires a manual technical write-up in addition to coding to receive the correct flag.

> Players will need to put together a detailed write-up of how you would need to solve the challenge (txt, Word, PDF, etc.) as well as compiled code and submit it to us via email at the following address for validation: ctf2019mobile400@trendmicro.com and please remember to include your team name in the email for tracking purposes.

> If your write-up is correct, you will receive the final correct flag via email reply that will need to be entered into the score server to obtain points.

> Please note any code attachments (up to 5MB total) should be zipped with a password shared in the email. Any attachments larger than 5MB total should be shared via a public cloud storage or file sharing solution of your choice.


***
> Some important points before you email a submission:
> 1.You must analyze the helper.ko file find the real vulnerability.

> 2.You must use helper.ko vulnerability to gain root privileges of the emulator.

> 3.The flag is located in the /flag.txt.

> 4.Please write the ndk executable program to use exploit to get the answer.

***

> There are further instructions in the READMEFIRST.txt file contained in the challenge package. Please be sure to read this file first!

> If there is an additional password on the embedded files.zip challenge package file, please use novirusoftmctf

> Download the file
> Extract the downloaded file by using the following password.
> Optional: Check integrity of 7z file by comparing file SHA256 checksum.
> Command to check SHA256 checksum:
> Linux: sha256sum filename.7z
> Windows: certUtil -hashfile filename.7z SHA256


> Password: bTIhkOXv52JtbPuMRahc
> SHA256 Checksum: 188ed7764c87fc1cb6c798c90fdb262f3ffc8317228e3fa7340564a7c21bbaff


> HINT 1: It is the bug uaf(use after free).
> If you would like to debug the kernel, download both gdb and gdb-orig of aarch64 platform on the internet to debug the kernel.
> The odds are small but not impossible that players failed to start emulator with errors about the libqt5widgets5.so, then execute the command `sudo apt-get install libqt5widgets5` in local linux environment.
>
> 檔案下載: https://drive.google.com/file/d/1uF48KkMij0oYqwNUvY_Wm4QitDOMQ0wX/view?usp=sharing

