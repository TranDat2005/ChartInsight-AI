<div align="center">

# 📊 ChartInsight AI

### AI-Powered Trading Chart Analysis for Crypto & Commodities

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.0+-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Gemini_AI-1.5_Pro-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS-lightgrey?style=for-the-badge)

<p align="center">
  <img src="https://img.shields.io/badge/State_Management-GetX-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/API-Google_Gemini-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Architecture-Clean_Architecture-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Design-Glassmorphism-pink?style=flat-square" />
</p>

**Upload a trading chart. Get instant AI-powered insights. Make smarter trading decisions.**

[🚀 Features]() • [📱 Screenshots]() • [🛠️ Installation]() • [📚 Documentation]() • [🤝 Contributing]()

---

</div>

## 📖 Overview

**ChartInsight AI** is a cutting-edge mobile application that leverages Google's Gemini 1.5 Pro multimodal AI to analyze trading charts for cryptocurrencies, gold, forex, and other financial instruments. Simply upload or capture a chart screenshot, and receive comprehensive technical analysis with actionable trade suggestions.

### 🎯 Problem Statement

Traders spend hours analyzing charts manually, often missing critical patterns or support/resistance levels. ChartInsight AI democratizes professional-grade technical analysis by providing instant, AI-powered insights accessible to everyone.

### 💡 Solution

A beautiful, intuitive mobile app that:
- ✅ Analyzes any trading chart in seconds
- ✅ Identifies patterns, trends, and key levels
- ✅ Suggests trades with entry, stop loss, and take profit levels
- ✅ Works offline after analysis (results are cached)
- ✅ Supports multiple asset classes

---

## ✨ Features

### 🤖 AI-Powered Analysis
- **Multimodal AI**: Uses Google Gemini 1.5 Pro for advanced image + text understanding
- **Comprehensive Insights**: Detects asset type, timeframe, trend direction, patterns
- **Trade Signals**: Provides BUY/SELL/HOLD recommendations with specific levels
- **Risk Assessment**: Highlights potential risks and considerations

### 📸 Image Handling
- **Multiple Input Methods**: Gallery upload or camera capture
- **Image Preview**: Review your chart before analysis
- **Format Support**: JPEG, PNG, and other common image formats
- **Compression**: Optimized image handling for faster uploads

### 🎨 Modern UI/UX
- **Glassmorphism Design**: Beautiful frosted glass effects
- **Dark Mode**: Eye-friendly dark theme
- **Smooth Animations**: Polished transitions and loading states
- **Responsive Layout**: Adapts to phones, tablets, and foldables
- **Custom Components**: Reusable, accessible UI elements

### 🏗️ Technical Excellence
- **GetX State Management**: Reactive, high-performance state handling
- **Clean Architecture**: Separation of concerns for maintainability
- **Error Handling**: Comprehensive error messages and recovery
- **Type Safety**: Full Dart null safety implementation
- **Offline Support**: View previous analyses without internet

---

## 📱 Screenshots

<div align="center">

| Upload Screen | Analyzing | Results Screen |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/7eb9b5dd-f642-4a1b-82f1-2ffbeb3323a3" width="250"> | <img src="https://github.com/user-attachments/assets/c50b9e23-3977-442a-a249-4245baa72bab" width="250"> | <img src="https://github.com/user-attachments/assets/96e60b26-962f-4ece-971a-050f3eca5af4" width="250"> |

| Chart Preview | Trade Signal | Analysis Details |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/279b8db7-5e43-4bc5-a688-22f717f84339" width="250"> | <img src="https://github.com/user-attachments/assets/36adb45c-0d2a-4a28-9ce3-c09e6c3c0e0b" width="250"> | <img src="https://github.com/user-attachments/assets/faa9522a-6f58-4c92-95e5-ad6cefc45f5f" width="250"> |

</div>


---

## 🛠️ Tech Stack

### Frontend
- **Framework**: Flutter 3.x
- **Language**: Dart 3.0+
- **State Management**: GetX 4.6+
- **UI Components**: Custom glassmorphism widgets
- **Typography**: Google Fonts (Poppins)
- **Animations**: Lottie, AnimatedSwitcher, FadeTransition

### Backend & APIs
- **AI Model**: Google Gemini 1.5 Pro (Multimodal)
- **HTTP Client**: Dio 5.5+
- **Image Handling**: image_picker 1.1+
- **Environment Config**: flutter_dotenv 5.1+

### Architecture
- **Pattern**: GetX MVC with Clean Architecture
- **Routing**: GetX Named Routes
- **Dependency Injection**: GetX Bindings
- **Data Layer**: Service-Repository pattern

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have:

- ✅ **Flutter SDK** 3.0 or higher ([Install Flutter](https://docs.flutter.dev/get-started/install))
- ✅ **Dart** 3.0 or higher (comes with Flutter)
- ✅ **Android Studio** / **Xcode** for emulators
- ✅ **Google Gemini API Key** ([Get API Key](https://makersuite.google.com/app/apikey))
- ✅ **Git** for version control

### System Requirements

| Platform | Minimum Version |
|----------|----------------|
| Android  | 6.0 (API 23)   |
| iOS      | 12.0           |
| Flutter  | 3.0.0          |
| Dart     | 3.0.0          |

---

## 📥 Installation

### 1️⃣ Clone the Repository

```
# HTTPS
git clone https://github.com/yourusername/chartinsight-ai.git

# SSH
git clone git@github.com:yourusername/chartinsight-ai.git

# Navigate to project
cd chartinsight-ai
```

### 2️⃣ Install Dependencies

```
# Get all Flutter packages
flutter pub get

# Verify installation
flutter doctor -v
```

### 3️⃣ Platform-Specific Setup
#### Android Setup
- No additional configuration needed! Permissions are already configured in AndroidManifest.xml.
```
cd ios
pod install
cd ..
```
- Ensure Info.plist has the required permissions (already included).



### 4️⃣ Run the App

```
# List available devices
flutter devices

# Run on connected device
flutter run

# Run in release mode
flutter run --release

# Run on specific device
flutter run -d <device_id>
```

## 📂 Project Structure

```
chartinsight_ai/
├── lib/
│   ├── main.dart                          # App entry point
│   ├── app/
│   │   ├── bindings/                      # GetX dependency injection
│   │   │   ├── upload_binding.dart
│   │   │   └── result_binding.dart
│   │   ├── controllers/                   # GetX controllers (business logic)
│   │   │   ├── upload_controller.dart
│   │   │   └── result_controller.dart
│   │   ├── data/
│   │   │   ├── models/                    # Data models
│   │   │   │   └── analysis_result.dart
│   │   │   └── services/                  # API services
│   │   │       └── ai_service.dart
│   │   ├── routes/                        # Navigation configuration
│   │   │   ├── app_pages.dart
│   │   │   └── app_routes.dart
│   │   └── ui/
│   │       ├── pages/                     # Screen widgets
│   │       │   ├── upload_page.dart
│   │       │   └── result_page.dart
│   │       ├── widgets/                   # Reusable components
│   │       │   ├── glass_card.dart
│   │       │   ├── custom_button.dart
│   │       │   └── analysis_card.dart
│   │       └── theme/                     # App theming
│   │           └── app_theme.dart
├── assets/
│   └── lottie/                            # Animation files
│       └── ai_loader.json
├── android/                               # Android native code
├── ios/                                   # iOS native code
├── test/                                  # Unit & widget tests
├── .gitignore                             # Git ignore rules
├── pubspec.yaml                           # Dependencies
└── README.md                              # This file
```

## 🎮 Usage Guide
### Basic Workflow
- Launch App → Opens on Upload Screen
- Select Chart → Choose "Upload from Gallery" or "Capture with Camera"
- Preview → Review the selected chart image
- Analyze → Tap "Analyze Now" button
- Wait → AI processes the chart (5-15 seconds)
- View Results → See comprehensive analysis and trade signal
- New Analysis → Tap "Try Another Chart" to start over

### Understanding Results
#### Trade Signal Card
- 🟢 BUY: Bullish bias with entry/SL/TP levels
- 🔴 SELL: Bearish bias with entry/SL/TP levels
- 🟡 HOLD: Neutral or unclear direction

### Analysis Sections
- Asset: Detected cryptocurrency/commodity (e.g., BTC/USD, Gold)
- Timeframe: Chart period (e.g., 1H, 4H, Daily)
- Trend: Overall direction (Bullish/Bearish/Neutral)
- Support: Key support levels to watch
- Resistance: Key resistance levels to watch
- Pattern: Identified chart patterns (e.g., Head & Shoulders, Triangle)
- Risks: Potential risks and considerations

## 🏛️ Architecture
### Design Pattern: GetX MVC + Clean Architecture
```
┌─────────────────────────────────────────────────────┐
│                    UI LAYER                         │
│  (Pages, Widgets, Theme)                            │
│  - upload_page.dart                                 │
│  - result_page.dart                                 │
│  - Reusable widgets                                 │
└─────────────────┬───────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────────────────────┐
│              CONTROLLER LAYER                       │
│  (Business Logic, State Management)                 │
│  - UploadController                                 │
│  - ResultController                                 │
│  - GetX reactive state                              │
└─────────────────┬───────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────────────────────┐
│                DATA LAYER                           │
│  (Services, Repositories, Models)                   │
│  - AIService (API calls)                            │
│  - AnalysisResult model                             │
└─────────────────┬───────────────────────────────────┘
                  │
                  ▼
┌─────────────────────────────────────────────────────┐
│              EXTERNAL APIs                          │
│  - Google Gemini 1.5 Pro                            │
└─────────────────────────────────────────────────────┘
```

### Key Components
#### 1. Controllers
Handle business logic and state management:
- UploadController: Manages image selection and analysis trigger
- ResultController: Displays and formats analysis results

#### 2. Services
Encapsulate external API communication:
- AIService: Gemini API integration with retry logic
  
#### 3. Models
Define data structures:
- AnalysisResult: Structured AI response data
- SuggestedTrade: Trade recommendation details

#### 4. Bindings
Manage dependency injection:
- Lazy loading of controllers
- Automatic disposal


## 🤖 API Integration
#### Google Gemini 1.5 Pro
- Endpoint: https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-pro:generateContent
* Request Structure:
```
{
  "contents": [
    {
      "parts": [
        {
          "text": "Analyze this chart and return JSON with asset, timeframe, trend, support, resistance, pattern, suggested_trade (bias, entry, stop_loss, take_profit), risks, and disclaimer."
        },
        {
          "inline_data": {
            "mime_type": "image/jpeg",
            "data": "<BASE64_ENCODED_IMAGE>"
          }
        }
      ]
    }
  ],
  "generationConfig": {
    "temperature": 0.4,
    "topK": 32,
    "topP": 1,
    "maxOutputTokens": 2048
  }
}
```
* Response Structure:
```
{
  "candidates": [
    {
      "content": {
        "parts": [
          {
            "text": "{\"asset\":\"BTC/USD\",\"timeframe\":\"4H\",...}"
          }
        ]
      }
    }
  ]
}
```

## API Configuration
### Features:
- ✅ Multimodal input (image + text)
- ✅ Automatic retry on failure
- ✅ Model fallback mechanism
- ✅ Response validation
- ✅ Error handling with user-friendly messages

### Rate Limits:
- Free Tier: 60 requests/minute
- For production: Consider upgrading to paid tier


## 📄 License
### This project is licensed under the MIT License - see the LICENSE file for details.

```
MIT License

Copyright (c) 2024 ChartInsight AI

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```


## 🙏 Acknowledgments
### Technologies
- Flutter - UI framework
- GetX - State management
- Google Gemini - AI model
- Dio - HTTP client
  
### Inspiration
- TradingView for chart analysis concepts
- Modern fintech apps for UI/UX inspiration
- Flutter community for best practices

### Contributors
- Thanks to all contributors who help improve ChartInsight AI!

<a href="https://github.com/amirbayat0/chartinsight-ai/graphs/contributors"> <img src="https://contrib.rocks/image?repo=amirbayat0/ChartInsight-AI" /> </a>


## 📞 Support & Contact

### Get Help
- 📧 Email: amirbayat.dev@gmail.com
 
### Report Issues
- Found a bug? Open an issue

### Feature Requests
- Have an idea? Submit a feature request


## ❓ FAQ
<details> <summary><strong>Is this app free to use?</strong></summary>
Yes! The app is completely free. You only need a free Google Gemini API key (60 requests/min).

</details><details> <summary><strong>Does it work offline?</strong></summary>
Analysis requires internet to connect to Gemini API. However, you can view previously analyzed charts offline.

</details><details> <summary><strong>Is the analysis accurate?</strong></summary>
The AI provides educated insights based on technical analysis principles. However, this is NOT financial advice. Always do your own research.

</details><details> <summary><strong>What chart types are supported?</strong></summary>
Any screenshot of candlestick, line, or bar charts for crypto, forex, stocks, or commodities.

</details><details> <summary><strong>Can I use this for live trading?</strong></summary>
This tool is for educational purposes only. Use at your own risk. Past performance doesn't guarantee future results.

</details><details> <summary><strong>How do I get a Gemini API key?</strong></summary>
Visit Google AI Studio, sign in, and click "Create API Key". It's free!

</details><details> <summary><strong>Can I contribute to this project?</strong></summary>
Absolutely! See the Contributing section. We welcome all contributions.

</details>


## ⚖️ Disclaimer
### IMPORTANT: This application is for educational and informational purposes only.

- ❌ NOT financial advice
- ❌ NOT investment recommendations
- ❌ NOT guaranteed to be accurate
- Trading and investing involve substantial risk of loss. Always:

- ✅ Do your own research (DYOR)
- ✅ Consult with licensed financial advisors
- ✅ Never invest more than you can afford to lose
- ✅ Understand the risks involved
- The developers are not responsible for any financial losses incurred using this app.


<div align="center">

### ⭐ Star this repo if you find it helpful!  

**Made with ❤️ by Flexz**

</div>









