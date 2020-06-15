# flutter_boilerplate

This project is a minimal boilerplate code that displays hello world

#### After cloning this repo, follow the steps given below
1. Go to **pubspec.yaml** and under **name** change the package name from **flutter_boilerplate** to your project name 
2. Go to **AndroidManifest.xml** in _android/app/src/main_ and change the **android:label** and **package** values to your _app's display name_ and _package name_ respectively.
3. Change the **applicationID** in _android/app/build.gradle_ with your _package_ name. *(It should match with _package_ value in _AndroidManifest.xml_ else it'll throw an error)*
4. run _flutter clean_ in your terminal

If you find the steps to be a bit complex then [go here]

[go here]: https://stackoverflow.com/questions/51534616/how-to-change-package-name-in-flutter
