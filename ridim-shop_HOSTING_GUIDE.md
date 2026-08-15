# Ridim Shop Version 1.0 - Hosting & Setup Guide

## 1. Firebase Config Setup (ফায়ারবেস কনফিগারেশন)
1. https://console.firebase.google.com -এ গিয়ে একটি প্রজেক্ট খুলুন।
2. **Authentication** সেকশন থেকে Email/Password ইনেবল করুন।
3. **Firestore Database** ক্রিয়েট করুন (Test mode)।
4. Project Settings থেকে Web App যুক্ত করে API Key সংগৃহীত কনফিগ ফাইলটি `js/firebase.js` ফাইলের `firebaseConfig` অবজেক্টে বসিয়ে দিন।

## 2. GitHub & Netlify / Vercel (ফ্রি হোস্টিং)
1. **GitHub Repository:** পুরো `ridim-shop` ফোল্ডারটি আপনার GitHub অ্যাকাউন্ট এ একটি নতুন রিপোজিটরিতে Push করুন।
2. **Netlify:** Netlify.com এ গিয়ে 'Import from Git' দিয়ে উক্ত রিপোজিটরিটি যুক্ত করুন। Build Command খালি থাকবে, Publish Directory থাকবে `/` বা root.
3. পাবলিশে ক্লিক করলে ১ মিনিটের মধ্যে আপনার ওয়েবসাইটটি লাইভ হয়ে যাবে।
