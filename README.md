# 📱 DixitCoder - Wireman MCQ App  

🚀 **DixitCoder - Wireman MCQ** is an **Ionic & Vue.js-based** Android application designed for **electricians, wiremen, and IoT professionals** to test and enhance their skills through **Multiple Choice Questions (MCQs).** The app is lightweight, fast, and optimized for learning.  

## 🎯 Features  
✅ **MCQ-based Quiz** for wiremen & IoT professionals  
✅ **Category-wise Questions** (Electrical, IoT, ESP8266, etc.)  
✅ **Responsive UI** built with Ionic Framework  
✅ **Offline Support** for practicing anywhere  
✅ **Android APK** support for mobile devices  
✅ **Dark Mode UI** for a better experience  

---

## 📂 Project Structure  

```
dixitcoder-wireman-mcq/
│── .vscode/                # VS Code settings  
│── android/                # Android build files  
│── public/                 # Static files for frontend  
│── resources/              # App resources (icons, images)  
│── src/                    # Main source code (Vue.js & Ionic components)  
│── tests/                  # Test files  
│── .browserslistrc         # Browser compatibility settings  
│── .eslintignore           # ESLint ignore rules  
│── .eslintrc.cjs           # ESLint configuration  
│── .gitignore              # Git ignored files  
│── capacitor.config.ts     # Capacitor configuration for native support  
│── cypress.config.ts       # Cypress testing configuration  
│── index.html              # Main HTML entry point  
│── ionic.config.json       # Ionic project configuration  
│── package-lock.json       # Auto-generated dependency lock file  
│── package.json            # Project dependencies and scripts  
│── tsconfig.json           # TypeScript configuration  
│── tsconfig.node.json      # TypeScript configuration for Node.js  
│── vite.config.ts          # Vite build configuration  
```

---

## 📥 Installation Guide  

### ✅ 1. Prerequisites  
- Install **Node.js** and **npm**  
- Install **Ionic CLI** and **Capacitor**  
```sh
npm install -g @ionic/cli
npm install -g @capacitor/core
```

### ✅ 2. Clone the Repository  
```sh
git clone https://github.com/dixitcoder/dixitcoder-wireman-mcq.git
cd dixitcoder-wireman-mcq
```

### ✅ 3. Install Dependencies  
```sh
npm install
```

### ✅ 4. Run the App Locally  
```sh
ionic serve
```

### ✅ 5. Build Android APK  
```sh
ionic build
npx cap sync android
npx cap open android   # Opens Android Studio for APK generation
```

---

## 📌 Troubleshooting  

### ❌ **App Not Installed?**  
✅ Enable **"Install from Unknown Sources"** in Android settings.  
✅ Make sure the APK is **signed** before installing.  
✅ Try installing manually using **ADB**:  
```sh
adb install my-app.apk
```

### ❌ **Build Issues?**  
✅ Run `npm audit fix` to fix package vulnerabilities.  
✅ Ensure your **Android SDK & Java JDK** are up to date.  
✅ If issues persist, **clear cache & rebuild**:  
```sh
npm cache clean --force
rm -rf node_modules package-lock.json
npm install
ionic build
```

---

## 📞 Contact & Support  

🌐 **Website:** [DixitCoder AI Tools](https://dixitcoder-tools-ai.web.app/)  
📷 **Instagram:** [@dixitcoder](https://www.instagram.com/dixitcoder)  
📧 **Email:** dixitcoder@example.com  

---

📌 **Copy this file and paste it into your GitHub repository as `README.md`.** 🚀
