# mohalbheri 00967712713622 read spc no box
# commend adb shell 
abd shell

adb shell export ANDROID_LOG_TAGS="" ; exec logcat -d QcrilMsgTunnelSocket:D QC_RIL_OEM_HOOK:V *:S

done
