
# 🍱 Food App

A modern **React Native** application built with **TailwindCSS**, designed to deliver a smooth and visually appealing food ordering experience.  
This project focuses on elegant UI, responsive layouts, and fast performance — ideal for learning and production use.

---

## 🚀 Features

- 📱 **Cross-platform:** Works on both Android and iOS  
- 🎨 **Styled with TailwindCSS:** Clean, utility-first design system  
- ⚡ **Fast Refresh:** Instant code updates during development  
- 🍔 **Food browsing UI:** Explore meals with images, prices, and details  
- 🔍 **Search and filtering:** Quickly find your favorite dishes  
- 🛒 **Cart management:** Add, remove, and review orders in real time  

---

## 🛠️ Tech Stack

- [React Native](https://reactnative.dev/) – Core framework  
- [Expo](https://expo.dev/) – Development environment and build tools  
- [TailwindCSS](https://tailwindcss.com/) – Utility-first CSS framework via [NativeWind](https://www.nativewind.dev/)  
- [React Navigation](https://reactnavigation.org/) – App routing and navigation  
- [Expo Icons](https://icons.expo.fyi/) – Icon library for UI design  

---

## 📦 Installation

Clone the repository and install dependencies:

bash
git clone https://github.com/mvdevelop/food-app.git
cd food-app
npm install
Or with Yarn:
bash
yarn install

## ▶️ Running the App

Start the Expo development server:

bash
npx expo start
Then:

Open the Expo Go app on your Android or iOS device.

Scan the QR code shown in your terminal or browser.

The Food App will launch instantly.

## 💅 TailwindCSS Setup (via NativeWind)
This project uses NativeWind for TailwindCSS styling in React Native.

You can customize styles in your tailwind.config.js file:

js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./App.{js,jsx,ts,tsx}", "./src/**/*.{js,jsx,ts,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};

## 📁 Project Structure
bash
food-app/
├── assets/             # Images, fonts, and icons
├── src/
│   ├── components/     # Reusable UI components
│   ├── screens/        # App screens (Home, Details, Cart, etc.)
│   ├── navigation/     # Navigation configuration
│   └── utils/          # Helper functions
├── App.js              # Main app entry
├── tailwind.config.js  # TailwindCSS configuration
└── package.json

## 🧩 Scripts
Command	Description
npm start	Start the Expo development server
npm run android	Run on Android device or emulator
npm run ios	Run on iOS simulator
npm run web	Run on web (experimental)

## 📸 Screenshots
Add screenshots or GIFs of your app here.

## 🤝 Contributing
Contributions are welcome!
Feel free to open issues or submit pull requests to help improve the project.

## 🧑‍💻 Author
mvdevelop

## 📜 License
This project is licensed under the MIT License.
See the LICENSE file for more details.
