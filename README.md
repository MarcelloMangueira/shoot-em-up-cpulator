# 👾 Shoot'em Up - CPULATOR (DE1-SoC ARMv7)

This repository contains a project completed for a university course on Introduction to Embedded Systems. It is a game developed in C for the DE1-SOC board (ARMv7). It was developed using the CPULATOR simulator (ARMv7) and later adapted to the real board, using peripheral mappings. Peripherals such as VGA, 7-segment displays, and push buttons, as well as the double-buffering technique, were used.

## 🔫 About the project
- A spaceship-themed shoot-em-up arcade game.
- Programmed in C.
- Created on the ARMv7 architecture.
- Developed using CPULATOR, but also runs on DE1-SOC.

## 💻 How to play (CPULATOR)
- Download the shootemup.c file
- Run it on the cpulator website with the Armv7 and DE1-SoC options.
- Select the C language option at the top of the website.
- Disable I/O device warnings on the left side of the website in the "Settings -> Debugging Checks" tab.
- Compile and run the game.

## 🔌 How to play (DE1-SoC board)
- Connect a monitor to the VGA output.
- Compile using: gcc -std=gnu99 -DDE1SOC shootemup.c -o shootemup.
- Run the program.

## 👽 Screenshots and game details
- Control the player's movement and shooting with the push buttons.
- Shoot enemies and avoid losing all your lives.
- Your score is updated and displayed on the 7-segment displays.
<img width="764" height="567" alt="image" src="https://github.com/user-attachments/assets/eefd3599-f904-448b-a811-a444c399271e" />

- The game features a variety of enemies and upgrades
<img width="762" height="566" alt="image" src="https://github.com/user-attachments/assets/d9f0dd52-d9b8-490c-9236-16f10a10f139" />
