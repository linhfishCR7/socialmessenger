# Social Messenger

Secure messaging app with group chats, media sharing, and end-to-end encryption

## 📱 App Information

- **Package Name:** `com.lehau.SocialMessenger`
- **Category:** social
- **Platform:** Android (Cordova/PhoneGap)
- **Version:** 1.0.0

## 🚀 Features

- Secure messaging
- Group chats
- Media sharing
- End-to-end encryption

## 🛠️ Build Instructions

### Prerequisites

- Node.js (v14 or higher)
- Apache Cordova CLI
- Android SDK (for Android builds)

### Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/linhfishCR7/SocialMessenger.git
   cd SocialMessenger
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Add platforms:
   ```bash
   cordova platform add android
   ```

4. Build the app:
   ```bash
   cordova build android
   ```

### Development

- **Run on device/emulator:**
  ```bash
  cordova run android
  ```

- **Build for production:**
  ```bash
  cordova build android --release
  ```

## 📦 Plugins Used

- `cordova-plugin-camera`
- `cordova-plugin-file`
- `cordova-plugin-contacts`
- `cordova-plugin-media`

## 🚀 Deployment

This repository is configured to work with third-party build services like:

- **PhoneGap Build**
- **Monaca**
- **Ionic Appflow**

Simply push this repository to your preferred build service to generate APK files.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**LinhFish Development Team**
- GitHub: [@linhfishCR7](https://github.com/linhfishCR7)
- Email: dev@linhfish.com

---

Built with ❤️ using Apache Cordova