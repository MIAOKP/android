[Android Open Kang Project](http://aokp.co)
====================================


Download the Source
===================

Please read the [AOSP building instructions](http://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Init core tree for xiaomi device/vendor :

    $ repo init -u https://github.com/MIAOKP/android.git -b kitkat

sync repo :

    $ repo sync

***

Building
--------

After the sync is finished, please read the [instructions from the Android site](http://s.android.com/source/building.html) on how to build.

    1:source build/envsetup.sh

    2:lunch 

    3:make bacon
