## Overview
Personal repo that includes prebuilt applications for use with RattlesnakeOS. See the [FAQ](https://github.com/dan-v/rattlesnakeos-stack#faq) for more details on customizations.
This also contains the MicroG prebuilts and patches from https://github.com/RattlesnakeOS/microg

```
[[custom-patches]]
patches = ["00002-microg-sigspoof.patch"]
repo = "https://github.com/johan-adriaans/Pixel2Apps"

[[custom-prebuilts]]
modules = ["GmsCore","GsfProxy","FakeStore","com.google.android.maps.jar","GoogleCalendarSyncAdapter"]
repo = "https://github.com/johan-adriaans/Pixel2Apps"

```

## Required Repo Structure
Each app you want to include should:
* Create a subdirectory for each app you want to add (e.g. app1), add both the APK file and Android.mk file into this subdirectory.
