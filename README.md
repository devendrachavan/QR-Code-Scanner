# 📷 QR Code Scanner App (Kotlin + ZXing)

Hello, and Welcome to the **#CodingWithDev** channel! 👋

In this tutorial, you’ll learn how to build a **QR Code Scanner App** in Android using **Kotlin** and the **ZXing library**. Whether you're building a contactless experience or integrating QR scanning into your app, this step-by-step guide shows you how to get it done quickly and efficiently.

---

## 📽️ YouTube Tutorial

▶️ **Watch the Full Video Tutorial Here**  
🔗 [https://youtu.be/gdWqDkqu3_o](https://youtu.be/gdWqDkqu3_o)

## 📽️ YouTube Channel
🎥 [Watch on YouTube](https://www.youtube.com/codingwithdev)  
> Don't forget to **👍 Like**, **👤 Share**, **✍️ Comment**, and **☝ Subscribe** to the channel for more Android tutorials!

---

## 📚 What You Will Learn

- 📦 Adding the necessary ZXing dependency for QR code scanning in your Android project.
- 🔐 Requesting camera permission dynamically and via manifest.
- 🚀 Launching the QR Code scanner using `ScanOptions` and `ScanContract`.
- 🖼️ Displaying scanned QR code content in a `TextView`.
- 💬 Handling scan results and user cancellations gracefully.

---

## 🛠 Tech Stack

- **Language**: Kotlin  
- **IDE**: Android Studio  
- **QR Scanner Library**: ZXing Android Embedded  
- **Minimum SDK**: 21+

---

## 🔧 Setup Instructions

### 1. Add ZXing Dependency

In your `build.gradle (Module)` file:

```gradle
implementation 'com.journeyapps:zxing-android-embedded:4.3.0'
