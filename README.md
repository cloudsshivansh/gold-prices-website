Live Gold Prices in India 🌟

A beginner-friendly website showing real-time 24K, 22K, and 18K gold prices across Indian cities using Metals.Dev API, deployed on Render.

Prerequisites





Metals.Dev API Key: You already have 4OVRIY3QY8IXHU2KGGRF9132KGGRF (free, 100 requests/month).



GitHub Account: Create one at GitHub if you don’t have one.



Render Account: Sign up at Render for free hosting.

Project Structure

gold-prices-website/
├── index.html         # Main website file
├── README.md         # This file
└── .gitignore        # Ignores unnecessary files

Setup Instructions





Check API Key:





The API key 4OVRIY3QY8IXHU2KGGRF9132KGGRF is already in index.html. No changes needed unless it stops working.



Create GitHub Repository:





Go to GitHub and click "New Repository".



Name it gold-prices-website and make it public.



On your computer, follow these steps:





Create a folder named gold-prices-website.



Save index.html, README.md, and .gitignore in it.



Download Git if you don’t have it.



Open a terminal (Command Prompt on Windows, Terminal on Mac/Linux):

cd /path/to/gold-prices-website
git init
git add .
git commit -m "First upload"
git remote add origin https://github.com/your-username/gold-prices-website.git
git push -u origin main



Replace your-username with your GitHub username.



Upload to Render:





Go to Render and log in.



Click "New" > "Static Site".



Connect your GitHub account and select the gold-prices-website repository.



Leave Build Command blank and set Publish Directory to . (a dot).



Click "Create Static Site".



Wait a few minutes. Render will give you a URL (e.g., https://gold-prices-website.onrender.com).



Test Your Website:





Open the Render URL in your browser.



You should see gold prices for 24K, 22K, and 18K across Indian cities with emojis.

Notes





Free Limits: Render’s free tier may be slow on first load. Metals.Dev’s 100 requests/month are saved with a 24-hour cache.



India Focus: Prices are in INR with city variations.



Help: If something goes wrong, check Render’s logs or ask me!

🚀 You did it! Enjoy your website!
