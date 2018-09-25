# Craps-Game-with-Custom-Linux-Driver

A console-based game based on the popular dice game Craps. Wrote a custom Linux device driver for a virtual device whose sole task is to generate a random dice roll. In addition, wrote the Craps game, which issues a read request via a system call to the virtual device, which will return a random integer between 1 and 6, each time a new dice roll is needed. The Craps game is fully functional and follows all the regular rules of the original dice game, using the virtual device to generate new dice rolls when necessary. The driver was written entirely in C, as well as the game, which also uses the C standard library.
