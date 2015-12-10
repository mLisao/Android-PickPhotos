#Android-PickPhotos

PickPhotos for Android Devices.

##How to use.

####PickConfig

```code

   new PickConfig.Builder(this)
                .pickMode(PickConfig.MODE_MULTIP_PICK)
                .maxPickSize(30)
                .spanCount(3)
                .toolbarColor(R.color.colorPrimary)
                .build();
```
####Permission

```code
	  <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE"/>
```
####mianfest
```code
   <activity android:name="me.crosswall.photo.pick.PickPhotosActiviy"
            android:screenOrientation="portrait"/>

```

