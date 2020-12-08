# HC90_PS2_Keyb
An simple adaptor that allows the use of a PS2 keyboard with the Victor HC-90 and HC-95 MSX computers


  This adaptor is completely based on the work by Kuni,  who has graciously shared it at:
  https://github.com/kuninet/KZ80-PS2KBD
  
  
    It only requires an Atmega328P chip,  a PS2 female connector, a 20 pin female IDC flat cable and a piece of protoboard
    
    
    1.-  The Atmega 328P needs to be flashed with a bootloader that enables it to use the internal oscilator ar 8MHz.  Some instructions are here:
    
    https://www.arduino.cc/en/Tutorial/BuiltInExamples/ArduinoToBreadboard
    
    2.-  Then,  download and install the code from Kuni's repository and upload it to the Atmega using the arduino IDE:
      
    https://github.com/kuninet/KZ80-PS2KBD/tree/master/source/PS2_KZ80
      
    3.-  Carefully solder the Atmega to the flat cable and the PS2 connector using the protoboard to hold it together.   Connect everything as shown here:
    
    https://github.com/dproldan/HC90_PS2_Keyb/blob/main/hc90%20to%20ps2.png
    
       The connector is shown in the drawing as you would see it from the back of the computer.
       
     Connect everything and good luck!
     
     
      
    
    
