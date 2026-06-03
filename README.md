# 🚀 BlinkKey - Voice Reminders in Under 2 Seconds

The simplest possible MVP app to capture thoughts via voice and turn them into reminders.

## 🌐 Live Demo

**[👉 CLICK HERE TO TEST NOW](https://biemverwaalsolid.github.io/blinkkey/)**

No installation needed. Just open and start speaking! 🎙️

---

## ✨ Features

✅ **Voice Input** - Tap microphone → speak → done  
✅ **LocalStorage** - Reminders saved in your browser  
✅ **Browser Notifications** - Get reminded at the right time  
✅ **3 Preset Times** - +10 min, Tonight 18:00, Tomorrow 09:00  
✅ **Offline** - Works without internet  
✅ **Minimal UI** - Black & white design, 2 taps max  
✅ **No Setup** - Just open in browser!  

---

## 🎯 How It Works

1. **Tap the big black microphone** → Speech-to-text starts listening
2. **Say your reminder** → "Buy milk", "Call mom", etc.
3. **Tap again or wait** → Text appears on screen
4. **Choose time** → +10 min, Tonight 18:00, or Tomorrow 09:00
5. **Reminder saved** → You get a browser notification at the right time

---

## 📱 Tech Stack (Web Version)

- **HTML/CSS/JavaScript** (vanilla, no frameworks)
- **Web Speech API** (voice input)
- **LocalStorage** (data persistence)
- **Notifications API** (browser notifications)
- **Service Worker ready** (offline support)

---

## 🛠️ Setup (Optional - Local Testing)

### Option 1: Direct Open
Just download `index.html` and open it in your browser.

### Option 2: Local Server
```bash
# Navigate to the project folder
python -m http.server 8000

# Open in browser
http://localhost:8000
```

---

## 🔍 Database Schema (LocalStorage)

```json
{
  "reminders": [
    {
      "id": 1717338456123,
      "title": "Buy milk",
      "datetime": "2024-06-03T15:30:00.000Z",
      "status": "active"
    }
  ]
}
```

---

## 🧪 Testing

### Browser Support
- ✅ Chrome/Chromium
- ✅ Edge
- ✅ Safari (iOS 14.5+)
- ✅ Firefox

### Mobile
- ✅ Android (Chrome)
- ✅ iPhone (Safari)

### Test Features
1. **Tap microphone** → Say "Test reminder"
2. **Tap +10 min** → Should save and show "Reminder set!"
3. **Wait 10 minutes** → Browser notification appears
4. **Press 'd'** → Debug panel shows all reminders

---

## 🐛 Troubleshooting

### "Microphone not working"
- Check browser permissions (top left of address bar)
- Grant microphone access
- Refresh page

### "Notifications not showing"
- Grant notification permissions when prompted
- Keep browser tab open
- Check browser notification settings

### "Nothing saved"
- Check if LocalStorage is enabled
- Press 'd' to see debug panel
- Try in incognito/private mode

---

## 📋 Flutter Version

Want the native app for iOS/Android? Check out the Flutter version in this repo.

---

## 🚀 Next Steps

- Test voice recognition
- Set reminders and get notifications
- Share feedback!

**Ready?** → **[Open BlinkKey Now](https://biemverwaalsolid.github.io/blinkkey/)**
