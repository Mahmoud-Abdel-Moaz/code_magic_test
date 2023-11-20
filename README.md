# code_magic_test


1- Change Package Id using change_app_package_name
 flutter pub run change_app_package_name:main com.new.package.name

2- create new keystore for new client
keytool -genkey -v -keystore ~/client-keystore.jks -keyalg RSA \
-keysize 2048 -validity 10000 -alias client
 - change mode on android build file to release mode and add singing configuration

3- create icons for app using flutter_launcher_icons
flutter pub run flutter_launcher_icons

4- create .env file with app configurations and read it by flutter_dotenv package

5- create firebase project for new client and get google_service configurations files 

6-create new group of variables for new client at code magic 

7- to encode 64 use => cat assets_red.zip | base64 | pbcopy


CM_KEYSTORE => keystore file
CM_KEYSTORE_PATH => keystore Path
CM_KEYSTORE_PASSWORD => keystore password
CM_KEY_ALIAS => keystore alias
CM_KEY_PASSWORD => key password 
CM_FIREBASE => firebase google-services file
APP_NAME => app name
PACKAGE_NAME => package name
DOTENV => .env file
CM_ASSETS => Assets Folder



