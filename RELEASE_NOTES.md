# AndroidMaterialValidation - RELEASE NOTES

## Version 3.0.1 (Feb. 23th 2019)

A minor release, which introduces the following changes:

- Updated dependency "AndroidUtil" to version 2.0.1.
- Updated AppCompat support library to version 1.0.2.

## Version 3.0.0 (Oct. 30th 2018)

A major release, which introduces the following changes:

- Migrated library to Android X.
- Updated dependency "AndroidUtil" to version 2.0.0.
- Updated targetSdkVersion to 28.

## Version 2.1.6 (May 2nd 2018)

A minor release, which introduces the following changes:

- Updated dependency "AndroidUtil" to version 1.20.2.
- Updated AppCompat v7 support library to version 17.1.1

## Version 2.1.5 (Jan. 26th 2018)

A minor release, which fixes the following issues:

- Updated `targetSdkVersion` to API level 27 (Android 8.1).
- Updated dependency "AndroidUtil" to version 1.19.0.
- The data structure `ListenerList` is now used for managing event listeners.

## Version 2.1.4 (Jan. 5th 2018)

A bugfix release, which fixes the following issues:

- Fixed crashes on older devices, e.g. https://github.com/michael-rapp/AndroidMaterialValidation/issues/3.

## Version 2.1.3 (Dec. 26th 2017)

A minor release, which introduces the following changes:

- Updated dependency "AndroidUtil" to version 1.18.3.
- Updated AppCompat v7 support library to version 17.0.2.

## Version 2.1.2 (Nov. 25th 2017)

A bugfix release, which introduces the following changes:

- The arrow of a `Spinner` is now properly tinted on devices with an API level less than 21 (see https://github.com/michael-rapp/AndroidMaterialValidation/issues/2).
- Updated dependency "AndroidUtil" to version 1.18.2.
- Updated AppCompat v7 support library to version 17.0.1.

## Version 2.1.1 (Nov. 1st 2017)

A minor release, which introduces the following changes:

- Fixed Lint errors, which occur in Lint 3.0.
- Updated dependency "AndroidUtil" to version 1.18.1.
- Updated AppCompat v7 support library to version 17.0.0.

## Version 2.1.0 (Oct. 1st 2017)

A feature release, which introduces the following changes:

- Updated dependency "AndroidUtil" to version 1.18.0.
- Updated AppCompat v7 support library to version 26.1.0.
- Updating the dependencies required to increase the `minSdkVersion` to API level 14.

## Version 2.0.6 (Sep. 20th 2017)

A minor release, which introduces the following changes:

- Updated `targetSdkVersion` to API level 26 (Android 8.0).
- Updated dependency "AndroidUtil" to version 1.17.1.
- Updated AppCompat v7 support library to version 25.3.1.

## Version 2.0.5 (Jan. 25th 2017)

A minor release, which introduces the following changes:

- Updated `targetSdkVersion` to API level 25 (Android 7.1).
- Updated dependency "AndroidUtil" to version 1.12.3.
- Updated AppCompat v7 support library to version 25.1.0.

## Version 2.0.4 (Sep. 11th 2016)

A minor release, which introduces the following changes:

- Updated `targetSdkVersion` to API level 24 (Android 7.0).
- Updated dependency "AndroidUtil" to version 1.11.1.
- Updated AppCompat v7 support library to version 24.2.0.

## Version 2.0.3 (Sep. 7th 2016)

A bugfix release, which fixes the following issues:

- https://github.com/michael-rapp/AndroidMaterialValidation/issues/1
- Updated dependency "AndroidUtil" to version 1.11.0.
- Updated AppCompat support library to version 23.4.0.

## Version 2.0.2 (Mar. 17th 2016)

A minor release, which introduces the following changes:

- Updated the dependency "AndroidUtil" to version 1.4.5.
- Fixed some deprecation warnings.

## Version 2.0.1 (Feb. 24th 2016)

A minor release, which introduces the following changes:

- The library is from now on distributed under the Apache License version 2.0. 
- Updated the dependency "AndroidUtil" to version 1.4.3.
- Updated the AppCompat support library to version 23.1.1.
- Minor changes of the example app.

## Version 2.0.0 (Oct. 18th 2015)

A major release, which introduces the following changes:

- The project has been migrated from the legacy Eclipse ADT folder structure to Android Studio. It now uses the Gradle build system and the library as well as the example app are contained by one single project.
- The library can now be added to Android apps using the Gradle dependency `com.github.michael-rapp:android-material-validation:2.0.0`

## Version 1.0.0 (June 7th 2015)

The first stable release, which initially provides the following features:
	
- The library provides a custom `EditText` implementation, which can be validated according to the Material Design guidelines.
- The library provides a custom `EditText` implementation, which can not only be validated according to the Material Design guidelines, but also allows to visualize the password strength, depending on customizable constraints.
- The library provides a custom `Spinner` implementation, which can be validated according to the Material Design guidelines.
- The library includes a large number of pre-defined validators, for example for validating phone numbers, e-mail addresses, domain names etc.