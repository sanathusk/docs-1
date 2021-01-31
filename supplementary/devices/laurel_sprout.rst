
laurel_sprout - Xiaomi Mi A3
===========================

The phone features a 6.088 inch HD+ (1560 x 720 pixel) resolution, 283ppi Super AMOLED display, a glass and plastic body, with Corning Gorilla Glass 5 protection on its front as well as its back. 
It is powered by a Qualcomm Snapdragon 665 SoC. It also has a 2.0, Type-C 1.0 reversible connector. 
The main camera has a 48MP Sony IMX586 sensor; there are also the 8MP ultrawide and 2MP depth sensing cameras. 
The front camera has a resolution of 32MP. The battery has a capacity of 4030mAh, which supports 18W quick charging via Qualcomm Quick Charge 3.0. 

The Xiaomi Mi A3 is a re-branded Xiaomi Mi CC9e smartphone, that comes with Android One instead of MIUI on the Mi CC9e. The Xiaomi Mi CC9e is a version meant for China, while the Xiaomi Mi A3 is the global version of the Mi CC9e.
The phone when released in July 2019,was  preinstalled with Android 9 "Pie" .Xiaomi released Android 11 update.

Status
------
Maintainers:
^^^^^^^^^^^^^^


  .. list-table::
    :header-rows: 1
    
    * - Who
      - GitHub
      - Other Links
    * - mintphin
      - https://github.com/mintphin/lunecrash
      - n/a
      - n/a
    * - maffeen
      - n/a
      - n/a
      - n/a


Halium
^^^^^^

A port for Halium 9 is Work-in-Progress by _`mintphin <https://github.com/mintphin>`_ . The device is capable of running Ubuntu touch based on erfan's GSI images.
The latest erfan's GSI images are based on Ubuntu touch OTA-13.

Port status
-----------
Component 	|Status 	|Details
AppArmor 	|Y 	
Boot into UI 	|Y 	
Camera 	|Y 	|Requires gst-droid
Cellular Calls 	|Y 	
Cellular Data 	|Y 	
GPS 	|Y 	
Sensors 	|Y 	
Sound 	|Y 	
UBPorts Installer 	|N 	
UBPorts Recovery 	|N 	
Vibrator 	|Y 	
Wi-Fi 	|Y 	

Distributions
^^^^^^^^^^^^^


.. list-table::
   :header-rows: 1

   * - Distribution
     - Device Specific Files
     - Kernel
     - What works
     - What doesn't work
   * - LineageOS placeholder `device page placeholder <placeholder>`_
     - `android_device_placeholder <placeholder>`_
     - `android_kernel_placeholder <placeholder>`_ based on vX.Y.Z
     - ?
     - ?
   * - Ubports placeholder `device page placeholder <placeholder>`_
     - `android_device_placeholder <placeholder>`_
     - `android_kernel_placeholder <placeholder>`_ based on vX.Y.Z
     - ?
     - ?


Kernel & Hardware
^^^^^^^^^^^^^^^^^

Mainline (vX.Y.Z as of writing)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Write whether something that is needed for the device is mainline already (switch the version in the heading for what's recent when you write this). This means **device tree source files (.dts) as well as single drivers** (for example only the wifi driver).

Cyanogemod based kernels (LOS & UBP)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If other kernels exist, just make up headlines with a name that describe the origin (Cyanogemod, LineageOS, UBports, Canonical, ...) and which is the underlying mainline version. Afterwards describe what's been improved or altered and if possible why or what is still missing.

Device Specifics
----------------

Guides
^^^^^^

This should be populated with guides how to get into different boot modes and similar. Maybe this can be pulled from the `LOS device database <https://github.com/LineageOS/lineage_wiki/tree/master/_data/devices>`_.

Developer Info
^^^^^^^^^^^^^^

Some devices show strange behaviour of some kind, try to find this (for example in the xda-developers forum) and document it

Useful Resources
^^^^^^^^^^^^^^^^

If anything might be usefull but didn't fit above you can just throw in some links here.
