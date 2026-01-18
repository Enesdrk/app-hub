# 📱 Smart App Hub

A smart, lightweight landing page designed for cross-promoting mobile applications. This simple HTML/JS solution automatically detects the user's device and redirects them to the appropriate app store developer page.

---

## 🚀 Features

-   **Smart Detection**: Identifies User Agent to distinguish between iOS and Android devices.
-   **Instant Redirection**: Redirects mobile users immediately to the native store (App Store or Google Play).
-   **Desktop Fallback**: Displays a beautiful, glassmorphism-styled landing page for desktop users with links to both stores.
-   **Zero Maintenance**: Updates automatically when you publish new apps to your store profiles.

## 🛠 How It Works

1.  **Android Users** 🤖 → Redirects to `Google Play Developer Profile`.
2.  **iOS Users** 🍎 → Redirects to `Apple App Store Developer Page`.
3.  **Others (PC/Mac)** 💻 → Shows a landing page with buttons for both.

## 🔗 Integration

Add this single link to your mobile apps' "More Apps" button:

```
https://enesdrk.github.io/app-hub/
```

## 🎨 Preview

The desktop view features a modern dark-mode design with ambient lighting effects.

| Desktop View | Mobile Logic |
|:---:|:---:|
| Interactive UI | Auto-Redirect |
| Glassmorphism Style | < 0.1s Latency |

## ⚙️ Configuration

To modify the redirection targets, edit the `index.html` file:

```javascript
// inside index.html
const IOS_DEVELOPER_URL = "https://apps.apple.com/..."; 
const ANDROID_DEVELOPER_URL = "https://play.google.com/...";
```

---

*This project is built for seamless cross-promotion across my app portfolio.*
