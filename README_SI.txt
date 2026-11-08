NIROSHANA VIRTUAL PHONE - Android Studio project

මෙය Samsung-style Virtual Phone Simulator එකකි. සැබෑ Android OS එකක් නොවේ.

ඇතුළත්:
- Demo login (email format එකක් පමණක් පරීක්ෂා කරයි; password එකක් store/send කරන්නේ නැත)
- Home screen සහ built-in demo app screens
- Phone, Contacts, Messages, Camera, Gallery, Browser, Music, Video, Settings, Calculator, Notes ආදියෙහි demo interfaces

සීමාවන්:
- Calls/SMS සැබෑ ලෙස සිදු නොවේ.
- Camera එකට ප්‍රවේශ නොවේ.
- App Center එකෙන් සැබෑ Android APK install නොකරයි.
- AI Assistant එක offline demo screen එකකි.
- මෙය සැබෑ Samsung firmware හෝ Android virtualization නොවේ.

APK build කරන ආකාරය:
1. PC එකට Android Studio install කරන්න.
2. Android Studio > Open > මෙම ZIP extract කළ NIROSHANA_Virtual_Phone folder එක තෝරන්න.
3. Gradle sync අවසන් වනතුරු රැඳී සිටින්න.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) තෝරන්න.
5. APK එක app/build/outputs/apk/debug/app-debug.apk යටතේ ලැබේ.
6. APK එක Samsung Galaxy A06 වෙත යවා install කරන්න.

අවශ්‍යතා:
- Android Studio සහ Android SDK Platform 35
- JDK 17 (Android Studio bundled JBR භාවිත කළ හැක)

මෙම project එකේ demo login සඳහා සැබෑ email/password භාවිත නොකරන්න.
