# SoulSync – (Sync your thoughts and emotions with a support system)

SoulSync is a full-stack **MERN** application designed to help users take care of their mental well-being. It provides an engaging interface, secure authentication, and multiple features like a mood tracker, AI-powered therapist chat, mood quiz, and anonymous sharing — all integrated into one seamless platform.  

---

## 📌 Features  

### 🔑 Cookie Session Login  
- Secure user authentication using **cookie-based sessions**  
- Protects sensitive pages from unauthorized access  
- Maintains user login state across sessions  

### 📊 Mood Tracker  
- Users can log their mood daily  
- Visualizes progress over time  
- Data securely stored in the database  

### 🤖 AI Therapist  
- AI-powered chatbot using **Gemini API**  
- Provides instant, conversational support  
- Offers helpful suggestions based on user input  

### 🧠 Mood Quiz  
- Interactive quiz to assess current mood  
- Generates **personalized feedback** using Gemini API  
- Encourages self-awareness and self-improvement  

### 📝 Anonymous Sharing  
- Allows users to post feelings or experiences anonymously  
- Builds a supportive community space  
- No personal data is linked to shared posts  

### 🛠️ CRUD Functionality  
- Full **Create, Read, Update, Delete** operations for:  
  - User accounts  
  - Mood logs  
  - Community posts  

---

## 🏗️ Project Structure  

### **Frontend (React)**  
SoulSync-Frontend/
- **public/** – Static assets (images, favicon, HTML files)  
- **src/** – React components, pages, and application logic  
- **package.json** – Frontend dependencies  
- **tailwind.config.js** – TailwindCSS setup  
- **README.md** – Project documentation  

### **Backend (Node + Express)**
SoulSync-Backend/
- **config/** – Environment and database configurations  
- **controller/** – Application logic for API endpoints  
- **data/** – Sample or seed data  
- **database/** – Database connection setup  
- **models/** – Mongoose schemas and models  
- **multer/** – File upload configurations  
- **routes/** – API route definitions  
- **upload1/** – Temporary uploads  
- **uploads/** – Permanent storage for uploaded files  
- **server.js** – Backend server entry point  
- **package.json** – Backend dependencies  



## 🖥️ Tech Stack

**Frontend:**  
- React.js  
- Tailwind CSS  
- JavaScript / HTML / CSS  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- Multer (for file uploads)  

**Other Integrations:**  
- Gemini API (via RapidAPI) – AI therapist & mood quiz processing  
- Cookie-session for secure authentication
