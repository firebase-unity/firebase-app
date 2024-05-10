# How To Install

- Since version `12.0.0` `FirebaseCppApp.bundle` used to running in unity editor in macbook not directly include in this package
- Instead it will be segregated into a separate bundle to minimize amount of bandwidth used by git LFS. [Install the following package if running on mac](https://github.com/firebase-unity/firebase-support-ios)


### Install by add directly in `manifest.json` in folder `Packages/manifest.json`

for version `12.0.0`
```csharp
"com.google.firebase.app": "https://github.com/firebase-unity/firebase-app.git#12.0.0",
```

dependency `external-dependency-manager-1.2.177`
```csharp
"com.google.external-dependency-manager": "https://github.com/google-unity/external-dependency-manager.git#1.2.177",
```
