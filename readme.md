# Phoque2 Board definitions

Usage in Platformio:

- Clone this repository into a folder within your PlatforIO project (for example `custom_arduino_variant`)
    - `mkdir custom_arduino_variant; cd custom_arduino_variant && git clone https://github.com/Moddingear/Phoque2-boarddef PHOQUE2`
- Move PHOQUE2.json to a folder named `boards` 
    - `mkdir ../boards; cp PHOQUE2.json ../boards`
- Add `board_build.variants_dir = custom_arduino_variant` to platformio.ini
- That's it
