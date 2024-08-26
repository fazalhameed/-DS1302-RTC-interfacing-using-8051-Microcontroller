# DS1302-RTC-interfacing-using-8051-Microcontroller

This driver facilitates communication between an 8051 microcontroller and the DS1302 real-time clock (RTC) module. It enables reading and writing of data/time to the DS1302, display of time on a 16x2 LCD, and setting the time on the RTC via PC using Hercules software and a serial port.

RTC Functions:
1. Read Time: Reads the current time from the DS1302 RTC module.
2. Write Time: Sets the time on the DS1302 RTC module.
3. Display Time: Automatically updates and displays the current time on a 16x2 LCD.

Usage:
1. Connect the DS1302 module and the 16x2 LCD display to the 8051 microcontroller.
2. Initialize the DS1302 RTC module using `DS1302_init()`.
3. Use `DS1302_get_time()` to read the current time from the DS1302.
4. Use `DS1302_set_time()` to set the time on the DS1302 RTC module.
5. Display the time on the LCD using your display library of choice.

Setting Time from PC:
1. Connect the serial port of the 8051 microcontroller to your PC.
2. Use Hercules software or any serial communication tool to send time-setting commands to the DS1302 RTC module.

Note:
- Refer to the DS1302 datasheet for detailed information on registers and commands used in the driver.
