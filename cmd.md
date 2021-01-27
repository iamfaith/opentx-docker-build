sudo docker build -t opentx-build .

sudo docker run --rm -it -e "BOARD_NAME=tlite" -e "CMAKE_FLAGS=HELI=YES FAI=CHOICE FONT=SQT5 INTERNAL_MODULE_MULTI=YES BLUETOOTH=NO VERSION_SUFFIX=FLEX MODULE_PROTOCOL_FLEX=YES" -v /home/faith/opentx:/opentx opentx-build
-----------------------



sudo docker run --rm -it -e "BOARD_NAME=tlite" -e "CMAKE_FLAGS=HELI=YES FONT=SQT5 FAI=CHOICE GVARS=YES LUA=YES PPM_UNIT=PERCENT_PREC1 MODULE_PROTOCOL_FLEX=YES" -v /home/faith/opentx:/opentx opentx-build



=======================================

----
use this 


sudo docker run --rm -it -e "BOARD_NAME=tlite" -e "CMAKE_FLAGS=HELI=YES FONT=SQT5 FAI=CHOICE GVARS=YES LUA=YES PPM_UNIT=PERCENT_PREC1 MODULE_PROTOCOL_FLEX=YES MODULE_PROTOCOL_FLEX=YES" -v /home/faith/opentx:/opentx opentx-build