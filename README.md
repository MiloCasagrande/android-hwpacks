= Android Hardware Packs =

The repository contains all the Android hwpack necessary to use Linaro Image
Tools while creating Android images.

For the specification of an Android hardware pack, look:

https://wiki.linaro.org/AndroidHardwarePacksV3

= How to =

A new command line argument has been introduced to 'linaro-android-media-create':

linaro-android-media-create --hwpack [FILE] ...

The new argument is optional, and old behavior has been maintaned.

= Availability =

The new option is available starting from Linaro Image Tools 2013.01.
