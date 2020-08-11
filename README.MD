# Flutter Clean Architecture Bootstrap project

Bootstrap project for Clean Architecture based Flutter projects.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view Flutter's [online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Getting started
1. Clone this project
2. Run inside Android Studio
3. Open preferences (<kbd>cmd</kbd> + <kbd>,</kbd>) and setup Dart SDK path under <kbd>Languages &amp; Frameworks</kbd> -> <kbd>Dart</kbd> -> <kbd>Dart SDK path</kbd> and enable Dart support for all modules.
4. Open preferences (<kbd>cmd</kbd> + <kbd>,</kbd>) and setup Flutter SDK path under <kbd>Languages &amp; Frameworks</kbd> -> <kbd>Flutter</kbd> -> <kbd>Flutter SDK path</kbd> 
 
## Tips and known bugs

### Adding a new module
In order to add a new module, run `flutter create --template=package {moduleName}` from the root folder of the project.

### IntellJ multi-module setup 
It is convenient to have a single project that contains each sub-project as a module. In case this becomes an issue, follow these steps:

- Open project settings (<kbd>cmd</kbd> + <kbd>;</kbd>)
- Open <kbd>Modules</kbd> page
- Remove the exisiting module(s)
- Click <kbd>+</kbd> and select {root}/module/{module_name}.iml file
- Do this for all modules

### Get dependencies bar inside pubspec.yaml
This is a bug. In order to get new dependencies, you can either run `flutter pub get` from module folder or by going to <kbd>Tools</kbd> -> <kbd>Flutter</kbd> -> <kbd>Flutter Pub Get</kbd>

### Frameworks Detected: Android framework is detected.
This is a bug. Safely ignore.
