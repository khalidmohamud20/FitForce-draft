# FitForce

**Track. Train. Transform.**  
FitForce is a modern fitness web application built with Django. It empowers users to create custom workout plans, log their exercises, and track their fitness progress over time in an intuitive and responsive interface.

---

## 📑 Table of Contents

- Project Overview  
- Project Planning  
- Features  
  - General Features  
  - Navigation & Hero  
  - Featured Posts  
  - Article Feed  
  - Post Details  
  - User Profiles  
  - Responsive Design  
- Technical Stack  
- AI Usage  
- Deployment  
- Testing  

---

## 📖 Project Overview  

FitForce is a fitness tracking platform that helps users stay committed to their health goals. Users can:  

- Create personalized workout plans  
- Log workouts with sets, reps, and exercise details  
- Monitor workout history and view progress visually  
- Manage their fitness routine through a clean and user-friendly dashboard  

The platform is built using Django with a dark-themed frontend enhanced by energetic, engaging accent colors.

---

## 🧠 Project Planning  

**Goals:**  

- Design a user-centric fitness tracker that is simple, useful, and responsive  
- Practice full-stack development with Django, templating, models, and views  
- Maintain clean separation of concerns: authentication, workout logic, UI  

**Development Phases:**  

- Planning & Setup – Project structure, GitHub repo, core models  
- Feature Implementation – Auth, plans, logs, dashboard  
- UI/UX Design – Templates, responsiveness, theming  
- Testing & Debugging – Forms, views, responsiveness  
- Deployment & Polish – Hosting, documentation, screenshots  

---

## 🚀 Features  

- User registration and login system  
- Workout plan creation  
- Exercise management (name, type, description)  
- Workout logging with date, sets, and reps  
- Dashboard with recent logs and quick links  
- Progress tracking via visual charts  
- Admin panel for database management  

---

## ⚙️ General Features  

- Clean, dark UI with accent colors that are energetic but not overwhelming  
- Smooth navigation between features with clear CTAs  
- Minimalist layout for focus and ease-of-use  
- Fonts and layout optimized for readability  

---

## 🧭 Navigation & Hero  

- **Navigation Bar:**  
  - Logo (FitForce) on the left using Fredoka One font  
  - Links on the right: Dashboard | Workout Plans | Log Workout | Profile | Logout  

- **Hero Section:**  
  - Large motivational message: "Take control of your fitness journey."  
  - Subtext: "Create plans, log your sessions, and see your progress come to life."  
  - Call-to-action: [Get Started] button  

---

## 🌟 Featured Posts  

- Recently logged workouts  
- New user-created plans  
- Fitness milestones (e.g., 30-day streaks)  

---

## 📰 Article Feed  

- Workout tips and guides  
- Recommended routines  
- Health articles curated by the admin team  

---

## 📄 Post Details  

- Title, date, and category  
- Author and profile link  
- Full post content  
- Related tags  

---

## 👤 User Profiles  

- Personal information (username, join date)  
- Number of plans created  
- Recent workout logs  
- Profile photo (optional)  
- Progress chart (exercise-wise)  

---

## 📱 Responsive Design  

FitForce is fully responsive across:  

- Smartphones  
- Tablets  
- Desktop screens  

**Frameworks/Approach:**  

- Bootstrap 5 for grid & responsiveness  
- Media queries for fine control  
- Mobile-first design philosophy  

---

## 🛠 Technical Stack  

| Layer          | Tool/Tech                         |  
| -------------- | -------------------------------- |  
| Backend        | Django (Python)                   |  
| Frontend       | Django Templates, Bootstrap      |  
| Database       | SQLite (dev), PostgreSQL (prod)  |  
| Authentication | Django built-in auth              |  
| Charting       | Chart.js                         |  
| Styling        | Custom CSS, Bootstrap            |  
| Fonts          | Fredoka One (logo), Inter (body) |  
| Version Control| Git & GitHub                     |  

---

## ⚙️ AI Usage  

- No AI-generated content in the app’s logic, views, forms, or templates  
- All code is hand-written for educational value  

---

## 🚀 Deployment  

**Hosting Targets:**  

- Backend: Render or Railway (PostgreSQL-compatible)  
- Static Files: Whitenoise + Django’s collectstatic  
- Environment: Python 3.11+, Django 4.x, Gunicorn (prod server)  

**Deployment Steps:**  

- Set up production database  
- Configure ALLOWED_HOSTS and environment variables  
- Apply migrations and collect static files  
- Deploy via Git or CI/CD pipeline  

---

## 🧪 Testing  

**Manual Testing:**  

- Auth flows: register, login, logout  
- CRUD: workout plans, logs, profile updates  
- Navigation & mobile responsiveness  
- Error handling (e.g., invalid forms)  

**Automated Testing:**  

- Django’s TestCase for:  
  - Model validation  
  - View permissions  
  - Form input checks  
  - Dashboard data display  

---
