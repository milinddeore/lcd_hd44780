# lcd_hd44780
HD44780 LCD - Arduino Due running Zephyr

Add lcd_hd44780 under ./zephyr-project/samples/driver/
verify your paths and if possible run 'source ./zephyr-project/zephyr-env.sh'
compile lcd_hd44780 code by issuing 'make' this will create zephyr.bin under 'outdir' directory.
This is binary file, flash it on your arduino due (as this is cross compiled for arduino-due), using BOSSA utility. 
