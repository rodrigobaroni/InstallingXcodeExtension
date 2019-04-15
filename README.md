# InstallingXcodeExtension
How to install Xcode extensions

# Installation
1. Clone or download the repo
2. run ``pod install`` if needed
3. Open ``YourExtension.xcodeproj`` or ``YourExtension.xcworkspace``
4. Enable target signing for both the Application and the Source Code Extension using your own developer ID
5. Select the application target and then Product > Archive
6. Export the archive as a macOS App
7. Run the app, then quit (Don't delete the app, put it in a convenient folder)
8. Go to System Preferences -> Extensions -> Xcode Source Editor and enable the ``YourExtension`` extension
9. The menu-item should now be available from Xcode's Editor menu

# Uninstallation
1. Remove the App, restart Xcode.

# List of Xcode Extensions 

* [List Xcode Extensions](https://github.com/theswiftdev/awesome-xcode-extensions)

# Extension you need to add to your project

* [Paste JSON as Code (quicktype)](https://github.com/quicktype/quicktype-xcode) – Paste JSON as Swift, Java, C++ or Obj-C++ models and serialization helpers.


