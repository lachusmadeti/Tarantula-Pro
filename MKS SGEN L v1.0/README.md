# Tarantula-Pro
Firmware Homers Odysseus/Tevo Tarantula Pro.  
MKS SGEN L v1.0 and MKS Mini 12864 LCD.  
Only files for the Marlin directory, you need a Marlin Firmware, download from https://marlinfw.org/meta/download/ and substitute the Marlin directory files inside.
Custom your printer name, and all you need.  
Base language is Spanish, you can change on #define LCD_LANGUAGE es
# Compiling instructions
I use for compile Visual Studio Code with platformio, remember to change the default_envs at platformio.ini and set LPC1768 for this board.
# Versions  
Stock -> stock hardware from factory  
Power Loss Recovery -> activated Power Loss Recovery, now writes always the last layer before printing, shorts SD´s life. Working on activate PIN for detect power failure and write only the actual possition of nozzle.  
