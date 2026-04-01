<p align="center">
  <img src="https://raw.githubusercontent.com/Uncover-Fitness/.github/main/assets/logo-3d.png" alt="Uncover Fitness" width="120" />
</p>

<h1 align="center">Product Overview</h1>

<p align="center"><em>Unified Training & Client Management Platform</em></p>

---

## At a Glance

Uncover is a full-stack fitness platform that connects trainers, nutritionists, and clients in one ecosystem — web dashboard, iOS app, and Android app.

| | |
|---|---|
| **Platforms** | Web · iOS · Android |
| **Users** | Admins · Trainers · Nutritionists · Clients |
| **AI** | Gemini-powered coaching, voice mode, body scan analysis, food recognition |
| **Wearables** | Apple Watch · Garmin · WHOOP · Oura · Polar · Fitbit · Withings |
| **Payments** | Stripe (subscriptions, packages, invoicing) |
| **Languages** | English · Spanish |

---

## For Clients

### Book & Manage Classes
Browse the weekly class timetable, book sessions instantly, join waitlists, and get reminders before class.

### Real-Time Heart Rate Monitoring
Connect a Polar H10 via Bluetooth for live BPM and heart rate zone tracking during class. See your position on the studio leaderboard in real time.

### 3D Body Composition Scanning
Capture front, side, and back photos for AI-powered body composition analysis. Track body fat, lean mass, BMI, BMR, and detailed measurements over time.

### Workout Programs
Access trainer-designed programs with video demonstrations. Log sets, reps, weight, and rest periods. Track personal records.

### Nutrition Tracking
Log meals, calories, and macros. Snap a photo of your food for instant AI-powered nutritional analysis. Set goals with your trainer and track hydration.

### AI Coach
Chat or use voice mode with an AI coach that knows your training history, body composition, and biometric data. Get personalized daily plans, recovery recommendations, and health summaries.

### Recovery Sessions
Book cryotherapy, infrared sauna, and compression therapy sessions directly in the app. Recovery data is tracked alongside your training metrics.

### Progress & Analytics
See your fitness journey on a comprehensive dashboard — weight trends, body composition changes, workout frequency, achievements, and leaderboards.

---

## For Trainers

### Client Management
View the full picture of every client — training history, nutrition logs, body composition scans, biometric trends, recovery sessions, and health documents in one place.

### Program Design
Create custom workout programs with exercises, sets, reps, tempo, and rest periods. Assign programs to individual clients or groups.

### Class Management
Set up class schedules, manage capacity, check in attendees, and view post-class heart rate analytics.

### AI-Assisted Reporting
Generate 7-page clinical reports that combine biometrics, AI-written narratives, and movement analysis. Review AI-generated health summaries before they reach clients.

### Messaging
Communicate directly with clients through in-app messaging. Send push notifications, reminders, and email updates.

---

## For Studios & Organizations

### Multi-Portal Admin
Dedicated admin dashboard with analytics, user management, studio configuration, and operational oversight.

### Staff Operations
Employee management, time and attendance, shift scheduling, payroll period exports (CSV/QuickBooks), and commission tracking.

### Membership & Payments
Stripe-integrated membership plans, credit packages, add-on subscriptions, invoicing, and usage tracking.

### Role-Based Access
Granular permission sets for admins, trainers, nutritionists, and clients. Custom roles and audit trail.

### Multi-Studio Support
Studio boundary middleware for organizations with multiple locations. Designed to scale.

### Compliance
HIPAA-aligned data handling, consent management, privacy controls, and data export/deletion capabilities.

---

## Technology

| Layer | Stack |
|-------|-------|
| **Backend** | Node.js · Express · TypeScript · Prisma · MongoDB Atlas |
| **Frontend** | React · TypeScript · Fluent UI · Vite |
| **Mobile** | React Native · Expo SDK 55 · TypeScript |
| **AI** | Google Gemini (chat, voice, vision, TTS) |
| **Payments** | Stripe |
| **Email** | Resend |
| **Real-time** | Socket.io |
| **Infrastructure** | Railway (API) · Vercel (Web) · EAS (Mobile builds) |

---

## Security & Privacy

- JWT authentication with refresh token rotation and MFA (TOTP)
- Role-based access control on every endpoint
- Health data consent is explicit and withdrawable
- Data export and deletion on request
- HIPAA-aligned infrastructure and data handling
- Production readiness score: **95/100** (independent audit)

---

<p align="center">
  <strong><a href="https://uncover.fit">uncover.fit</a></strong><br/>
  <sub>&copy; 2026 Uncover Fitness. All rights reserved.</sub>
</p>
