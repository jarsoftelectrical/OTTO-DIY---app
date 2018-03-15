# OTTO-DIY---app
OTTO DIY app created for bluetooth conectivity.


Please make sure that you use all the Libraries within these folders, even if you already have similar libraries.

If you have a default Bluetooth module use the OTTO_NEW_OTTO_APP_9600 sketch.

Please check this repository for Android app updates.

Otto will be in his standard waiting MODE, once the APP is connected to Otto - a command to put him into MODE 4, app mode, will be sent to Otto, the features and control from the app will then be possible.

In the event that Otto does not seem to function with the app, select MODE 4 from the app, this will resend the command to put him into app mode again. Otto will display the MODE number on his Matrix mouth each time it is changed.


If all else fails and Otto still does not resond to the app, Please check the Baud rate of the sketch matches the Baud rate of the Bluetooth module, the default for most standard modules is 9600 but this might not be correct for every module.

