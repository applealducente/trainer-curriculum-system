# Trainer Curriculum Management System

Progressive learning platform for 10+ day trainer onboarding.

## 🎯 Features

- 📚 **Progressive Activity Reveal** - One activity at a time, next unlocks when done
- 🔴 **Sync/Async Indicators** - Clear marking of synchronous (live) vs asynchronous (self-paced)
- 📊 **Admin Dashboard** - Real-time tracking of trainer progress
- 💾 **Data Persistence** - All progress saved in browser
- 📱 **Mobile Friendly** - Works perfectly on all devices

## 🚀 Quick Start

### For Trainers:
1. Visit: https://trainer-curriculum-system.vercel.app
2. Click **Trainer** role
3. Enter your name
4. Select your day (1-10)
5. Click **Start Learning**

### For Admins:
1. Click **Admin** role
2. Enter admin password (default: `admin123`)
3. View progress dashboard

## 📅 Days Included

- **Day 1** - Orientation, Setup & FC Foundation
- **Day 2** - Product Knowledge & Application  
- **Day 3** - Trial/OTC + Call Flow Foundation
- Days 4-10 - Ready to add

## 🛠️ Technologies

- Pure HTML, CSS, JavaScript
- localStorage for data persistence
- No external dependencies
- Fully responsive design

## 📝 How to Customize

### Change Admin Password
Edit `index.html`:
1. Find: `const correctPassword = 'admin123';`
2. Change to your password

### Add Days 4-10
Edit `index.html` and add to curriculum object:
```javascript
"4": {
    title: "Your Day Title",
    objective: "Your objective",
    activities: [
        { time: "8:00–9:00", duration: "1 hr", name: "Activity", type: "Synchronous", delivery: "Trainer-led", purpose: "Purpose" }
    ]
}
```

## 🚀 Deployment

Deployed on Vercel. Auto-deploys on GitHub push.

## 📜 License

MIT

---

**Last Updated:** August 2026  
**Status:** Production Ready ✅
