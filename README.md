# 📝 AI Quick Blog (Full Stack + Gemini AI)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-Content_Gen-blue?style=for-the-badge)

### [🔴 LIVE DEMO ](https://ai-quick-blog-iota.vercel.app/)
*(Click above to view the application)*

---

### 🚀 **Overview**
**Quick Blog** is a production-ready **Full Stack Blogging Platform** designed for content creators. 
Unlike static blogs, this application features an **AI-Powered Writing Assistant** (integrated with Google Gemini API) that helps admins generate, expand, or summarize blog content instantly.

### 🛠 **Tech Stack**
* **Frontend:** React.js, Tailwind CSS (Responsive Design)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Atlas)
* **AI Integration:** Google Gemini API (for content generation)
* **Authentication:** JWT (JSON Web Tokens) & Custom Middleware

### ✨ **Key Features**
* **🤖 AI Content Generation:** Admins can draft entire articles or brainstorm ideas using the built-in Gemini AI tool.
* **🔐 Secure Admin Dashboard:** Complete CMS capabilities to Create, Edit, Publish, and Unpublish posts.
* **🛡️ JWT Authentication:** Secure login system with role-based access control (Admin vs. Reader).
* **💬 Real-Time Comments:** Users can engage with posts via a dynamic comment section.
* **📱 Fully Responsive:** Optimized for Mobile, Tablet, and Desktop using Tailwind CSS.

---

### 📸 **Screenshots**

| Admin Dashboard | AI Writing Tool |
| :---: | :---: |
| *(Add Screenshot 1)* | *(Add Screenshot 2)* |

---

### 🏃‍♂️ **How to Run Locally**

```bash
# Clone the repository
git clone [https://github.com/Manya2811/ai_quick_blog.git](https://github.com/Manya2811/ai_quick_blog.git)

# Navigate to backend and install dependencies
cd backend
npm install

# Setup Environment Variables (.env)
MONGO_URI=your_mongodb_string
JWT_SECRET=your_secret
GEMINI_API_KEY=your_gemini_key

# Run the Backend
npm start

# Navigate to frontend and start React
cd ../frontend
npm install
npm start
