# 💪 AI Fitness Trainer 🤖

An AI-powered personal fitness trainer that creates **custom workout** and **diet programs** tailored to your goals — all with a smart voice-enabled assistant.

---

## 🚀 Highlights

- **Tech Stack:** Next.js, React, Tailwind CSS, Shadcn UI  
- **🎙️ Voice AI Assistant** powered by Vapi  
- **🧠 LLM Integration** with Gemini AI  
- **🏋️ Personalized Workout Plans** based on goals, injuries, and fitness level  
- **🥗 Custom Diet Programs** matching your dietary preferences and allergies  
- **🔒 Secure Authentication** via Clerk  
- **💾 Real-time Database** with Convex  
- **🎬 On-demand Program Generation**  
- **💻 Modern UI Layouts** optimized for all devices  
- **🎭 Client & Server Components** for performance and flexibility  

---

## ✨ Features

- **Smart AI Trainer** – Conversational interface that learns about your fitness needs  
- **Custom Workouts** – Exercise routines tailored to you  
- **Personalized Diet Plans** – Meal suggestions considering allergies & preferences  
- **Multi-Program Management** – Store multiple programs but keep only the latest active  
- **Responsive UI** – Works on desktop, tablet, and mobile  

---

## 🛠️ Setup

### 1. Clone the repository
```bash
git clone https://github.com/Laxman-Katneni/AI-Fitness-Trainer.git
cd AI-Fitness-Trainer
```

### 2. Install dependencies
```bash
npm install
```
4. Configure Environment Variables

Create a .env file in the root directory:
```bash
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```
4. Run the development server
npm run dev
Visit http://localhost:3000 in your browser.
🧩 Technologies Used
Next.js – React framework for frontend & API routes
Tailwind CSS & Shadcn UI – Styling & components
Clerk – Authentication & user management
Vapi – Voice AI platform for conversational interfaces
Convex – Real-time database
Gemini AI – Large Language Model for personalized plans

## ⚠️ Limitations (Free Tier Usage Only)
Since this project uses **only free tiers** for all services, there are some constraints:

- **Clerk Free Tier**  
  - Limited monthly active users (typically 5,000 on free plan, but may vary)  
  - Certain advanced authentication features (like SMS) may be restricted  

- **Vapi Free Tier**  
  - Limited voice minutes per month  
  - Possible latency in real-time interactions if usage exceeds free quota  

- **Gemini AI Free Tier**  
  - Limited number of requests per day  
  - Potential rate limiting during peak hours  

- **Convex Free Tier**  
  - Limited database storage and query count  
  - Restricted concurrent connections  

- **Vercel Free Tier**  
  - Bandwidth and execution time limits  
  - Build execution minutes are capped monthly  

- **General Impact**  
  - Heavy use could trigger service throttling  
  - Not ideal for high-traffic production deployment without upgrading plans  

## 🔗 Links
- **GitHub Repository:** [AI Fitness Trainer](https://github.com/Laxman-Katneni/AI-Fitness-Trainer)  
- **LinkedIn:** [Laxman Katneni](https://www.linkedin.com/in/laxman-katneni)  


