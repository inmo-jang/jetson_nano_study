# jetson_nano_study
Jetson Nano Study

## Trouble shootings while setting up
- No booting after showing NVIDIA symbol
  - This is because of lack of the power supply for the nano. I used an Apple Magic Keyboard, which particularly seems need more power than a normal keyboard. With my mobile phone charger 5V-2A, the nano was able to boot with a wired mouse only. So, I was able to set up the board using the mouse, then connecting with the keyboard is okay with my 5V-2A mobile phone charger.
  
- VSCode install should be based on `arm64`

