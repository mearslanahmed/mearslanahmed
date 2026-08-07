<div align="center">

## Arslan Ahmed

[arslanahmed.me](https://arslanahmed.me) · [LinkedIn](https://linkedin.com/in/mearslanahmed) · [Fiverr](https://fiverr.com/mearslanahmed) · [Email](mailto:arslanahmednaseem@gmail.com)

</div>

---

I build production software across mobile, backend, and applied AI, and I care more about shipping AI into real products than running experiments in notebooks. AgriGuard started with a client requirement, ran through six months of EfficientNetB3 training on crop disease data, and ended with an ESP32 controlling an irrigation pump from a React Native app. That's the kind of problem I find interesting.

Freelancing internationally since my second year of university. 5.0 on Fiverr. Currently shipping SpendWise.

---

## Projects

**[AgriGuard](https://github.com/mearslanahmed/AgriGuard)** · [Live](https://mearslanahmed.github.io/AgriGuard/) · [APK](https://github.com/mearslanahmed/AgriGuard/releases)

Built for AG Leaders. A single disease classifier fails because it conflates diseases across crops: a tomato lesion and a mango lesion look similar enough to confuse the model. The fix: a crop gate first. EfficientNetB3 identifies the crop (11 classes, 99.15% accuracy), rejects unknown inputs, then a second EfficientNetB3 classifies disease within that confirmed crop (76 classes, 94.86% accuracy, 0.94 macro F1). Dual ESP32 architecture: CAM module handles image capture, WROOM handles pump relay and soil moisture, separated because running GPIO alongside camera and WiFi on a single ESP32-CAM causes ADC failure.

`React Native` `Node.js` `TensorFlow` `Flask` `EfficientNetB3` `ESP32` `HuggingFace`

---
**[SpendWise](https://github.com/mearslanahmed/spendwise-react-native)** · [Live](https://spendwiseapp.tech) · [Google Play](https://play.google.com/store/apps/details?id=com.mearslanahmed.SpendWise)

AI finance tracker built solo, live on Android. The financial advisor is RAG-grounded against each user's transaction history, budgets, and wallets before generating responses, preventing generic or fabricated advice. Gemini Vision extracts structured transaction data from receipts, reducing manual entry to a single image. Native Android home screen widget built in Kotlin with Jetpack Glance so users can log transactions without opening the app. AI features routed through a Next.js backend API to keep keys off the client. Jest test coverage before release.

`React Native` `Kotlin` `TypeScript` `Expo` `Firebase` `Gemini` `Groq` `Next.js` `RAG` `Jest`

---

**[TalentSift](https://github.com/mearslanahmed/TalentSift)** · [Live](https://talentsift.live)

AI recruitment platform. Backed by PostgreSQL on Supabase to handle the concurrent read/write patterns an applicant tracking system generates: multiple recruiters reviewing, scoring, and updating candidates simultaneously. LangChain + Groq handle automated screening interviews with instant scoring. Stripe subscription tiers for premium features.

`Next.js` `Django REST` `PostgreSQL` `LangChain` `Groq` `Stripe` `Supabase`

---

**[ReelTime](https://github.com/mearslanahmed/reeltime-android)** · [Kaffeine](https://github.com/mearslanahmed/kaffeine-android) · [Movies Recommending System](https://github.com/mearslanahmed/movies-recommending-system) · [Employee Management System](https://github.com/mearslanahmed/employee-management-system)

---

## Stack

```
Languages   JavaScript · TypeScript · Python · Kotlin · C# · C++
Mobile      React Native · Expo · Android SDK
Frontend    React · Next.js · Tailwind CSS
Backend     Node.js · Express · Django REST · Flask
Databases   MongoDB · PostgreSQL · Firebase · MySQL
AI/ML       TensorFlow · PyTorch · Keras · LangChain · Scikit-learn · Pandas · NumPy
Tools       Git · Linux · Postman · Android Studio
```

---

## Experience

**Python Developer — AI/ML** · Smart Algorithm (AI Soft) · Dec 2024 – Mar 2025  
Designed, trained, and deployed seven ML models across classification, regression, and clustering. Integrated trained models into production Django applications end-to-end.

**Freelance Developer** · Fiverr · Jan 2024 – Present  
5.0/5.0. Mobile apps, REST APIs, and full-stack systems for international clients.
