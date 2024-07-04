# Diag-mode-qualcomm

resetprop ro.bootmode usbradio
resetprop ro.build.type userdebug
setprop sys.usb.config diag,diag_mdm,adb
