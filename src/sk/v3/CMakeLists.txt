
set(AVR_MCU atmega32u4)
set(MCU_FREQ 16000000UL)

set(AVR_PROGRAMMER avr109)
set(AVR_PROGRAMMER_PORT /dev/ttyACM0)
#set(AVR_PROGRAMMER_BAUDRATE 19200)
set(PROGRAM_EEPROM False)

avr_add_executable(sk_v3_master master/main.cpp)
avr_add_executable(sk_v3_slave  slave/main.cpp)
