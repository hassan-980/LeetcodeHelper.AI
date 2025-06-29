# 🧩 LeetCode Problem Helper Extension

A Chrome Extension that gives you **smart AI-generated hints** directly on LeetCode problem pages. Designed to help you think better, not spoil the solution — ideal for learning, practice, and interviews.

---

## ⚡ Features

- 💡 **Instant Hint Button** on LeetCode problems  
- 🤖 **AI-generated hints** based on problem description  
- ⏱️ Save time by getting direction without full solutions  
- 🧠 Encourages problem-solving with the right level of guidance  
- 🧩 Works seamlessly with LeetCode UI  

---

## 📸 Screenshots

> _Include a few screenshots or a demo GIF here showing the extension on a LeetCode problem page with the "Generate Hint" button and a displayed hint._

---

## 🛠️ Tech Stack

- **Platform**: Chrome Extension (Manifest V3)  
- **Language**: JavaScript / HTML / CSS  
- **AI Backend**: OpenAI API (or other LLM)  
- **Optional Parser**: LeetCode DOM parsing for problem detection  

---

## 🧪 How It Works

1. Install the extension in your browser  
2. Open any [LeetCode](https://leetcode.com) problem  
3. Click the **"Generate Hint"** button  
4. A contextual, non-spoiler **hint** appears — just enough to guide you  
5. Use it to brainstorm your solution confidently

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/leetcode-hint-extension.git
```

### 2. Load as Unpacked Extension

1. Go to `chrome://extensions/` in your browser  
2. Enable **Developer Mode** (top right)  
3. Click **"Load unpacked"**  
4. Select the project directory  

---

## 📁 File Structure

```
leetcode-hint-extension/
├── manifest.json
├── background.js
├── content.js
├── popup.html
├── popup.js
├── styles.css
└── icons/
```

---

## ✨ Example Hint Output

> **Problem:** Two Sum  
> **Hint:** Try storing each number’s complement in a hash map as you iterate. Check if the current number exists in it.

---

## 🚧 Roadmap

- [ ] Add multiple hint levels (basic, intermediate, advanced)  
- [ ] Support for daily challenge detection  
- [ ] Optional solution reveal (opt-in)  
- [ ] Firefox support  
- [ ] User customization options (themes, hint style)

---

## 🤝 Contributing

Contributions are welcome!  
1. Fork this repo  
2. Make your changes  
3. Open a pull request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [LeetCode](https://leetcode.com) for their amazing problem set  
- [OpenAI](https://openai.com) for hint generation  
- Built with 💻 and 💙 by [Your Name](https://github.com/yourusername)
