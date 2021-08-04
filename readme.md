# broken-capacitor-plugins-demo

Demonstrating how to reproduce the "plugin is not implemented on android" behaviour

# Instructions

1. Replace `PUT_YOUR_API_KEY_HERE` in AndroidManifest.xml with a working google maps API key
1. Run npm install
1. Run npx cap sync
1. Run ionic cap run android
1. Observe that the map appears correctly
1. Then switch branch in this repository to `breaking-branch`
1. Run npm install to install the new packages, which is similar to my project
1. Run npx jetifier to fix another issue
1. Observe that the plugin does not load, and Android Studio Logcat reports "plugin is not implemented on android"
