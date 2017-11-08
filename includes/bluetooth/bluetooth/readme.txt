Please note that in order to use Bluetooth stack for the cross compilation on Raspberry Pi,
download bluez stack and add the lib directory content to here,
with inclusion paths corrected.
i.e. #include <bluetooth/bluetooth.h> -> #include "bluetooth.h"

This code is tested with bluez-5.9
Download from: https://www.kernel.org/pub/linux/bluetooth/