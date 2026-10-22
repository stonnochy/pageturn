# Pageturn (Android)

An offline EPUB and PDF reader for touch and controller, made for the AYN Thor.
The reader is a web page bundled inside a small Android app. It needs no internet
and asks for no permissions. Your books and reading positions stay on the device.

## Get the APK (pick one)

### A. Android Studio on a PC or Mac
1. Install Android Studio (it includes everything else).
2. Choose **Open** and select this folder. Let Gradle sync finish. The first sync downloads
   the reader's libraries and fonts, so you need to be online for that one build.
3. Menu **Build > Build App Bundle(s) / APK(s) > Build APK(s)**.
4. Copy `app/build/outputs/apk/debug/app-debug.apk` to the Thor.

If Studio reports a missing Gradle wrapper, open Settings > Build > Gradle and set it to use
Gradle 8.9 and JDK 17.

### B. GitHub, no install needed
1. Create a new repository on github.com and upload everything in this folder
   (keep the `.github` folder).
2. Open the **Actions** tab, run **Build APK**, then download `Pageturn-apk` from the finished run.
3. Unzip it and copy `app-debug.apk` to the Thor.

## Install on the Thor
Open the APK from the Files app. Android asks to allow installs from that app once.
Accept, install, then open **Pageturn**.

## Controls
D-pad or left stick turn pages. A shows or hides the menu bars. B goes back.
L1/R1 change chapter. L2/R2 change text size. Start opens contents. Select opens appearance.
The Android Back button also goes back.
