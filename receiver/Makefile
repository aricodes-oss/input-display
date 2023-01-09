SRC_DIR = ./src
OUT_DIR = /run/media/ari/CIRCUITPY

SERIAL_DEVICE = /dev/serial/by-id/usb-Raspberry_Pi_Pico_W_E6614C311B272A36-if00

push:
	cp -r ${SRC_DIR}/* ${OUT_DIR}/

pull:
	cp -r ${OUT_DIR}/* ${SRC_DIR}

term:
	tio ${SERIAL_DEVICE}
