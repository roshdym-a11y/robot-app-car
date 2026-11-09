# LITTLE ENGINEERS – ROBOT CONTROLLER

Android app (Kotlin, no external libraries) for an Arduino UNO R3 4WD robot with HC-05 Bluetooth.

Build the APK: open this folder in Android Studio and run Build > Build APK(s), or push it to GitHub
(the workflow in .github/workflows builds `app-debug.apk` for you), or run `gradle assembleDebug` (JDK 17, Android SDK 34).
Output: app/build/outputs/apk/debug/app-debug.apk

Robot code: arduino/RobotCar/RobotCar.ino (wiring and the command list are in its header).
Pair the HC-05 once in Android Bluetooth settings (PIN 1234 or 0000), then open the app.
