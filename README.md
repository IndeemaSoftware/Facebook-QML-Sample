How to use:

Include headers:

Android:
#include "android/FacebookQMLAndroid.h"

iOS:
#include "ios/FacebookQMLiOS.h"

Register QML-mematype:
qmlRegisterType("me.mnafees", 1, 0, "Facebook");

AndroidManifest.xml:
set minimum and target SDK version

gradle.properties:
set Android NDK path in systemProp.ndk_dir property

Create Facebook QML object;

Implement callbacks: onLoginSuccess, onLoginError, onLoginCancel, onShareSuccess, onShareError, onShareCancel

login() method shows native login popup
