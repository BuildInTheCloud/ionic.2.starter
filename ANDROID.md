# android build and test
1. run `ionic platform add android`. (RUN ONCE)
2. run visual studio emulator for android
3. click on `debug` in `VS Code` and select `Run Android on device`. requires (Cordova tools to be installed in VS Code.)


# android release
1. ionic build android --release
2. androind-key-gen.bat (ONLY RUN ONCE)
3. androind-apk-sign.bat
4. androind-apk-zipalign.bat
5. login to https://play.google.com/apps
6. upload platforms\android\build\outputs\apk\android-release-signed.apk

