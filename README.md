# How To Install

- As of version 12.0.0 `FirebaseCppApp.bundle` used to run in unity editor on macbook will not be directly included in this bundle
- Instead it will be segregated into a separate bundle to minimize amount of bandwidth used by git LFS. [Install the following package if running on mac](https://github.com/firebase-unity/firebase-support-ios)


### Install by add directly in `manifest.json` in folder `Packages/manifest.json`

for version `12.7.0`
```csharp
"com.google.firebase.app": "https://github.com/firebase-unity/firebase-app.git#12.7.0",
```

dependency `external-dependency-manager-1.2.185`
```csharp
"com.google.external-dependency-manager": "https://github.com/googlesamples/unity-jar-resolver.git?path=upm#v1.2.185",
```
