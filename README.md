# 🔒 SecureClick – Malicious Redirect Blocker Extension

SecureClick is a lightweight Chrome extension that detects and blocks suspicious redirects, popups, and unwanted video hijacks (like YouTube auto-opens) when users click on links across untrusted websites.

> 🔐 Designed to protect users from phishing, redirect scams, and malicious behavior triggered by accidental clicks.

---

## 🚀 Features

- ✅ Detects and blocks forced redirects  
- ✅ Prevents unwanted video launches or popup hijacks  
- ✅ Alerts user with non-intrusive notifications  
- ✅ Allows whitelisting trusted websites  
- ✅ Built for speed and performance  

---

## 🛠️ Tech Stack

- JavaScript  
- Chrome Extensions API  
- Manifest V3  
- Storage API (for trusted site sync)

---

## 📦 Folder Structure

SecureClick/
├── background.js
├── content.js
├── popup.html
├── popup.js
├── style.css
├── icons/
└── manifest.json


---

## 📸 Screenshots

![SecureClick Demo](./screenshots/secureclick-demo.gif)

> 📝 Add your actual GIF or PNG inside a `screenshots/` folder in your repo.

---

## 🔧 How to Use

1. Clone or download this repository  
2. Go to `chrome://extensions/`  
3. Enable **Developer Mode**  
4. Click **Load unpacked**  
5. Select the `SecureClick` project folder  
6. You're protected! 🛡️

---

## 💾 Storage Sync

SecureClick uses `chrome.storage.sync` to auto-sync your list of trusted websites across devices where you're logged into Chrome.

---

## 📌 Roadmap

- [ ] Enable dynamic threat-level scoring  
- [ ] Integrate with Google Safe Browsing API  
- [ ] Export/Import trusted site list  
- [ ] Firefox support  

---

## 🧠 Author

- 👩‍💻 **Sai Sharanya**  
- GitHub: [sharanya330](https://github.com/sharanya330)  
- Project Link: [SecureClick Repo](https://github.com/sharanya330/secureclick)

---

## 📃 License

This project is licensed under the MIT License.
