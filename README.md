# EXPOXUR – The Digital Booth Experience  
**Tagline**: *Expose Greatness.*

Expoxur is a gamified, all-in-one platform that transforms traditional expo events into sustainable, engaging, and digital-first experiences. Attendees, Exhibitors, and Organizers each get their own dashboards with tools to interact, connect, and elevate event presence — all from a single scan.

---

## 🧠 Core MVP Vision

Build a full-stack MVP using Supabase + modern frontend tools. The app must support 3 user roles:

- **Event Attendees**
- **Booth Exhibitors**
- **Event Organizers**

Each role has:
- Their own dashboard
- Log-out capability
- Custom views and functionality

### 🔐 Unified Auth Page:
A single log-in/sign-up interface with tabbed sections for each user role. Each tab contains role-specific fields:
- **Attendees**: name, email, phone
- **Exhibitors**: company name, email, role, industry
- **Organizers**: org name, contact info, event intent

---

## 🏠 Public Site Pages

### 🔹 Landing Page (`/`)
Includes scrollable sections:
- About
- Event Attendees: What’s in it for them
- Booth Exhibitors: What’s in it for them
- Event Organizers: What’s in it for them  
Each section includes **trust-building content** and a clear **CTA (Call to Action)** to sign up or log in.

### 🔹 Events Page (`/events`)
Public directory of upcoming events (created by Organizers via their dashboards). Visitors can browse events, view booths, and see tagged sponsors.

---

## 📦 Supabase Tables (Pre-Created)

These tables exist in the Supabase backend. Let the app build out their logic and relations dynamically:

- `users`  
- `events`  
- `booths`  
- `interactions`  
- `notifications`  
- `event_tags`  

Foreign key relationships, RLS, and column logic (timestamps, triggers, etc.) to be handled based on app behavior and role-based rules.

---

## 📲 Dashboard Features (Per Role)

### 🧑 Attendees
- View booths per event
- Scan to interact
- Join games/promos
- Earn badges
- Track history

### 🏢 Exhibitors
- Create/edit booth profiles
- Upload logo, CTA links, offers
- View engagement
- Receive sponsor tag notifications

### 🎤 Organizers
- Create/manage events
- Tag registered exhibitors as:
  - Co-Presenter
  - Major/Minor Sponsor
  - Custom Labels
- Manage event status:
  - Event Requests
  - Ongoing Events
  - Upcoming Events

---

## 🎨 UI / Design System

- Background: #111111 (charcoal)
- Accent: #E53935 (Expoxur Red)
- Text: White
- Font: `Poppins`, `Inter`, `Montserrat`
- Logo: Red ascending "E" with **"Expose Greatness"** tagline

---

## 🚀 Future Add-Ons

- White-labeled versions per organizer
- Leaderboards for gamified booths
- Real-time chat between users
- Analytics dashboard for sponsors

---

## 🙌 Built With Love By:
Lovely Candy Sagun & Elijah Charlie —  
For a generation that’s done with boring booths and hungry for digital greatness.

