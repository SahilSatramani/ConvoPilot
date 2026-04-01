# 📱 ConvoPilot

ConvoPilot is a mobile application built with React Native that helps users capture, transcribe, and interact with their meeting conversations in real-time. It features calendar integration, real-time audio transcription, offline-first capabilities, and a chat interface powered by AI.

---

## 📱 Features

- **Google Sign-In** (via Firebase Authentication)
- **Google Calendar Integration** to fetch upcoming events
- **Real-Time Transcription** with 30-second segmented updates
- **Offline-First Transcription Syncing** (using SQLite)
- **Chat with Transcript** using OpenAI / Gemini API
- **Tabbed Navigation** (Memories, Calendar, Transcript)
- **Location tagging** using Reverse Geocoding

---

## 🛠️ Tech Stack

- **React Native** with TypeScript
- **Firebase Auth**
- **Google Calendar API**
- **OpenAI / Gemini API** for transcription & chat
- **SQLite** for offline data storage
- **React Navigation**
- **@react-native-google-signin/google-signin**
- **react-native-audio-recorder-player**

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/convopilot.git
cd convopilot
```

### 2. Install Dependencies

```bash
yarn install
# or
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file and add:

```env
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
OPENAI_API_KEY=your_openai_or_gemini_api_key
```

### 4. Run the App

```bash
npx react-native run-android
# or for iOS
npx react-native run-ios
```

---

## 🧪 Testing

- Transcript recording  
- Location tagging  
- Summarization  
- Chat interface  

---

## 📌 Notes

- Ensure the following APIs are enabled in Google Cloud:
  - Google Calendar API  
  - Geocoding API  

- Add correct SHA-1 fingerprint and package name in:
  - Firebase Console  
  - Google Cloud Console  

- If the transcript is less than 30 seconds long, auto-summarization and chat features will not be triggered.
