# Social Messenger

Secure messaging app with group chats, media sharing, and end-to-end encryption

## 📱 App Information

- **Package Name:** `com.lehau.SocialMessenger`
- **Category:** social
- **Platform:** Android (Apache Cordova)
- **Version:** 1.0.0

## 🚀 Features

- Secure messaging
- Group chats
- Media sharing
- End-to-end encryption

## 🛠️ Build Instructions

### Prerequisites

- Node.js (v16 or higher)
- Apache Cordova CLI: `npm install -g cordova`
- Android SDK and Android Studio
- **Vega SDK v0.20 or newer** (for Vega device compatibility)

### Local Development

1. **Clone and setup:**
   ```bash
   git clone <repository-url>
   cd SocialMessenger
   npm install
   ```

2. **Add Android platform:**
   ```bash
   cordova platform add android
   ```

3. **Build for development:**
   ```bash
   cordova build android
   ```

4. **Run on device/emulator:**
   ```bash
   cordova run android
   ```

5. **Build for production:**
   ```bash
   cordova build android --release
   ```

### CI/CD with Codemagic

This project includes a `codemagic.yaml` configuration for automated builds:

1. Connect your repository to [Codemagic](https://codemagic.io)
2. The build will automatically:
   - Install dependencies
   - Add Android platform
   - Build release APK/AAB
   - Generate artifacts

## 📦 Plugins Used

- `cordova-plugin-camera`
- `cordova-plugin-file`
- `cordova-plugin-contacts`
- `cordova-plugin-media`

## 🎯 Device Compatibility

### Vega Device Support

This app is built with **Vega SDK v0.20 or newer** compatibility:

- ✅ Supports Vega devices with SDK v0.20+
- ✅ Optimized for Vega processor architecture
- ✅ Compatible with standard Android devices
- ✅ Minimum Android SDK: 33
- ✅ Target Android SDK: 35

**Note:** Ensure your Vega device is running SDK version 0.20 or newer for optimal performance and compatibility.

## 🏗️ Project Structure

```
SocialMessenger/
├── www/                 # Web assets
│   ├── css/            # Stylesheets
│   ├── js/             # JavaScript files
│   ├── img/            # Images and icons
│   └── index.html      # Main HTML file
├── platforms/          # Platform-specific code (auto-generated)
├── plugins/            # Cordova plugins (auto-generated)
├── config.xml          # Cordova configuration
├── package.json        # Node.js dependencies
├── codemagic.yaml      # CI/CD configuration
└── README.md           # This file
```

## 📄 License

This project is licensed under the MIT License.

## 👨‍💻 Author

**LinhFish Development Team**
- Email: dev@linhfish.com

---

Built with ❤️ using Apache Cordova and the Cordova App Generator