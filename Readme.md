
# Hackathon Team Guidelines & Day-Wise Plan  

This repository contains the official plan, guidelines, and roadmap for our Hackathon project.  
Our goal is to build a **Safe & Smart Home Services App** where users can easily book verified electricians, plumbers, and other service providers.


##  Team Members  

### Frontend Developers  
- Hiba  
- Areeba  
- Mehak  

### Backend Developers  
- Hmaad  
- Qurrat  

### Leader  
- Syeda (Planning, Coordination & Pitch Deck)  

---

##  Setup Instructions  

1. Clone repository:  
   ```
   git clone https://github.com/SyedaQurrat/Madad-Gar.git
   ```

2. Create your branch:

  ```
   git checkout -b your-name-branch
  ```

3. Work on assigned files/folders, then push code:

```
git add .
git commit -m "your message"
git push origin your-name-branch
```

# Day-Wise Roadmap
## Day 1 – Research & Setup

### Frontend (Hiba, Areeba, Mehak):

- Setup Next.js + Tailwind project.

- Create folder structure (components, pages, styles).

- Prepare placeholder screens (Home, Login, Signup, Profile).

### Backend (Hmaad, Qurrat):

- Setup Firebase project (Firestore, Auth, Hosting).

- Create collections: users, providers, bookings.

- Setup roles (User, Provider).


## Day 2 – Authentication
### Frontend:

- Build Login & Signup UI pages.

- Add form validation + role selection (User / Provider).

### Backend:
- Implement Firebase Auth.

- Link roles in Firestore (on signup assign role field).

- Return token/session to frontend.

## Day 3 – Booking Flow Part 1
### Frontend:
- User side booking form (select service type, date, time).

- Provider profile display page (basic info + skills).

### Backend:
- Create booking API (store in Firestore).

- Link booking to both user_id and provider_id.

## Day 4 – Booking Flow Part 2 & Emergency

### Frontend:
- Emergency button UI (highlighted).

- Booking status page (Pending/Accepted/Completed).

### Backend:
- Emergency service logic (nearest available provider).

- Firestore triggers for status updates.

## Day 5 – Tracking & Payment

### Frontend:
- Live tracking page (location updates).

- Payment screen design.

### Backend:
-Real-time tracking via Firestore updates.

- Integrate payment gateway (Stripe/Razorpay).

## Day 6 – Reviews & Notifications

### Frontend:
- Review & Rating UI.

- Notifications popup in app.

### Backend:
- Store ratings in Firestore.

- Setup Firebase Cloud Messaging for push notifications.

## Day 7 – Testing & Final Touches

### Frontend:
- Test booking → payment → review flow.

- Polish UI (responsiveness, animations).

### Backend:
- Test DB queries + API errors.

- Secure role-based access (only verified providers can accept jobs).

## Day 8 – Presentation Day
### Leader (Syeda):
- Pitch problem → solution → uniqueness.
### Frontend Team:
- Showcase user journey (Signup → Book → Track → Pay → Review).

### Backend Team:

- Explain Firebase integration (Auth, Firestore, Messaging, Payments).
