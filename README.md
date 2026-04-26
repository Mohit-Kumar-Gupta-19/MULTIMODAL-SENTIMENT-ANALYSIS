#  Multimodal Sentiment Analysis

A web application for sentiment analysis using multiple data modalities.  
This project integrates frontend UI, Node.js backend logic, and Supabase for database/authentication.

🚀 **Live Demo:** https://multimodal-senti-analysis.vercel.app/

---

##  Overview

Multimodal Sentiment Analysis allows users to analyze sentiments using different data inputs such as text, image, audio, or video (depending on your supported features).  
This project demonstrates how to combine modern web UI with backend machine learning APIs and cloud database services.

---

## 🛠 Features

✔ Modern web interface  
✔ Sentiment prediction UI  
✔ Supabase integration  
✔ AJAX / API communication  
✔ Hosted live with Vercel

---

## 📁 Project Structure

📦 multimodal-sentiment-analysis ┣ 📂 public ┃ ┣ index.html ┃ ┗ i3.html ┣ 📂 src ┃ ┗ (JS, CSS, Backend files) ┣ .gitignore ┣ vercel.json ┣ README.md ┗ package.json

---

## 🧩 Technologies Used

| Layer | Tech |
|-------|------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js |
| Hosting | Vercel |
| Database / Auth | Supabase |
| Version Control | Git & GitHub |

---

## 📌 Installation (Local Development)

> Make sure you have **Node.js** installed on your machine.

1. Clone the repository  
```bash
git clone https://github.com/Mohit-Kumar-Gupta-19/MULTIMODAL-SENTIMENT-ANALYSIS.git

2. Navigate into project



cd multimodal-senti-analysis

3. Install dependencies



npm install

4. Create a .env file Copy your environment variables here:



SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

5. Start the app



npm start

Now open:

http://localhost:3000

If the app runs on a different port, check the terminal output for the correct URL.

🚀 Deployment

This project is deployed using Vercel.

✔ Push to GitHub
✔ Connect GitHub repo with Vercel
✔ Add environment variables in Vercel dashboard
✔ Automatic deployment with vercel.json routing config


---

📍 Routes

Path	Page

/	Main Home UI
/auth	Authentication / i3.html


This is handled with vercel.json routing:

{
  "routes": [
    { "src": "/auth", "dest": "/i3.html" }
  ]
}


---

🧪 Testing

Check console logs if API isn’t responding

Make sure Supabase keys are correct

Verify Vercel environment variables



---

🤝 Contributing

1. Fork the repo


2. Create a new branch



git checkout -b feature/your-feature

3. Commit your changes



git commit -m "Add your feature"

4. Push and open a pull request




---


🙌 Acknowledgements

Thanks to: ✨ Vercel
✨ Supabase
