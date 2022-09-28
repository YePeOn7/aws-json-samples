CC = gcc
CFLAG = -Wall ${INCLUDE_PATH}

TARGET = jsonTest

SOURCE = jsonTest.c
SOURCE += ../aws-iot-device-sdk-embedded-c/libraries/standard/coreJSON/source/core_json.c

INCLUDE_PATH += -I ../aws-iot-device-sdk-embedded-c/libraries/standard/coreJSON/source/include/

all:
	${CC} ${CFLAG} ${SOURCE} -o ${TARGET}

clean:
	rm -rf ${TARGET}
