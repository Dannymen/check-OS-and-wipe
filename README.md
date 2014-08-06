check-OS-and-wipe
=================


if $ adb shell getprop ro.build.version.release  
  adb shell
  recovery --wipe_data
else 
  adb reboot
  
  
print "Double Check Factory Wipes"
