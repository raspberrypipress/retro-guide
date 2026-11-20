# Raspberry Pi Guide to Retro Gaming

Example code and resources for Raspberry Pi Guide to Retro Gaming

## Altirra (Atari 8-bit) notes:

- We accidentally omitted some apt dependencies in the Altirra compilation instructions (very sorry about that). Please see raspberrypipress/retro-guide#1 for instructions to fix this.
- After we went to press, AltirraSDL began exhibiting a GUI freeze on Linux, including Raspberry Pi. This has been fixed as of ilmenit/AltirraSDL#113.
- The most recent version of AltirraSDL enable some screen effects by default that may cause it to run slowly even on a Raspberry Pi 5/500/500+. If you find this to be the case, click the *View* menu, choose *Screen Effects* and change it from *Basic* to *(None)*. If you'd like to leave them enabled, you can experiment with the settings by choosing *Adjust Screen Effects* instead of *(None)*.
