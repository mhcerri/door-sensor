#
# ATtiny2313 Blink example using makefile.
#
# Make sure Arduino 1.6.4+ is installed on your system or use ARDUINO_DIR to
# point to an Arduino installation.
#
# To change the fuses values refer to the datasheet:
#   http://www.atmel.com/images/doc2543.pdf
#
# And use `make set_fuses`.
#
# To program use `make ispload`.
#
ALTERNATE_CORE		= tiny
ALTERNATE_CORE_PATH	= ../attiny-core/avr/
BOARD_TAG		= attinyx5
BOARD_SUB		= 85
F_CPU			= 1000000L
ISP_PROG		= arduino
ISP_PORT		= /dev/ttyUSB0
ISP_HIGH_FUSE		= 0xdf
ISP_LOW_FUSE		= 0x63
ISP_EXT_FUSE		= 0xff
ARDUINO_LIBS 		= RF24
USER_LIB_PATH		= ../libraries
include ../arduino-mk/Arduino.mk
