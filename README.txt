Galaxy Striker - Android APK বানানোর নির্দেশনা
=============================================

১. Android Studio ইনস্টল করুন (developer.android.com/studio)।
২. File > Open করে এই GalaxyStriker-android ফোল্ডারটি খুলুন।
৩. Gradle sync শেষ হতে দিন। লাগলে AppCompat লাইব্রেরি যোগ করুন:
   app/build.gradle-এর dependencies ব্লকে লিখুন:
       implementation 'androidx.appcompat:appcompat:1.7.0'
৪. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
৫. APK পাবেন: app/build/outputs/apk/debug/app-debug.apk
৬. Release APK (Play Store-এর জন্য): Build > Generate Signed App Bundle / APK।

ফোনে ইনস্টল করতে "অজানা উৎস থেকে ইনস্টল" অনুমতি দিতে হবে।

দ্রষ্টব্য: ল্যান্ডস্কেপ/পোর্ট্রেট ও আইকনের জন্য mipmap PNG-এর ব্যবস্থা এখনো যোগ করা হয়নি।
সবচেয়ে সহজ উপায়: Android Studio-তে New > Image Asset দিয়ে space_shooter_icon.png থেকে ic_launcher তৈরি করুন।
