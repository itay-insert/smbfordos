# smbfordos
it's super mario bros for the ms-dos opreating system!
















the source code is in the assembly file "mario.asm", to run it, assemble with:




nasm -f bin mario.asm -o mario.COM





then run it in dosbox 0.74 or dosbox-x (0.74 reccommended for best performance)
if you don't have nasm... install it, also
make sure your emulator supports:



vga mode 13h 320x200x8

the pit timer

a ps/2 keyboard

soundblaster



the game can't work without those!

reccomended dosbox speed for guarranteed best performance: 45000 cycles+

reccomended cpu for best peformance: pentium 90mhz+

also don't forget to bring your own legally obtained audio files (Ground.wav), at 8-bit pcm
from a rom or something the game would throw an error code and bring you back to dos without those!

note for dosbox-x/vm users:
specificallly in dosbox-x and the vm, soundblaster driver won't work properly
and i am not going to fix it anytime soon, so if you want mario music that badly
make sure to open rayman at least once before you open this game... because this
fixes the soundblaster for whatever reason (rayman really is a magical game)...
or you could just run it in dosbox 0.74 instead where everything just works!
