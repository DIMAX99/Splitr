# 🤝 Contributing to Splitr

Thank you for your interest in contributing to **Splitr**! 🎉  
We’re thrilled to have you on board and can’t wait to see your ideas come to life.  

# 📌 Project Overview
Splitr is an AI-powered expense-sharing web app built with Next.js, TypeScript, Tailwind CSS, and Convex.
It simplifies splitting bills between friends, tracking payments, and managing shared expenses with AI-assisted summaries.

# Tech Stack & Requirements

- ⚡ **Next.js 14** + **JavaScript** + **Tailwind CSS**
- 🛠 **Convex** (Backend)
- 🔑 **Clerk** (Authentication)
- 🤖 **Gemini AI API** (AI features)

## 🛠 Tech Stack & Requirements
- Node.js ≥ 18
- npm or yarn
- Convex CLI (`npm install -g convex`)
- Clerk test credentials (shared by project admin)

---
# 🚀Getting Started (Setup Instructions)

## 1. Fork the repository
## 2. Clone your fork
   `git clone https://github.com/<your-username>/Splitr.git`

## 3. Install dependencies
npm install

## 4. Start Convex
npx convex dev

## 5. Run the app
npm run dev

🔹 Environment Variables (create .env.local):

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=...
CLERK_SECRET_KEY=...
CONVEX_DEPLOYMENT=...
RAZORPAY_KEY_ID=...
RAZORPAY_KEY_SECRET=...
OPENAI_API_KEY=...

# Contribution Workflow

1. Pick an Issue → Check GitHub Issues with good first issue or help wanted.
2. Discuss Before Coding → Comment under the issue to get assigned.
3. Create a New Branch:
   `git checkout -b feature/your-feature-name`
   
4. Make Changes & Test Locally
5. Commit:
  `git commit -m "feat: add expense filtering by category"`

6. Push & Open PR:
  `git push origin feature/your-feature-name`

8. PR Review Process → At least 1 approval before merging.

# 🏷Issue Labels

* 🟢good first issue → Easy, beginner-friendly
* 🟡 help wanted → Needs extra eyes
* 🐛bug → Something is broken
* ✨enhancement → Feature improvements
* 📄documentation → README or doc updates

# 📏Code Style Guidelines

* Follow JavaScript strict mode
* Prettier for formatting (npm run format)
* Descriptive commit messages (Conventional Commits format)
* No direct commits to main


# 🗣 Communication

* 💬 GitHub Discussions for ideas & queries
* 📢 GSSoC Discord for community chats
* 📧 Contact Dhruv Bajaj (Project Admin) at d4bajaj@gmail.com for urgent issues


# 💡First PR Ideas

* Improve README visuals (badges, screenshots)
* UI polish (empty state screens, loading spinners)
* Create reusable components for buttons, modals
* Write utility functions for expense calculations

# 📜 Code of Conduct
Please read our Code of Conduct before participating.
