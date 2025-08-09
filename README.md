# SystemCore Kotlin Template

This repository contains a SystemCore FRC project with Kotlin added. Just duplicate the repo,
change the team number in `.wpilib/wpilib_preferences.json`, and you can begin coding!

If you would like to change what package your project is stored in (from `frc.robot` to `org.chillout1778`, for example),
rename the package and then edit line 16 (where `ROBOT_MAIN_CLASS` is defined) of `build.gradle` to reflect your new package.

Unless you choose to use the `@file:JvmName` annotation, Kotlin will append `Kt` to the end of your file name. So if your
main class is called `Main`, your `ROBOT_MAIN_CLASS` definition needs to point to `MainKt`. If you mark with `@file:JvmName`,
just use whatever name you set in the annotation. Remember to use the full package name when pointing to the main class.