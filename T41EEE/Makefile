# for use with the Arduino CLI https://github.com/arduino/arduino-cli
.PHONY: build flash

BOARD = teensy:avr:teensy41
PORT  = usb1/1-1/1-1.4/1-1.4.2


dummy:
	@echo "Please specify a target to build"


build:
	arduino-cli compile --fqbn ${BOARD}

flash:
	arduino-cli upload --fqbn ${BOARD} --port ${PORT}
