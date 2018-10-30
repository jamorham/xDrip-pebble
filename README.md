# cgm-pebble-offline
Offline pebble watchface based on the Nightscout community version
Note:  This current version is a modifcation of Kevin Lee's original cgm-pebble-offline.  It is intended for use with xDrip, not Nightscout.

As such, it is based on the cgm-pebble version 6.0 code.
There ARE NO EASTER EGGS.
Alerts have been removed except for the falling rate-of-change alerts.
This watch face is meant for patients to use with xDrip, not for parents/carers.
All notifications/alerts are generated within xDrip (except for falling rate-of-change).
Ensure you enable notifications from xDrip in the Pebble App, and enable Third Party notifications, otherwise these will NOT come through on the pebble.

<a href="https://ibb.co/dtUFdn"><img src="https://preview.ibb.co/eR5oyn/IMG_1238.jpg" alt="IMG_1238" border="0"></a>
<a href="https://ibb.co/kunXTA"><img src="https://preview.ibb.co/d5qVFq/IMG-1240.jpg" alt="IMG-1240" border="0"></a>

Choose "Standard Watchface (old)" in xDrip and activate "xdrip Statusline (watch)" in your ConfigBuilder of AAPS.
Then install this watchface manually over the existing one:
Activate the developer option in your pebble app and have a look at the given IP adress.
Switch to the main directory from terminal and execute:

export PEBBLE_PHONE="192.168.xxx.xxx"

pebble install
