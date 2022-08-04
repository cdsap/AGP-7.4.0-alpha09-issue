## Issue AGP 7.4.0-alpha09 and Kotlin 1.5.32 with databinding
Project using:
* Gradle 7.5
* AGP 7.4.0-alpha09
* KGP 1.5.32
* Databinding enabled

Error:
```
Class 'kotlin.Unit' was compiled with an incompatible version of Kotlin. The binary version of its metadata is 1.7.1, expected version is 1.5.1.
```

Steps to reproduce:
`./gradlew assembleDebug`

Build scan: https://gradle.com/s/pok4eqyxxbb4s

Same project using 7.4.0-alpha08 compiles correctly






