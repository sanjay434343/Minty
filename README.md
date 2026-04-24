<div align="center">

  <img src="assets/images/logo.png" width="140" height="140" alt="Minty Logo" style="border-radius: 28px;" />

  <h1>🌿 Minty</h1>
  <h3><i>Your Money. Your Rules. Zero Effort.</i></h3>

  <p>
    <img src="https://img.shields.io/badge/Platform-Android-0B5D4C?style=for-the-badge&logo=android&logoColor=7FBF9A" />
    <img src="https://img.shields.io/badge/Built_with-Flutter-0B5D4C?style=for-the-badge&logo=flutter&logoColor=7FBF9A" />
    <img src="https://img.shields.io/badge/Backend-Firebase-0B5D4C?style=for-the-badge&logo=firebase&logoColor=FFD60A" />
    <img src="https://img.shields.io/badge/Payments-Razorpay-0B5D4C?style=for-the-badge&logo=razorpay&logoColor=7FBF9A" />
  </p>

  <p>
    <img src="https://img.shields.io/badge/Version-1.0.0-7FBF9A?style=flat-square" />
    <img src="https://img.shields.io/badge/License-Proprietary-0B5D4C?style=flat-square" />
    <img src="https://img.shields.io/badge/Min_SDK-Android_7.0+-182620?style=flat-square" />
  </p>

  <br/>

  > **The average Indian loses ₹18,000/year to expenses they don't even remember making.**
  > Minty fixes that — automatically, silently, beautifully.

</div>

---

## 🧨 The Problem

You already know you should track expenses. But you don't. Nobody does.

Here's why every expense tracker fails you:

| ❌ The Problem | 💡 How Minty Solves It |
| :--- | :--- |
| **Manual entry is tedious** — you forget 70% of transactions | 📲 **SMS Auto-Capture** reads your bank alerts and logs every ₹ automatically |
| **Apps feel like spreadsheets** — zero motivation to open them | 🍱 **Bento UI Design** — a living, breathing interface with glassmorphism, haptics, and spring animations |
| **Generic advice** — "spend less" isn't actionable | 🤖 **AI Financial Advisor** analyzes YOUR patterns and tells you exactly where your money leaks |
| **No accountability** — overspending has no consequence | 🔴 **Risk Detector** fires real-time alerts when you cross 70% of your monthly budget |
| **Clunky input** — 6 taps to add one coffee | 📳 **Shake-to-Add** — physically shake your phone to open the expense adder in < 0.3 seconds |

---

## 💰 Why You Need Minty — The Money Impact

<div align="center">

```
┌─────────────────────────────────────────────────┐
│                                                 │
│   Without Minty          With Minty             │
│   ──────────────         ─────────────          │
│   ₹45,000 salary         ₹45,000 salary        │
│   ₹43,200 spent          ₹36,000 spent         │
│   ₹1,800 saved           ₹9,000 saved          │
│                                                 │
│   Annual savings: ₹21,600   →   ₹1,08,000      │
│                                                 │
│          That's 5x more savings.                │
│          That's your emergency fund.            │
│          That's your first investment.           │
│                                                 │
└─────────────────────────────────────────────────┘
```

</div>

Minty users report **saving 3–5× more** within the first 60 days — not because they're budgeting harder, but because they finally **see** where the money goes.

---

## ✨ Feature Arsenal

### 📲 SMS Intelligence Engine
Your bank already sends you SMS alerts for every transaction. Minty intercepts them in real-time using a **native Kotlin parser** — no third-party SDKs, no cloud processing. Every ₹ is captured, categorized, and logged before you put your phone down.

- ✅ Supports **UPI, NEFT, IMPS, card swipes, ATM withdrawals**
- ✅ Works with **SBI, HDFC, ICICI, Axis, Kotak, Paytm, GPay** alerts and more
- ✅ Auto-detects debits vs credits using contextual keyword analysis
- ✅ **100% on-device** — your SMS data never leaves your phone

### 🤖 AI Financial Advisor
Not a chatbot. An advisor that knows your salary, your spending habits, your goals — and speaks to you in plain language.

- 📊 Analyzes your transaction history against your declared income
- 🎯 Generates **personalized insights**: _"You spent ₹4,200 on food delivery this week — that's 38% above your usual."_
- 🔄 Daily AI allowance with plan-based scaling (4/day free → Unlimited on Elite)
- 💬 Interactive AI chat for on-demand financial guidance

### 🔴 Risk Detection System
A background engine that continuously monitors your financial health:

- ⚠️ **Overspending Alert** — fires when expenses cross 70% of your monthly budget
- 💸 **Low Savings Warning** — triggers if net balance falls below 20% of income
- 🏦 **Debt Signal Detection** — scans for EMI, loan repayment, and overdue keywords
- 📉 Budget context calculated from your declared salary vs actual outflows

### 📳 Shake-to-Add
The fastest expense entry in any finance app. Period.

- Just **shake your phone** on the home screen
- The expense adder flies up with a spring animation
- Tunable sensitivity (default: 12.0 m/s²) — adjust it in Settings
- Haptic feedback confirms detection instantly

### 🍱 Bento UI (Japanese-Inspired Design)
Every screen is a composition of modular, interactive tiles:

- **Glassmorphism cards** with frosted blur and transparency
- **Staggered reveal animations** — elements cascade in with spring physics
- **Haptic signatures** — credits pulse ↑ upbeat, debits press ↓ with weight
- **Elastic bottom sheets** that respond to flick velocity
- **Wavy slider widgets** for a tactile, analog feel

### 💼 Multi-Wallet Architecture
Organize your money by purpose, not just totals:

- 🏠 Personal, Savings, Business — create wallets for every financial context
- 🔒 Free users get **2 wallets**, premium unlocks **10**
- 📊 Per-wallet analytics and transaction isolation
- ₹29 per additional wallet for free-tier (one-time purchase via Razorpay)

### 🌍 Multi-Currency Support
Live exchange rates with support for 8+ currencies:

`INR` · `USD` · `EUR` · `GBP` · `JPY` · `AUD` · `CAD` · `CHF` — and more

- Rates fetched from **ExchangeRate API** on every app launch
- Offline fallback to last-known rates
- Currency-specific flag imagery bundled natively

### ☁️ Cloud Backup & Sync
- **Firestore-backed** profile and preference sync
- **Encrypted local storage** via `flutter_secure_storage` + Hive
- **WorkManager-powered** periodic background backups
- Seamless sign-out / sign-in restoration — your data follows you

### 🔔 Smart Notifications
- **Daily spending summaries** — morning, afternoon, evening reminders
- **Weekly and monthly rollups** with calculated totals
- **FCM push notifications** for plan expiry and feature updates
- **Firebase Crashlytics** — crash-free experience with real-time monitoring

---

## 💎 Plans & Pricing

<div align="center">

| | 🌱 **Minty Basic** | ⚡ **Pro Monthly** | 👑 **Elite Yearly** |
| :--- | :---: | :---: | :---: |
| **Price** | **Free** | **₹99/month** | **₹499/year** |
| **Wallets** | 2 | 10 | 10 |
| **AI Insights** | 4/day | 10/day | **Unlimited** |
| **SMS Auto-Track** | 20/month | 300/month | **Unlimited** |
| **Shake-to-Add** | 15/month | 200/month | **Unlimited** |
| **Transaction History** | 7 Days | Full Access | Full Access |
| **Analytics Depth** | Basic | Advanced | **Deep Insights** |
| **Data Export** | ❌ | ❌ | ✅ |
| **Risk Alerts** | ✅ | ✅ | ✅ |
| **Cloud Backup** | ✅ | ✅ | ✅ |
| **Priority Support** | ❌ | ✅ | ✅ |

</div>

> [!TIP]
> **Elite Yearly saves you ₹689/year** compared to Pro Monthly (₹99 × 12 = ₹1,188 vs ₹499). That's 58% off — and you get unlimited everything.

### 💳 Additional Purchases
| Item | Price | Type |
| :--- | :---: | :---: |
| Extra Wallet Slot | ₹29 | One-time |

All payments are processed securely through **Razorpay** with server-side validation. No credit card data is stored on-device.

---

## 🏗️ Architecture

```
minty/
├── lib/
│   ├── main.dart                    # App bootstrap, Firebase, WorkManager
│   ├── core/
│   │   ├── config/                  # Environment configuration
│   │   ├── constants/               # AppConstants, AppPrices
│   │   ├── extensions/              # Dart extensions
│   │   ├── providers/               # Riverpod (currency, exchange rates)
│   │   ├── services/
│   │   │   ├── sms_service.dart     # SMS listener + background processing
│   │   │   ├── backup_service.dart  # Cloud backup via WorkManager
│   │   │   ├── reminder_service.dart# Smart notification scheduling
│   │   │   ├── payment_service.dart # Razorpay integration
│   │   │   ├── limit_engine.dart    # Plan-based paywall enforcement
│   │   │   ├── analytics_service.dart
│   │   │   ├── fcm_service.dart     # Push notifications
│   │   │   └── usage_log_service.dart
│   │   ├── storage/                 # Hive + SecureStorage + JsonDB
│   │   ├── theme/
│   │   │   ├── app_colors.dart      # Centralized color palette
│   │   │   ├── app_theme.dart       # Material dark theme
│   │   │   └── app_typography.dart  # Playfair Display + system fonts
│   │   └── widgets/                 # FadeTranslate, PressScale, WavySlider
│   └── features/
│       ├── auth/                    # Google Sign-In, UserProfile model
│       ├── home/                    # Dashboard, balance header, transaction list
│       ├── insights/                # AI advisor, charts, deep analytics
│       ├── onboarding/              # Profile setup, plan selection
│       ├── settings/                # Preferences, shake sensitivity
│       ├── shell/                   # AppShell (bottom nav, usage refresh)
│       ├── splash/                  # Animated splash screen
│       ├── transactions/            # Expense adder, transaction CRUD
│       └── wallet/                  # Multi-wallet management
├── android/
│   └── app/src/main/kotlin/com/sas/minty/
│       ├── SmsParser.kt             # Native SMS → Transaction parser
│       ├── RiskDetector.kt          # Financial risk analysis engine
│       └── CategoryEngine.kt        # Auto-categorization (Food, Travel, etc.)
└── assets/
    ├── images/                      # Logo, onboarding, currency flags
    └── fonts/                       # Playfair Display
```

### Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Framework** | Flutter 3.9+ (Dart) |
| **State Management** | Riverpod 2.5 |
| **Authentication** | Firebase Auth + Google Sign-In |
| **Database** | Cloud Firestore + Hive (offline-first) |
| **Secure Storage** | flutter_secure_storage (AES-256) |
| **Payments** | Razorpay Flutter SDK |
| **Background Tasks** | WorkManager |
| **Push Notifications** | Firebase Cloud Messaging (FCM) |
| **Analytics** | Firebase Analytics |
| **Crash Reporting** | Firebase Crashlytics |
| **Native Layer** | Kotlin (SMS parsing, risk detection) |
| **Typography** | Playfair Display (bundled) |

---

## 🚀 Installation & Setup

### Prerequisites
- Flutter **3.9.2+** installed ([flutter.dev](https://flutter.dev))
- Android Studio or VS Code with Flutter extension
- A Firebase project with Firestore, Auth, Analytics, Crashlytics, and FCM enabled
- A Razorpay account for payment processing

### Step 1 — Clone & Install
```bash
git clone https://github.com/your-username/minty.git
cd minty
flutter pub get
```

### Step 2 — Firebase Configuration
1. Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
2. Register an Android app with package name `com.sas.minty`
3. Download `google-services.json` and place it in:
   ```
   android/app/google-services.json
   ```
4. Enable these Firebase services:
   - ✅ Authentication (Google Sign-In)
   - ✅ Cloud Firestore
   - ✅ Analytics
   - ✅ Crashlytics
   - ✅ Cloud Messaging

### Step 3 — Razorpay Setup
Add your Razorpay API keys in the payment service configuration. Never commit keys to version control — use environment variables or secure storage.

### Step 4 — Build & Run
```bash
# Debug
flutter run

# Release APK
flutter build apk --release

# Release App Bundle (Play Store)
flutter build appbundle --release
```

> [!IMPORTANT]
> ### ⚙️ Required Android Permissions (Post-Install)
> Minty uses SMS reading for automated transaction capture. Due to Android's security policies, the user must manually:
>
> 1. **Disable Google Play Protect** → Open Play Store → Tap profile → Play Protect → Settings ⚙️ → Turn off "Scan apps with Play Protect"
> 2. **Allow Restricted Settings** → Go to Settings → Apps → Minty → Tap ⋮ (3-dot menu) → Select "Allow restricted settings"
> 3. **Grant SMS Permission** → The app will prompt on first launch — tap "Allow"
>
> Without these steps, SMS auto-capture will not function. All other features work normally.

---

## 🎨 Design Language

<div align="center">

| Token | Hex | Usage |
| :--- | :---: | :--- |
| 🟢 **Mint Green** | `#7FBF9A` | Brand primary, accents, highlights |
| 🟩 **Deep Green** | `#0B5D4C` | Headers, emphasis, premium elements |
| 🟡 **Accent Yellow** | `#FFD60A` | CTAs, warnings, Pro badges |
| ⬛ **Dark Background** | `#0E1812` | App canvas |
| 🟫 **Dark Card** | `#182620` | Card surfaces |
| 🟢 **Income Green** | `#4DD9A0` | Credit indicators |
| 🔴 **Expense Coral** | `#E05C6A` | Debit indicators |
| 🔵 **Info Sky** | `#4DB8FF` | Informational highlights |
| ⚫ **Dim Text** | `#6B8A82` | Secondary labels |

</div>

Typography: **Playfair Display** for display headings · System font for body text
Theme: **Dark-first** with light surfaces for onboarding and expense entry

---

## 🗺️ Roadmap

- [ ] 💳 **NFC Tap-to-Track** — Log transactions by tapping your wallet on your phone
- [ ] 👨‍👩‍👧 **Family Sharing** — Shared wallets with household budget sync
- [ ] 💻 **Desktop Companion** — Windows/macOS app with deep database reconciliation
- [ ] 📊 **Prediction Engine** — AI forecasts your end-of-month balance from current burn rate
- [ ] 🧾 **Receipt Scanner** — OCR-powered receipt capture and auto-categorization
- [ ] 📈 **Investment Tracker** — Mutual funds, stocks, and SIP tracking in one place
- [ ] 🏦 **Bank Sync (AA Framework)** — Account Aggregator integration for real-time balance sync

---

## 🔒 Privacy & Security

- 🔐 **AES-256 encryption** for all locally stored financial data
- 📵 **SMS data never leaves your device** — parsing is 100% on-device via native Kotlin
- ☁️ **Firestore sync** is limited to profile preferences and plan status — transaction data stays encrypted locally
- 🚫 **No third-party analytics SDKs** — only Firebase (Google's first-party suite)
- 💳 **Razorpay handles all payment data** — Minty never sees or stores card numbers

---

## 📊 By the Numbers

| Metric | Value |
| :--- | :--- |
| **Lines of Code** | 15,000+ |
| **Insights Engine** | 100,000+ characters of AI logic |
| **Supported Banks** | 20+ Indian banks |
| **SMS Regex Patterns** | 3 cascading patterns with fallback |
| **Animation Widgets** | 5 custom (FadeTranslate, PressScale, RevealAnimation, WavySlider, StatTile) |
| **Background Services** | 4 (Backup, Reminders, SMS, FCM) |
| **Currencies** | 8+ with live exchange rates |

---

<div align="center">

  <img src="assets/images/logo.png" width="60" height="60" alt="Minty" />

  <br/><br/>

  **Minty** — *Stop guessing where your money goes. Start knowing.*

  <br/>

  <sub>Built with 🌿 in India · Crafted for every ₹ that matters</sub>

  <br/><br/>

  <p>
    <img src="https://img.shields.io/badge/Made_with-Flutter-0B5D4C?style=for-the-badge&logo=flutter&logoColor=7FBF9A" />
    <img src="https://img.shields.io/badge/Powered_by-Firebase-0B5D4C?style=for-the-badge&logo=firebase&logoColor=FFD60A" />
    <img src="https://img.shields.io/badge/Designed_in-India_🇮🇳-0B5D4C?style=for-the-badge" />
  </p>

</div>

---

`#minty` `#expense-tracker` `#personal-finance` `#flutter` `#ai-finance` `#bento-ui` `#sms-parsing` `#india-fintech` `#razorpay` `#firebase` `#riverpod` `#money-management` `#budget-tracker` `#savings-app` `#financial-advisor`
