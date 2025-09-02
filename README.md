# 🛡 SafeRoute AI – City-Sakhi  

An *AI-powered Safety Heatmap and Route Planner* that helps users find the *safest routes* in urban areas by crowdsourcing real-time safety reports (harassment, poorly lit areas, crowded zones, etc.) and integrating with *Google Maps + Firebase*.  

The application calculates a *Safety Score (0–100)* for routes, highlights risky areas with colored markers, and allows users to report incidents for community safety.  

---

## 🌟 Features  

✅ *Safety Heatmap* – Visualizes incident reports (harassment, unlit areas, crowded spots, safe zones).  
✅ *Safest Route Finder* – Calculates alternative walking routes and highlights the safest one in *green*.  
✅ *Dynamic Risk Indicators* – Color-coded:  
   - 🔴 Harassment/Incident  
   - 🟡 Poorly Lit  
   - 🔵 Too Crowded  
   - 🟢 Safe Zone  
✅ *Community Check-ins* – Users can report their surroundings in real-time (saved to Firebase).  
✅ *Multi-Mode Travel Info* – Distance & duration estimates for car 🚗, bike 🚴, transit 🚆, and walking 🚶.  
✅ *Smart Scoring System* – Uses density of risk points per kilometer to generate a *Safety Score*.  

---

## 🛠 Tech Stack  

- *Frontend*: HTML5, TailwindCSS, JavaScript  
- *Maps API*: Google Maps JavaScript API (maps, places, geometry, marker libraries)  
- *Database*: Firebase Firestore (real-time safety check-ins)  
- *Hosting*: Any static hosting (Firebase Hosting, Netlify, Vercel, etc.)  

---
