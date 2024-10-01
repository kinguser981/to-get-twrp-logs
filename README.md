# How to get TWRP log files:​
#
# recovery.log
```
adb pull /tmp/recovery.log
```
OR
Advanced -> Copy Log -> Swipe to copy log to default storage
# dmesg
```
adb shell dmesg > dmesg.log
```
OR
#
Advanced -> Copy Log -> check "Include kernel log" -> Swipe to copy log to default storage
#
# logcat
```
adb logcat -d > logcat.txt
```
OR
#
Advanced -> Copy Log -> check "Include Logcat" -> Swipe to copy log to default storage
#
