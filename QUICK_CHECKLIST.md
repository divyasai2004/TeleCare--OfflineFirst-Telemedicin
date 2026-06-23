# 🎯 Quick Checklist: Path to 100%

## ⚠️ CRITICAL (Must Do - 13-18 hours)

### 1. Video/Audio Calls (6-8 hours)
```
□ Install: npm install simple-peer
□ Create: app/api/webrtc/route.ts (signaling server)
□ Create: app/components/AudioCall.tsx (start with audio, simpler)
□ Create: app/components/VideoCall.tsx (optional, if time)
□ Modify: app/components/ChatInbox.tsx (add "Call" button)
□ Test: Call works between patient and doctor
```

### 2. Offline Support - PWA (4-6 hours)
```
□ Create: public/sw.js (service worker)
□ Create: public/manifest.json (PWA manifest)
□ Create: app/lib/offline-storage.ts (IndexedDB wrapper)
□ Modify: app/layout.tsx (register service worker)
□ Modify: next.config.ts (add PWA config)
□ Test: Works offline (airplane mode)
```

### 3. Medicine Stock API (3-4 hours)
```
□ Create: app/api/pharmacy-stock/route.ts
□ Add: Mock stock data (In Stock/Out of Stock)
□ Modify: app/find-medicine/page.tsx (show stock status)
□ Add: "Last updated" timestamp
□ Add: "Check Nearby Pharmacies" button
```

---

## 🔧 IMPORTANT (Should Do - 7-10 hours)

### 4. Enhanced Offline Rules (2-3 hours)
```
□ Expand: SYMPTOM_RULES in symptom-checker/page.tsx
□ Add: 20+ more symptom combinations
□ Add: Age-specific advice
□ Improve: Hindi translations
```

### 5. Consultation Features (3-4 hours)
```
□ Add: Consultation scheduling (calendar)
□ Add: Prescription PDF download
□ Add: Appointment reminders
□ Add: Follow-up booking
```

### 6. Medicine Features (2-3 hours)
```
□ Add: Generic alternatives
□ Add: Price comparison
□ Add: Drug interaction checker
□ Add: Dosage calculator
```

---

## ✨ POLISH (Nice to Have - 6-9 hours)

### 7. Performance (2-3 hours)
```
□ Optimize images (next/image)
□ Add loading skeletons
□ Add error boundaries
```

### 8. Accessibility (2-3 hours)
```
□ Add ARIA labels
□ Test keyboard navigation
□ Test screen reader
```

### 9. Documentation (2-3 hours)
```
□ Write README.md
□ Create demo video
□ Document API endpoints
```

---

## 🚀 MINIMUM VIABLE (10 hours for 90%+)

**Priority Order:**
1. Audio calls (4h) ⚠️ CRITICAL
2. Service worker (2h) ⚠️ CRITICAL  
3. Mock pharmacy API (1h) ⚠️ CRITICAL
4. Offline queue (2h) ⚠️ CRITICAL
5. Enhanced rules (1h) ✅ IMPORTANT

---

## 📊 Current vs Target Score

| Feature | Current | Target | Gap |
|---------|---------|--------|-----|
| Remote Consultation | 15/20 | 20/20 | Video/Audio calls |
| Health Records | 19/20 | 20/20 | ✅ Already good |
| Medicine Availability | 12/20 | 18/20 | Real-time stock |
| AI Symptom Checker | 18/20 | 20/20 | ✅ Already good |
| Offline Support | 13/20 | 18/20 | PWA + offline queue |

**Current: 72/100 → Target: 96-100/100**

---

## ⏰ Time Breakdown

**If you have 10 hours:**
- Audio calls: 4h
- Service worker: 2h  
- Mock pharmacy: 1h
- Offline queue: 2h
- Enhanced rules: 1h
**Result: 90%+ score**

**If you have 20 hours:**
- All above (10h)
- Video calls: +4h
- Enhanced features: +6h
**Result: 95%+ score**

**If you have 30+ hours:**
- All above (20h)
- Polish & optimization: +10h
**Result: 98-100% score**

---

## ✅ Final Submission Checklist

**Core Features:**
- [ ] Video OR Audio calls work
- [ ] Service worker installed (PWA)
- [ ] Offline symptom checker works
- [ ] Medicine stock API (mock is fine)
- [ ] Health records accessible

**Testing:**
- [ ] Test offline mode (airplane mode)
- [ ] Test on mobile device
- [ ] Test video/audio call
- [ ] Test Hindi language

**Documentation:**
- [ ] README.md with setup
- [ ] Demo video/GIF
- [ ] Presentation slides

---

**Start with Audio Calls + Service Worker = 6 hours = 85%+ score!**
