# smbfordos
it's super mario bros for the ms-dos opreating system!

## gameplay
so far the game includes walking, running and jumping, as well
as basic scrolling and level data, hold the arrow keys to walk,
hold the left shift to run faster while walking, press the left
control to jump and press escape to exit the game back to dos.

## System Requirements
To run properly on a real machine, super mario bros for dos requires the
following:


- an 8086-compatible cpu (386 or newer recommended)

- the MS-DOS opreating system 

- vga graphics mode 13h support

- a ps/2

- the PIT timer

- Soundblaster 1 (soundblaster 16 recommended)

- at least 256kb of free ram (612kb of ram recommended)

- at least 2 megabytes of free space on the disk (for executable + audio files)

This game haven't been tested yet on a real machine, so performance and soundblaster audio may have some issues
it's generally recommended to run this game on the dosbox emulator, the recommended emulator that was tested is
dosbox 0.74 at a speed of 45000 cycles+.


## Running the game
To run the game, download the latest release from the releases and extract a zip
if needed, once you done it, you should see a file named "mario.COM" that is the
dos executable, you should also see an audio file, the audio file and the executable
must be in the same folder, else the game would refuse to run and would exit back
to the dos terminal, once you got the executable and the audio files in the same
folder you should be able to run it in an emulator or a real machine if you got one.


## Building from the assembly file
The source code of the game is stored in the assembly file "mario.asm", to assemble
the game run the following script:

nasm -f bin "mario.asm" -o mario.COM

if you don't have NASM, make sure to install it on your system.


## A guide for installing NASM

### Installing NASM on Windows
To install NASM,
Download the installer from:
https://www.nasm.us

then run the installer and during setup, make sure to enable "Add NASM to PATH",
Once the installation is done, verify it in bash using the following command:

nasm -v

### Installing NASM on Linux
To install NASM on linux, open the terminal and run the following commands:

sudo apt update

sudo apt install nasm

then verify with:

nasm -v

### Installing NASM on macOS (Homebrew)
To Install NASM, run the following command:

brew install nasm

then verify with:

nasm -v