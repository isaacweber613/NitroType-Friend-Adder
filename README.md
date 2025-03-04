# NitroType-Friend-Adder Bookmarklet
A JavaScript bookmarklet to automatically press the "add friend" button on nitrotype.com/friends on the recent tab
# 🚀 NitroType Friend Adder Bookmarklet

## 🔹 Features
✅ **Clicks all "Add Friend" buttons automatically**  
✅ **Random delay** between **0.3s and 0.9s** per click to avoid detection  
✅ **Easy to use**—just save it as a bookmark and click!  
✅ **No extensions needed!**  

---

## 📌 How to Use
### **Step 1: Create a Bookmark**
1. Copy this code:
   ```javascript
   javascript:void(function(){let b=Array.from(document.querySelectorAll('.btn.btn--positive.btn--thinner')).filter(b=>b.innerText.includes("Add Friend")&&!b.classList.contains("is-success")),d=()=>Math.random()*(900-300)+300,i=0;function c(){i<b.length?(b[i].click(),console.log(`✅ Clicked 'Add Friend' button ${i+1} of ${b.length}`),i++,setTimeout(c,d())):alert("🎉 All friends added!")}b.length>0?c():alert("No 'Add Friend' buttons found!")})();

2. Open your browser’s bookmarks manager.
3. Click "Add New Bookmark".
4. Paste the copied code into the URL field.
5. Name it something like "NitroType Auto Add Friends". or something very short so it doesn't take up to much space in the bookmarks bar
6. Save the bookmark.

**Step 2: Use the Bookmarklet**
1. **Go to [NitroType Friends Page](https://www.nitrotype.com/friends)**.
2. Click on the **Recent** tab.
3. Click your **NitroType Auto Add Friends** bookmark.
4. Watch it **automatically add all friends** with random delays! 🎯🔥

---

## 🛠️ Advanced Settings
Want to tweak the script? Change the delay timing here:
```javascript
d = () => Math.random() * (1500 - 800) + 800; // Random delay between 0.8s and 1.5s
```
- **Faster clicks** → Use `(700 - 300) + 300`
- **Slower clicks** → Use `(2000 - 1000) + 1000`

## 💡 Credits
Made with ❤️ by [isaacweber613](https://github.com/isaacweber613)  with the help of ChatGPT
Feel free to **fork & improve**! 🚀

---

## ⚠️ Disclaimer
This script is **not affiliated with or endorsed by NitroType**. Use at your own risk.

- The author **is not responsible** for any consequences of using this script.
- There is **no guarantee** that NitroType will always allow this to work.
- Use this script **ethically and responsibly**.
- By using this script, **you agree that the author is not liable** for any account issues, bans, or other consequences.

If you have concerns about using this script, **do not use it**.

---

## 🌐 Website
Try the bookmarklet directly at:  
🔗 **[NitroType Friend Adder](https://isaacweber613.github.io/NitroType-Friend-Adder/)**  

