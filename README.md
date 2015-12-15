LG G2 AT&T Device Configuration for Broken OS
=============================================
**UNOFFICIAL**
--------------

`./repo/local_manifests/broken_roomservice.xml`
```
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project path="device/lge/d800" name="drgroovestarr/device_lge_d800" remote="github" revision="m6.0" />
  <project path="device/lge/g2-common" name="drgroovestarr/device_lge_g2-common" remote="github" revision="m6.0" />
  <project path="vendor/lge" name="proprietary_vendor_lge" remote="aicp" revision="mm6.0" />
  <project path="kernel/lge/msm8974" name="kernel_lge_msm8974" remote="aicp" revision="mm6.0" />
  <project path="external/sony/boringssl-compat" name="android_external_sony_boringssl-compat" remote="cm" revision="cm-13.0" />

</manifest>
```