## Overview
Personal repo that includes prebuilt applications for use with RattlesnakeOS. See the [FAQ](https://github.com/dan-v/rattlesnakeos-stack#faq) for more details on customizations.

```
[[custom-prebuilts]]
  modules = ["app1", "app2"]
  repo = "https://github.com/RattlesnakeOS/example_prebuilts"
```

## Required Repo Structure
Each app you want to include should:
* Create a subdirectory for each app you want to add (e.g. app1), add both the APK file and Android.mk file into this subdirectory.
