# moto_x4_wide_permission

Unset the prop vendor.camera.aux.packagelist.

In lineage if the prop is not defined the aux camera is exposed to all apps.

Can work with others roms that have same behaviour.

https://github.com/LineageOS/android_frameworks_base/blob/884fa6b77413118c160a5476bdad171c6c355df1/core/java/android/hardware/camera2/CameraManager.java#L916
