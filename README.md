# SAMD-UPDI-breakaway
 A USB-to-UART-to-UPDI circuit board designed in KiCAD, based on Quentin Bolsee's [SAMD11C14 UART/UPDI programmer](https://fabacademy.org/2020/labs/ulb/students/quentin-bolsee/projects/samd11c_uart-updi/).  This version is designed so you can snap it in half to create a USB-to-UART adapter, and a UART-to-UPDI adapter, that can be used separately or joined together.  If you don't plan to use the "breakaway" feature, you don't need to solder in the 6-pin headers, and you might want to delete the internal slot to make it stronger.
 
 ![Hero shot of board](SAMD-UPDI-Breakaway-vsm.jpg)

 # Parts List
* [MCP1700T-3302E/TT LDO Voltage Regulator 5v->3.3v](https://www.mouser.com/ProductDetail/579-MCP1700T3302E-TT)
* [ATSAMD11C14A-SSNT SAMD microcontroller](https://www.mouser.com/ProductDetail/556-ATSAMD11C14ASSNT)
* [M20-8750242 2.54mm 2+2 DIL SMT header](https://www.mouser.com/ProductDetail/855-M20-8750242)
* [M20-8890645 2.54mm 6 way horzontal male SMT header](https://www.mouser.com/ProductDetail/855-M20-8890645)
* [M20-7910642R 2.54mm 6 way horzontal female SMT header](https://www.mouser.com/ProductDetail/855-M20-7910642R)  Qty: 2
* [1206 SMD resistor 4.7k](https://www.mouser.com/ProductDetail/652-CR1206-JW-472ELF)
* [1206 SMD resistor 1.2k](https://www.mouser.com/ProductDetail/652-CR1206FX-1201ELF)
* [1206 SMD zero-ohm SMD jumper](https://www.mouser.com/ProductDetail/652-CR1206-J-000ELF)
* [1206 SMD 1uF ceramic capacitors](https://www.mouser.com/ProductDetail/187-CL31B105KAHNFNE) Qty: 2
