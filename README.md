
BiometricManager crash on release build (Android 9)

https://github.com/takagisou/BiometricManagerCrashOnAndroid9/blob/main/app/src/main/java/com/example/biometricmanagercrashonandroid9/MainActivity.kt#L42


```kotlin
BiometricManager.from(context).canAuthenticate(BiometricManager.Authenticators.BIOMETRIC_WEAK)
```

<img src="./assets/ss.gif" />
