# Adam Ibrahim

CS and math at Centre College, class of 2028. I mostly write C and Python. Looking for a Summer 2027 software engineering or quant internship.

I tend to like problems with a hard limit on them. The ChessOS kernel had to fit in 5 KB, and the archive players had to work inside a hosted site I can't change much.

[ChessOS](https://github.com/adam-ibrahim-git/ChessOS) is a 16-bit x86 OS I wrote for my operating systems class last spring. It boots from a floppy image in QEMU into a shell, and `execute chess` starts a two-player game. The course gave us the bootloader and a spec for the system calls, file system and shell, and I wrote those in C. Then I added the chess (ported from a Python version I made in intro programming), a clock in the corner of the screen that runs off the timer interrupt (that handler is in assembly), and simulated scheduling and memory allocation. The bootloader only reads 10 sectors, which is where the 5 KB comes from. Mine compiles to about 3.5.

The chess won't let you move into check and shows CHECK!, but it doesn't know when the game is over yet, and there's no castling, en passant or promotion. The OS runs one program at a time, so the scheduler is a simulation.

[datafest-2026](https://github.com/adam-ibrahim-git/datafest-2026) is the code behind our Best in Show at ASA DataFest 2026 (I led a team of three): were patients' paths through a regional health system equitable across groups? The data itself is confidential.

I'm also the only web developer for We Were Here, a public archive of Black history in Danville, KY. [we-were-here](https://github.com/adam-ibrahim-git/we-were-here) has the media hosting and the players the site embeds ([try one](https://adam-ibrahim-git.github.io/we-were-here/player.html)).

Not on GitHub: research with Prof. Neidmann on Collatz-style integer maps, private until the group publishes. I wrote a second engine on a different algorithm from the group's and it matched all 14,028 entries of their degree-3 matrix. I also proved a parity law for the component counts.

I TA intro Python and the C/Linux systems course and run the intramural soccer league here. Top 0.2% on Chess.com. Grew up in Egypt and Saudi Arabia.

adam.ibrahim@centre.edu or [LinkedIn](https://www.linkedin.com/in/adam-ibrahim-ln/)
