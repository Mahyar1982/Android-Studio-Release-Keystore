# How to create key store in Android studio



### First we need to build a signed APK (Build > Generate Signed APK)

### We need the following information:

#### Key store path
#### Key store password
#### Key Alias
#### Key Alias password

### Open Command prompt

#### Navigate to Java/bin/

##### by typing "keytool" and press enter, I can check possible commands

#### keytool -list -v -keystore "Your key store location path" -alias "ALIAS NAME" -storepass "Keystore password" -keypass "Alias password"

### For Example:

##### C:\Program Files (x86)\Java\jdk1.8.0_161\bin>keytool -list -v -keystore "C:\Mahyar\projects\signed apk\realITProject.jks" -alias "key0" -storepass "123456" -keypass "123456"

##### Reference:
###### https://www.youtube.com/watch?v=KsHKCeh4pg4
