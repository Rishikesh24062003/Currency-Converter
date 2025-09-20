# 💱 Currency Converter

A simple and interactive **Currency Converter Web App** built with **React.js**.
It allows users to convert between different currencies using real-time exchange rates from a free API.

---

## 🚀 Features

* 🌍 Convert between multiple world currencies
* 🔄 Real-time exchange rates via [ExchangeRate API](https://api.exchangerate-api.com/)
* 📱 Responsive UI for desktop and mobile
* ⚡ Fast and lightweight (React + Fetch API)
* 🎨 Clean design with intuitive interface

---

## 📸 Screenshots

<img width="1440" height="855" alt="image" src="https://github.com/user-attachments/assets/4d7da7e3-0cd2-47b0-aa11-b69a742d4b69" />


---

## 🛠️ Tech Stack

* **Frontend:** React.js, JavaScript, CSS
* **API:** Exchange Rate API (or any other free currency API)
* **Build Tool:** Vite / Create React App (depending on your setup)

---

## 📂 Project Structure

```
Currency-Converter/
├── public/            # Static assets
├── src/
│   ├── components/    # Reusable React components
│   ├── App.js         # Main app component
│   ├── index.js       # React entry point
│   └── styles.css     # Global styles
├── package.json       # Dependencies and scripts
├── README.md          # Project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repo**

   ```bash
   git clone https://github.com/Rishikesh24062003/Currency-Converter.git
   cd Currency-Converter
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the app**

   ```bash
   npm start
   ```

   The app will run at [http://localhost:3000](http://localhost:3000).

---

## 🌐 API Setup

The app fetches real-time data from a free currency exchange API.
If you’re using a different API, update the URL in your `apiClient.js` (or wherever you fetch rates).

Example API call:

```javascript
fetch(`https://api.exchangerate-api.com/v4/latest/USD`)
  .then(res => res.json())
  .then(data => console.log(data));
```

---

## 📦 Deployment

* **Vercel** → `vercel --prod`
* **Netlify** → Drag & drop build folder
* **GitHub Pages** → `npm run build && gh-pages -d build`

---

## 📝 Future Enhancements

* ✅ Add historical currency charts 📊
* ✅ Dark mode toggle 🌙
* ✅ Offline caching with localStorage
* ✅ Multi-language support 🌐

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch (`feature-new`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature-new`)
5. Open a Pull Request
