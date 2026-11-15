# BLUE PHANTOM Android Overlay — Starter v0.1

এটি একটি Android Studio source project, APK নয়। Android Studio/Gradle দিয়ে build করতে হবে।

## বর্তমান ফিচার
- Display over other apps permission
- Draggable floating BP button
- Overlay giveaway panel
- Mission যাচাই করা participant-এর নাম হাতে যোগ করা
- Entry list থেকে একজন random winner নির্বাচন
- Winner নির্বাচনের পর সেই নাম list থেকে বাদ

## সীমাবদ্ধতা
- YouTube Official app-এর live comments সরাসরি পড়া হয় না।
- YouTube API/OAuth backend এখনো যুক্ত করা হয়নি।
- Prize fulfillment admin-এর হাতে; অ্যাপ কোনো Free Fire top-up বা item পাঠায় না।
- Android/YouTube screen-capture overlay দেখায় কি না, নিজের ফোনে test করতে হবে।
- এটি development starter; production release-এর আগে testing, accessibility, privacy, foreground-service ও target SDK requirements পূরণ করতে হবে।

## Build
1. Android Studio-তে এই project folder open করুন।
2. Gradle sync সম্পন্ন করুন।
3. Build > Build Bundle(s) / APK(s) > Build APK(s)।
4. ফোনে install করার আগে নিজের build ও permission যাচাই করুন।
