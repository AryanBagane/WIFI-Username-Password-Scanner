# 📶 Wi-Fi QR Credentials Reveal

This project provides a stylish and secure way to share your **Wi-Fi credentials!**  
When someone scans your QR code, a modern animated webpage opens with a **curtain effect**, a **custom message**, and your **Wi-Fi SSID and password**—all displayed in a visually appealing manner.

---

## ✨ Features
- 🎭 Animated curtain reveal for extra flair  
- 💬 Custom slang/message at the top (Marathi or any language)  
- 📡 FontAwesome Wi-Fi icon  
- ⚙️ Easy to customize credentials and colors  
- 📱 Responsive—works on phones and computers  
- 🗂️ No backend or database, just a single HTML file  
- 🚀 Free hosting on Vercel or any static site host  

---

## 🚀 Quick Start

### 1. Deploy on Vercel
1. Go to [https://vercel.com/](https://vercel.com/).
2. Drag and drop your `index.html` or link your GitHub repo.
3. Obtain your public deployment URL (e.g. `https://yourdomainname.vercel.app/`).

### 2. Generate QR Code
1. Visit [qr-code-generator.com](https://www.qr-code-generator.com/) (or similar).  
2. Paste your **Vercel URL** and create the **QR code**.  
3. Print or save the QR for guests to scan.

---

## 🛠️ Customization

### Edit your credentials:
```html
<span id="ssid">Your_Username</span>
<span id="passwd">Your_password</span>
```

### Change the slang/message:
```html
<div class="slang">हवा आहे ती वाय-फाय ची, घे उडवून!</div>
```

### Change colors/styles:
Tweak colors in the `<style>` tag at the top of `index.html`.

---

## 📷 Example
When scanned, your QR code opens a page showing:
- ✨ Animated curtains  
- 💬 Your chosen phrase/message  
- 📡 Wi-Fi icon (FontAwesome)  
- 💳 Styled SSID and password card  

---

## 🏆 Why Use This?
✅ Saves time: no need to type passwords or repeat yourself to guests.  
🎨 Fun, personalized, and visually impressive.  
📴 Works offline after loading once.  

---

## 📄 License
**MIT License**  
Free to use, modify, and share.  

---

Made with ❤️ for stress-free Wi-Fi sharing!
