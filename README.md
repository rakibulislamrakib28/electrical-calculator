# Electrical Load Calculator - Android APK Project

এটি Capacitor ভিত্তিক Android app project। মূল calculator UI `www/index.html`-এ আছে।

## GitHub থেকে APK বানানো

1. এই project-এর সব ফাইল GitHub repository-তে upload করুন।
2. GitHub repository-তে Actions খুলুন।
3. `Build Android APK` workflow চালু করুন।
4. কাজ শেষ হলে Actions-এর workflow run থেকে APK artifact download করুন।

## Local build

```bash
npm install
npx cap add android
npx cap sync android
```

তারপর Android Studio দিয়ে `android` folder খুলে APK build করা যাবে।

> Calculator-এর ফলাফল আনুমানিক। বাস্তব electrical installation-এর ক্ষেত্রে cable ampacity, cable length, voltage drop, installation method, breaker characteristics এবং স্থানীয় electrical code যাচাই করা প্রয়োজন।
