# 🧠 Histochat – Create & Learn from AI Personalities

**Histochat** is an interactive educational SaaS platform that empowers learners to create their own custom **AI personalities** powered by GPT models. Users can simulate conversations with historical figures, scientists, fictional characters, or any custom mentor—making education immersive, personalized, and fun.
 
---

## 🚀 Features

- 🎭 **AI Persona Creation**  
  Design your own learning companions – give them a name, background, tone, and knowledge scope.

- 💬 **Conversational Learning**  
  Chat with AI personas to learn topics interactively — history, science, math, literature, and more.

- 🧠 **Powered by GPT**  
  Uses OpenAI’s GPT models to generate intelligent, context-aware responses.

- 🎓 **Education-Focused UX**  
  Tailored for learning retention with persona memory, chat history, and knowledge scaffolding.

- 🏷️ **Topic Tagging**  
  Organize your learning journeys by subject, persona, or goal.

- 📱 **Responsive Design**  
  Usable on all devices with an intuitive, clean UI.

---

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express (or your backend setup)
- **AI Engine:** OpenAI GPT (via API)
- **Database:** MongoDB / PostgreSQL (depending on your implementation)
- **Auth:** JWT / Firebase / Auth0
- **Hosting:** Vercel / Netlify / Render / AWS (adjust based on your actual host)

---

## 📁 Folder Structure (Sample)

histochat/
├── client/ # React frontend
│ ├── components/ # Reusable UI components
│ ├── pages/ # Routes like /dashboard, /chat, /profile
│ ├── hooks/ # Custom React hooks
│ ├── utils/ # Helper functions
│ └── assets/ # Images, icons, etc.
├── server/ # Backend API
│ ├── routes/ # REST API endpoints
│ ├── controllers/ # Logic for chat, users, personas
│ ├── models/ # Mongoose / ORM schemas
│ └── config/ # Env, DB setup
└── README.md

---

## 🧪 Local Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/histochat.git
   cd histochat

2. **Install dependencies**
   ```bash
    cd client && npm install
    cd ../server && npm install

3. **Create .env files in both client/ and server/ as needed:**
   ```bash
    OPENAI_API_KEY=your_key
    MONGO_URI=your_db_uri
    JWT_SECRET=your_secret

4. **Run development**
   ```bash
    cd server && npm run dev
    cd ../client && npm run dev

## 🧑‍🏫 Use Cases

- 📚 **Learn History Interactively**  
  Chat with AI personas like *Einstein*, *Cleopatra*, or *Napoleon* to explore historical events and philosophies.

- 💻 **Build a Virtual Coding Tutor**  
  Create AI mentors who specialize in programming languages or technical interviews.

- 👩‍🏫 **Educators & Classrooms**  
  Teachers can design custom AI guides to assist students with coursework or simulate historical debates.

- 🌍 **Language Learning Roleplay**  
  Practice foreign languages by conversing with character-based AIs in immersive contexts.

---

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/a26da74a-261e-47c8-9170-97559e068738)



