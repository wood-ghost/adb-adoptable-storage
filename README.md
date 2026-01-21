# adb-adoptable-storage

ref: https://zhuanlan.zhihu.com/p/190916713

```bash
chmod +x ./adb/linux/adb

# xperia
./adb/linux/adb shell sm set-force-adoptable true

./adb/linux/adb shell sm list-disks

# 50% internal
./adb/linux/adb shell sm partition disk:179,64 mixed 50

# 100% internal
./adb/linux/adb shell sm partition disk:179,64 private
```

Then the xperia system will help you format the SD card.
