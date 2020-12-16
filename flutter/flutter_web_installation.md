# Flutter installation for web
Using flutter 1.22

### Prerequisites
* Java JDK 14
* Flutter 
* Android Studio

### Installation steps
* Install prerequisites
* Install Android SDK Command-line
  * Android Studio -> Tools -> Sdk Manager -> Appearance & Behavior -> System Settings -> Android SDK -> Android SDK Command-line tools
* Install Android Studio Flutter and Dart plugins

### Post-installation steps
* accept flutter license
  * ```flutter doctor --android-licenses```
* set path to android studio
  * ```flutter config -- android-studio-dir=<ANDROID_STUDIO_PATH>```
* precache flutter
  * ```flutter precache --verbose ```
* enable web support
  * ```flutter channel beta```
* upgrade and precache flutter
  * ```flutter upgrade```
  * ```flutter precache```
* enable web support 
  * ```flutter config --enable-web```
  
