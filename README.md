Flutter Basic Commands + Cheat Sheet
Flutter Cheat Sheet
The most important Flutter Commands are listed here with a brief description of them. You can either execute Flutter Commands in the terminal on your computer or in the terminal in VS Code. If the commands are to do something with your project, it helps to be in the project folder.
 Flutter Help:
$ flutter -h
Shows you all commands with a description again in the terminal.
 Flutter Version:
$ flutter --version
Shows you your installed Flutter version.

Flutter Channel:
$ flutter channel
Shows you in which channel (branch) you are - default is channel stable. If you want to try new features you can also switch to the beta channel.

Flutter Doctor:
$ flutter doctor
Gives you the information about your development environment.  Flutter Upgrade:
$ flutter upgrade
This will update to the latest Flutter version.

Flutter Downgrade:
$ flutter downgrade <version> (example: $ flutter downgrade v2.3.2)
This allows you to downgrade to a specific version.

Neues Projekt erstellen:
$ flutter create <app name> (example: $ flutter create "myapp")
Create a new flutter project with the standard counter app.

Flutter Emulator:
$ flutter emulator
Listet dir alle verfügbaren devices.

Flutter Emulator launch:
$ flutter emulator --launch <emulator_name> (example $ flutter emulator --launch myPixel)
Starts a specific emulator (Virtual device).  Flutter Run:
$ flutter run
Starts your app on a virtual device (if available & started) in debug mode.  Flutter Release:
$ flutter run --release
Starts your app on a virtual device (if available & started) in release mode. So install a whole APK on the phone.

Flutter Clean:
$ flutter clean
Removes the files created during the build from the project (cleans up). Can sometimes help with weird behavior. However, you often have to re-enter afterwards $ flutter pub get  Flutter pub get:
$ flutter pub get
Downloads the dependencies in the project.     Commands für den Debug Modus:
These commands will help you if you have started the app from VS Code in debug mode (flutter run) with the terminal.

Big R:
Restart the app on the emulator with the code changes.
 Small r:
Hot reload: Loads code changes live.

Q:
Close the app (quit). Stops debugging.



