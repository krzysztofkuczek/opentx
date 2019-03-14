

The  2.2.3 version for xlite enabling old PXX 9ms pulse based driver for external modules. Just to make it works with Qczek LRS http://qczek.beyondrc.com/qczek-lrs-433mhz-1w-lora-rc-link/.

Compiled with flags
cmake -DPCB=XLITE -DMODULE_R9M_FULLSIZE=YES -DMULTIMODULE=YES -DLUA=YES -DLUA_COMPILER=YES -DTRANSLATIONS=EN -DCMAKE_PREFIX_PATH=/usr/local/opt/qt5 ..
