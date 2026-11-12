# Raspberry Pi Guide to Retro Gaming

Example code and resources for Raspberry Pi Guide to Retro Gaming

## Altirra (Atari 8-bit) notes:

- We accidentally omitted some apt dependencies in the Altirra compilation instructions (very sorry about that). Please see raspberrypipress/retro-guide#1 for instructions to fix this.
- After we went to press, AltirraSDL began exhibiting a GUI freeze on Linux, including Raspberry Pi. Please run the command `git checkout afcd3beb970343626ae49fe917e5d56f925fdcf8` after you `cd` into the `AltirraSDL` folder and before the first `cmake` command. See ilmenit/AltirraSDL#112 for details.
