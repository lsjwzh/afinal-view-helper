# Afinal-view-helper

Simple plug-in for Android Studio/IDEA that allows one-click creation of [Afinal view injection](https://github.com/yangfuhai/afinal) view injections.

## How to install

- in Android Studio: go to `Preferences → Plugins → Browse repositories` and search for `afinal`  [waiting]

_or_

- [download it](http://plugins.jetbrains.com/plugin/7369) and install via `Preferences → Plugins → Install plugin from disk`


## How to use it

 ![](img/zelezny_animated.gif)

 1. Right click on usage of desired layout reference (e.g. R.layout.main in your Activity or Fragment), then `Generate` and `Generate Afinal Injections`
 2. Pick injections you want, you also have an option to create ViewHolder for adapters.
 3. Click `Confirm` and enjoy injections in your code with no work!


## How to build the code

- follow [Getting Started with Plugin Development](http://confluence.jetbrains.com/display/IDEADEV/Getting+Started+with+Plugin+Development)
- make sure you have Java 6 installed if you want to publish it in the plugin repository

## Other's work

- [IDEA code generator](https://github.com/kurganec/intellij-android-codegenerator/) by Anatoly Korniltsev
- [butter knife generator](https://github.com/inmite/android-butterknife-zelezny) by inmite