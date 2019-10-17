# picoCTF 2019 Reverse Engineering

## vault-door-training
Your mission is to enter Dr. Evil's laboratory and retrieve the blueprints for his Doomsday Project. The laboratory is protected by a series of locked vault doors. Each door is controlled by a computer and requires a password to open. Unfortunately, our undercover agents have not been able to obtain the secret passwords for the vault doors, but one of our junior agents obtained the source code for each vault's computer! You will need to read the source code for each level to figure out what the password is for that vault door. As a warmup, we have created a replica vault in our training facility. The source code for the training vault is here: [VaultDoorTraining.java](./vault-door-training/VaultDoorTraining.java)

## vault-door-1
This vault uses some complicated arrays! I hope you can make sense of it, special agent. The source code for this vault is here: [VaultDoor1.java](./vault-door-1/VaultDoor1.java)

## vault-door-3
This vault uses for-loops and byte arrays. The source code for this vault is here: [VaultDoor3.java](./vault-door-3/VaultDoor3.java)

## vault-door-4
This vault uses ASCII encoding for the password. The source code for this vault is here: [VaultDoor4.java](./vault-door-4/VaultDoor4.java)

## vault-door-5
In the last challenge, you mastered octal (base 8), decimal (base 10), and hexadecimal (base 16) numbers, but this vault door uses a different change of base as well as URL encoding! The source code for this vault is here: [VaultDoor5.java](./vault-door-5/VaultDoor5.java)

## vault-door-6
This vault uses an XOR encryption scheme. The source code for this vault is here: [VaultDoor6.java](./vault-door-6/VaultDoor6.java)

## vault-door-7
This vault uses bit shifts to convert a password string into an array of integers. Hurry, agent, we are running out of time to stop Dr. Evil's nefarious plans! The source code for this vault is here: [VaultDoor7.java](./vault-door-7/VaultDoor7.java)

## vault-door-8
Apparently Dr. Evil's minions knew that our agency was making copies of their source code, because they intentionally sabotaged this source code in order to make it harder for our agents to analyze and crack into! The result is a quite mess, but I trust that my best special agent will find a way to solve it. The source code for this vault is here: [VaultDoor8.java](./vault-door-8/VaultDoor8.java)

## asm1
What does asm1(0x1f3) return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format. [Source](./asm1/test.S) located in the directory at /problems/asm1_2_4ced82d316c06cd3a46ba3bda9f6c144.

## asm2
What does asm2(0x10,0x18) return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format. [Source](./asm2/test.S) located in the directory at /problems/asm2_0_a50f0b17a6f50b50a53305ebd71af535.

## asm3
What does asm3(0xaeed09cb,0xb7acde91,0xb7facecd) return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format. [Source](./asm3/test.S) located in the directory at /problems/asm3_0_9cdf5fc9325b2a6276fb8e5908f0b5df.

## asm4
What will asm4("picoCTF_e341d") return? Submit the flag as a hexadecimal value (starting with '0x'). NOTE: Your submission for this question will NOT be in the normal flag format. [Source](./asm4/test.S) located in the directory at /problems/asm4_4_046c448fbb6c43457e9709d33d485bc2.

## droids0
Where do droid logs go. Check out this [file](./droids0/zero.apk). You can also find the file in /problems/droids0_0_205f7b4a3b23490adffddfcfc45a2ca3.

## droids1
Find the pass, get the flag. Check out this [file](./droids1/one.apk). You can also find the file in /problems/droids1_0_b7f94e21c7e45e6604972f9bc3f50e24.

## droids2
Find the pass, get the flag. Check out this [file](./droids2/two.apk). You can also find the file in /problems/droids2_0_bf474794b5a228db3498ba3198db54d7.

## reverse_cipher
We have recovered a [binary](./reverse_cipher/rev) and a [text file](./reverse_cipher/rev_this). Can you reverse the flag. Its also found in /problems/reverse-cipher_2_d8dc36eefa9dfce00eac3dab8f42513c on the shell server.

## Need For Speed
The name of the game is [speed](https://www.youtube.com/watch?v=8piqd2BWeGI). Are you quick enough to solve this problem and keep it above 50 mph? [need-for-speed](./Need%20For%20Speed/need-for-speed).

## Time's Up
Time waits for no one. Can you solve this before time runs out? [times-up](./Time's&#32;Up/times-up), located in the directory at /problems/time-s-up_1_7d4f79c3df3e1b044801573eea5722be.

## Time's Up, Again!
Previously you solved things fast. Now you've got to go faster. Much faster. Can you solve *this one* before time runs out? [times-up-again](./Time's&#32;Up,&#32;Again!/times-up-again), located in the directory at /problems/time-s-up--again-_5_54119090b1f81877d44974f305bc7051.
