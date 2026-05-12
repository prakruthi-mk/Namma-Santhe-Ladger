# Project Report: Namma-Santhe Ledger

## 1. Executive Summary
**Namma-Santhe Ledger** is a modern, secure, and AI-powered financial management application designed specifically for local market dealers (Santhe). The application digitizes traditional credit-tracking (Udari) systems, offering dealers a professional tool to manage their business with precision and security.

## 2. Key Features

### 🚀 AI Receipt & Bill Scanner
- **Technology**: Integrated **Google ML Kit (Text Recognition)**.
- **Functionality**: Dealers can tap the camera icon to snap a photo of a physical bill. The AI automatically extracts the total amount and fills the transaction field, saving time and preventing typing errors.

### 🔐 Multi-Layer Security
- **Dealer Authentication**: Dedicated Sign-In and Sign-Up screens allowing multiple dealers to have private accounts.
- **Biometric Unlock**: Integrated **Android Biometric API** for Fingerprint, Face, or PIN unlock every time the app opens, ensuring financial data is protected.
- **Data Isolation**: A robust database architecture ensures that Dealer A can never see Dealer B's customers or transactions.

### 🌍 Dual-Language Support (English & Kannada)
- **Full Localization**: Complete support for **English** and **ಕನ್ನಡ (Kannada)**.
- **Smart Reminders**: Automated WhatsApp and SMS payment reminders are sent in the dealer's chosen language.
- **User Preference**: The app remembers the language choice per user and allows changing it upon logout.

### 📱 Premium UI/UX Design
- **Material 3 Interface**: Built with Jetpack Compose using a professional **Deep Teal and Gold** theme.
- **Dealer Dashboard**: A high-impact dashboard showing "Total Outstanding" and "Today's Sales" using high-contrast stat cards.
- **Performance**: Optimized data loading patterns to ensure a glitch-free experience when navigating through customer profiles.

## 3. Technical Stack
- **Framework**: Kotlin & Jetpack Compose (UI)
- **Architecture**: MVVM (Model-View-ViewModel) for clean, maintainable code.
- **Database**: Room Persistence Library with multi-user schema support.
- **AI Engine**: Google Play Services ML Kit.
- **Session Management**: Persistent sessions via SharedPreferences.

## 4. Impact for the Dealer
1. **Time Saved**: AI scanning removes the need for manual calculation.
2. **Professionalism**: Sending professional Kannada/English reminders builds trust with customers.
3. **Security**: Financial records are no longer in an open book; they are locked behind biometrics.
4. **Accuracy**: Real-time sales tracking helps dealers understand their daily profit and lending.

---
*Report generated on: ${java.time.LocalDate.now()}*
