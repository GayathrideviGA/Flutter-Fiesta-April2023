# Understanding Modules of Flutter Project for Seamless App Communication

In a Flutter project, there are several files and folders present that are related to the native modules of the app. These native modules are specific to the target platform of the app, such as Android, iOS, or web.

## Android 🤖

The `android/` folder contains the Android-specific code of the app. It includes the `AndroidManifest.xml` file, which declares various metadata about the app, such as its name, version, permissions, and activities. It also includes the `build.gradle` file, which defines the app's build process and dependencies. Additionally, there may be other folders, such as `java/` and `res/`, which contain Java/Kotlin code and resources, respectively.

- `AndroidManifest.xml`: an XML file that provides essential information about the app to the Android system
- `build.gradle`: a Groovy script that defines the app's build process and dependencies
- `java/`: contains Java or Kotlin code that is specific to the Android platform
- `res/`: contains Android resources such as images, icons, and layouts that are used in the app

## iOS 🍎

The `ios/` folder in a Flutter project contains all the iOS-specific code that is required to build and run the app on an iOS device or simulator. This folder is only present in Flutter projects that are intended to be run on iOS devices. The folder contains various files and subdirectories that are necessary for building and running the app on an iOS device or simulator.

- `Info.plist`: a mandatory file that must be present in any iOS app
- `Podfile`: a file that is used to manage dependencies for iOS apps that are built using CocoaPods
- `Runner/`: a subdirectory that contains the Xcode project file for the iOS app

## Web 🌐

The `web/` folder in a Flutter project contains all the code and resources required to build and run the app on the web platform.

- `index.html`: the entry point for the app's web page
- `main.dart`: the entry point for the app's Dart code
- `assets/`: contains static assets such as images, fonts, and stylesheets used in the app

### Other Files and Folders

- `.idea/`: contains settings related to the code editor you are using to build the application
- `lib/`: the most important folder in the project, used to write most of the dart code
- `.gitignore`: a file that stores files that are hidden from the IDE and need to be ignored when a project is uploaded to version control platforms like GitHub
- `.metadata`: a file that contains metadata required by the Flutter tool to track the Flutter project
- `.packages`: a file that holds the path to every package and library used in the project
- `pubspec.lock`: a file that contains the version of each dependency and packages used in the Flutter application
- `pubspec.yaml`: a file that we use to add metadata and configuration specific to our application
- `README.md`: a markdown file that is used to describe your application in the GitHub repository

Link for package explained as demo during the session: [external_app_launcher](https://github.com/GayathrideviGA/external_app_launcher)

### Get in touch:
- Connect with me on Twitter [@gayuga99](https://twitter.com/gayuga99)
- Connect with me on LinkedIn  [Gayathri Devi Srinivasan](https://www.linkedin.com/in/gayathri-devi-srinivasan-961bbb147/)

