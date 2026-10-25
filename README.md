# Elite Central Portal + EVIDERA

A premium, modern, fully responsive central student portal designed for the **Elite Batch 2025–2029** at **Francis Xavier Engineering College (FXEC)**.

This portal acts as the centralized gateway for academic tracking, attendance records, milestone task planning, assignment submissions, problem-solving progress, and hackathon competition evidence verification via **EVIDERA**.

---

## 🚀 Key Features

- **Light-First Modern SaaS Aesthetic**: Inspired by modern dashboards (Linear, Notion, Vercel), featuring crisp typography (Plus Jakarta Sans & Inter), soft neutral surfaces, restrained elevation, and subtle brand accents.
- **EVIDERA Integration**: Dedicated first-class portal card with custom screenshot/evidence verification identity, connecting students directly to the hackathon and competition proof submission system.
- **Client-Side Real-Time Search**: Instant fuzzy filtering across portal titles, subtitles, descriptions, categories, and keywords with `/` or `Ctrl+K` keyboard shortcuts.
- **Category Filter Tabs**: Switch between **All Portals**, **Student Platforms**, **Academic Activities**, and **Hackathons & Proofs**.
- **Responsive Navigation**: Full desktop sidebar with collapse and mobile drawer navigation with accessible backdrop overlay.
- **High Accessibility (a11y)**: Semantic HTML5 landmarks, visible focus-visible indicators, full keyboard navigation, screen-reader accessible links, and reduced-motion support.
- **Zero Backend Dependency**: 100% static frontend deployable directly to **Vercel** with no server-side build steps or runtime overhead.

---

## 🌐 Connected Portals Directory

| Portal Name | Category | Destination URL | Purpose / Description |
|---|---|---|---|
| **EVIDERA** | Student Platforms / Hackathons | `https://student-screenshot-portal.onrender.com/hackathons` | Student Screenshot Portal for Hackathons & Competitions proof submissions. |
| **Elite Attendance Portal** | Academic Activities / Platforms | `https://lodportal.netlify.app/` | View attendance records, leave records, and status information. |
| **Task Planning Portal** | Academic Activities | `https://script.google.com/a/macros/francisxavier.ac.in/s/AKfycbynjp3vACDQaOiVPJGx6yfO7-MW1BBsSDO0bX4dYwKgeK4qVGXWuY3Louw43JLwnRS1/exec` | Sprint roadmaps, task schedules, and milestone planning. |
| **Elite Task Portal** | Student Platforms | `https://elite-dashboard-as.onrender.com/` | Assignment submission, deliverable verification, and activity tracking. |
| **PS Daily Updation Portal** | Academic Activities | `https://docs.google.com/spreadsheets/d/1FuXF9q0X1pS8Bw-D8gyZ0IyEaUwrQ4yD4iBPWIWlP1c/edit?usp=sharing` | Daily problem-solving progress tracking sheet. |
| **FXEC Campus Portal** | Institutional Resource | `https://francisxavier.ac.in/` | Official Francis Xavier Engineering College autonomous portal. |

---

## 💻 Local Testing & Preview

To preview the portal locally, you can use any static HTTP server.

### Option A: Using Python
```bash
# Run inside the project directory
python -m http.server 3000
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option B: Using Node.js (npx)
```bash
npx serve .
```

### Option C: Direct File Opening
You can also open `index.html` directly in any modern web browser (Chrome, Edge, Firefox, Safari).

---

## 🚢 Vercel Deployment Instructions

The portal is optimized to deploy directly on **Vercel** as a pure static frontend.

### Step 1: Initialize Git and Commit Changes
```bash
git init
git add .
git commit -m "feat: redesign Elite Central Portal with premium UI and EVIDERA integration"
```

### Step 2: Push to GitHub
1. Create a new repository on your GitHub account (e.g., `elite-central-portal`).
2. Link your local repository and push:
```bash
git remote add origin https://github.com/<your-username>/elite-central-portal.git
git branch -M main
git push -u origin main
```

### Step 3: Deploy to Vercel
1. Log in to [Vercel](https://vercel.com).
2. Click **Add New...** > **Project**.
3. Import your `elite-central-portal` GitHub repository.
4. Framework Preset: **Other** (Static HTML).
5. Root Directory: `./` (default).
6. Build and Output Settings: Leave default (No build command needed).
7. Click **Deploy**.

Your Elite Central Portal will be live with an SSL certificate and global CDN edge caching.

---

## 🔒 Security & Privacy Notice

- **No Credentials Stored**: The central portal does not handle, intercept, or store student passwords or credentials.
- **Secure External Links**: All external portal links are configured with `target="_blank" rel="noopener noreferrer"` to protect against tab-nabbing vulnerabilities.
- **Strict Headers**: `vercel.json` provides strict security headers (`X-Frame-Options`, `X-Content-Type-Options`, `Referrer-Policy`).

---

## 🏛 Institution & Batch Details

- **Batch**: Elite Batch 2025–2029
- **Institution**: Francis Xavier Engineering College (Autonomous), Tirunelveli, Tamil Nadu, India
