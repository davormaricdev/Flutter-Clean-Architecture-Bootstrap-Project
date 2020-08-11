### Flutter Clean Architecture Bootstrap project

Bootstrap project for Clean Architecture based Flutter projects.

## Tips and known bugs

# IntellJ multi-module setup 
It is convenient to have a single project that contains each sub-project as a module. In case this becomes an issue, follow these steps:

- Open project settings (cmd+;)
- Open "Modules" page
- Remove the exisiting module(s)
- Click "+" and select {root}/module/{module_name}.iml file
- Do this for all modules
After Step 3 Intellij will need the Flutter SDK to be set again. Go to Preferences (cmd+,) and re-select your flutter SDK path

# Get dependencies bar inside pubspec.yaml
This is a bug. In order to get new dependencies, you can either run `flutter pub get` from module folder or by going to Tools -> Flutter -> Flutter Pub Get