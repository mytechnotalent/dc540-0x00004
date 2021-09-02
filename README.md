![image](https://github.com/mytechnotalent/dc540-0x00003/blob/main/DC540%20Angels%20Of%20Death.png?raw=true)

# dc540-0x00003
DC540 hacking challenge 0x00003 [C CTF].

<br>

## PROMOTIONAL VIDEO - WATCH NOW [HERE](https://youtu.be/YJAa4o7WXkE) ON YOUTUBE

<br>

## Prior Challenge [HERE](https://github.com/mytechnotalent/dc540-0x00002)

<br>

## Join DC540 Discord [HERE](https://discord.gg/TC9V9RCr5U)

<br>

## FREE Reverse Engineering Self-Study Course [HERE](https://github.com/mytechnotalent/Reverse-Engineering-Tutorial)

<br>

## Parts
#### [Raspberry Pi Pico](https://www.canakit.com/raspberry-pi-pico.html?cid=usd&src=raspberrypi)
#### [Set of 2 x 20-pin Headers for Raspberry Pi Pico](https://www.canakit.com/set-of-2-20-pin-headers-for-raspberry-pi-pico.html)
#### [830 Hole Breadboard](https://www.canakit.com/solderless-breadboard-830-hole.html)
#### [Jumper Wires Male to Male - Pack of 30](https://www.canakit.com/jumper-wires-male-to-male-6.html)
#### [20 Pcs 6 mm 2 Pin Momentary Tactile Tact Push Button Switch Through Hole Breadboard](https://www.amazon.com/Momentary-Tactile-Through-Breadboard-Friendly/dp/B07WF76VHT)
#### [Micro USB Cable High Speed Data and Charging, Nylon Braided Charger Cord, 3-Pack, 3 Feet](https://www.amazon.com/Rankie-Micro-Charging-Braided-3-Pack/dp/B01JPDTZXK)

<br>

## Schematic
![image](https://github.com/mytechnotalent/dc540-0x00003/blob/main/schematic.png?raw=true)

<br>

## BRIEF
A month has transpired and the team was unsuccessful with cracking the MicroPython firmware.  To date this is the only way into the Dark Eyes 1337 Gate to gain access to their secret facility located in a classified location in Siberia.

Pacing back and forth, Bets Fielding and the team continued to do digital forensics on Natalia's usb drive which she used in Dr. Rinn's private study to get the 1337 Gate firmware.

All of the sudden, Bets stumbled upon a hidden partition which contained two files named `1337бэкдор.uf2` and `capture.png` which she was able to retrieve.  

Bets phoned Natalia and asked if she knew about this hidden partition and she said she did not.  Natalia said that she simply grabbed the first usb she could find in Dr. Rinn's Study which was taped to the bottom of her desk drawer.

Knowing this is a raw .uf2 file, Bets knew she had to get it into a bin format to be able to reverse it properly in Ghidra.  Bets wondered if the firmware would also be in MicroPython like the previous one or perhaps a pure C binary.

<br>

## MISSION
You have been selected by the DC540 ANGELS OF DEATH to be the Reverse Engineer on this mission. Your task is to review the attached `capture.png` and convert the `1337бэкдор.uf2` to a .bin binary to begin reverse engineering. Your mission is to flash a Raspberry Pi Pico with the `1337бэкдор.uf2` firmware and see how it operates. Convert the file to a .bin file to bring into Ghidra and properly reverse engineer and then manually hex-edit the `1337бэкдор.uf2` with your changes and re-flash the Raspberry Pi Pico to get the entrance flag and report back to, "The Architect" with your results by sending a private Discord DM to Kevin Thomas.

## HINT
"You will know you have the flag as it will end with, `for processing...`"

<br>

## License
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)
