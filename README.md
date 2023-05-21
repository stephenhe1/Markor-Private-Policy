# Markor-Private-Policy
## Markor - Note and Todo List: Privacy policy

Welcome to the Markor - Note and Todo List for Android!

This app will be available on Google Play soon.

As an avid Android user myself, I take privacy very seriously.
I know how irritating it is when apps collect your data without your knowledge.

I hereby state, to the best of my knowledge and belief, that I have not programmed this app to collect any personally identifiable information. All data (created by you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

```xml
<uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
<uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
<uses-permission 
android:name="android.permission.INTERNET" />
<uses-permission android:name="com.android.launcher.permission.INSTALL_SHORTCUT" />
<uses-permission 
android:name="android.permission.RECORD_AUDIO" />
```

<br/>

|                    Permission                    | Why it is required                                           |
| :----------------------------------------------: | ------------------------------------------------------------ |
|    android.permission.WRITE_EXTERNAL_STORAGE     | Allows my application to write to external storage.          |
|    `android.permission.READ_EXTERNAL_STORAGE`    | Allows my application to read from external storage.         |
| com.android.launcher.permission.INSTALL_SHORTCUT | Allows my application to install a shortcut in Launcher.     |
|           android.permission.INTERNET            | Allows my application to open network sockets. Markor does not use your internet connection unless the user-generated content references external resources (for example, when you reference an external image by URL). |
|        `android.permission.RECORD_AUDIO`         | Attach voice notes to the text. The permission is only used after click on the "attach audio" button, at the audio record dialog. Audio recording is always started and stopped manually by you (button press). |

 <hr style="border:1px solid gray">


If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email , and I will surely try to fix it/help you.

Yours sincerely,  
Seal Accessibility.  
Irvine, CA, USA.  
2023seal@gmail.com
