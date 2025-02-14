# Expo Go Setup Guide

## Prerequisites
Before installing Expo Go, ensure you have the following installed:

- **Node.js LTS**: Download and install from [Node.js official site](https://nodejs.org/).
- **VS Code**: Download and install from [VS Code official site](https://code.visualstudio.com/).
- **Compatible Operating System**: macOS, Linux, or Windows.
- **Physical Mobile Device**: Android or iOS.

## Why Use Expo Go?

Expo Go simplifies the mobile development and testing process by allowing you to run React Native applications directly on your physical device without needing an emulator. It supports both **Android** and **iOS** devices, making it a cost-effective and efficient solution.

## Steps to Install Expo Go

### 1. Install Expo CLI (Command Line Interface)

Run the following command in your terminal to install Expo CLI globally:

```sh
npm install -g expo-cli
```

Verify the installation by running:

```sh
expo --version
```

### 2. Install Expo Go on Your Mobile Device

#### **For Android Users:**
1. Open **Google Play Store**.
2. Search for **Expo Go**.
3. Click **Install**.

#### **For iOS Users:**
1. Open **Apple App Store**.
2. Search for **Expo Go**.
3. Click **Get** to install.

### 3. Create an Expo Account
1. Open the **Expo Go** app.
2. Click **Sign Up** (or Log in if you already have an account).
3. Complete the registration process.

### 4. Set Up a New Expo Project
Run the following command in your terminal to create a new Expo project:

```sh
expo init my-first-app
```

Navigate to your project directory:

```sh
cd my-first-app
```

Start the development server:

```sh
expo start
```

### 5. Connect Expo Go with Your Project
1. Open **Expo Go** on your mobile device.
2. Scan the QR code displayed in your terminal using your device’s camera (or manually enter the provided link in Expo Go).
3. Your React Native app should now launch on your physical device.




