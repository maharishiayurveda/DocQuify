# 🚀 DocQuify

**DocQuify** is a powerful AI-powered platform that helps users extract relevant information from research papers and technical documentation by asking natural language questions. Upload PDFs and ask context-based queries to get quick, accurate answers — without reading the entire document.

---

## ✨ Features

- 📄 **PDF Upload**: Upload research papers or technical docs for smart processing.
- ❓ **Context-Based Question Answering**: Ask questions and get answers directly from the uploaded content.
- 🔍 **Stay Updated**: Understand new tech trends by uploading the latest whitepapers or articles.
- 🔐 **Google Login Integration**: Secure, seamless sign-in using Clerk’s Google Auth.
- ☁️ **AWS S3 Storage**: Store and access documents reliably.
- 🧠 **AI + Vector Search**: Uses OpenAI and Pinecone for semantic search and precise answers.

---

## 🛠️ Tech Stack

| Layer         | Tech Used                         |
|---------------|-----------------------------------|
| Frontend      | Next.js, TypeScript               |
| Backend       | Node.js, Express.js, PostgreSQL   |
| Authentication| Clerk (Google Login)              |
| Storage       | AWS S3                            |
| AI & Search   | OpenAI API, Pinecone Vector DB    |

---
## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/docquify.git
cd docquify

2. Install Dependencies
bash
Copy
Edit
npm install

3. Set Environment Variables
Create a .env file in the root directory and add the following:

env
Copy
Edit
JWT_SECRET=your_jwt_secret
AWS_S3_BUCKET_NAME=your_bucket_name
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
OPENAI_API_KEY=your_openai_key
PINECONE_API_KEY=your_pinecone_key


4. Run the Development Server
bash
Copy
Edit
npm run dev
🤝 Contributing
We welcome contributions! To contribute:

Fork the repository

Create a new branch (git checkout -b feature-name)

Make your changes

Submit a pull request

Found a bug or have a suggestion? Feel free to open an issue.
 
 Let me know if:
- You want the markdown as a downloadable `.md` file.
- You have a live deployment link to add.
- You want to include screenshots or a GIF demo.


  
