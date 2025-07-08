# 📡 GPS to Telegram

A simple **HTML + JavaScript** project to capture the user’s GPS location and send it to your Telegram chat using a Telegram Bot.

---

# 🚀 How It Works

- When someone opens the page, it asks for GPS location permission.
- If allowed, it fetches **latitude**, **longitude**, and **accuracy**.
- It sends this information to your **Telegram Bot**.
- It also shares a clickable Google Maps link.

---

# ⚙️ Setup & Usage

## ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/localhostvicky/GPS_Tracking
cd GPS_Tracking
```

---

## ✅ Step 2: Create a Telegram Bot

1. Open Telegram and search for **@BotFather**  
2. Start the chat and type `/newbot`  
3. Follow the instructions and get your **Bot Token**  
4. Copy your Bot Token safely

---

## ✅ Step 3: Get your Chat ID

1. Open Telegram and search for **@userinfobot** or **@getidsbot**  
2. Start the bot — it will show your **User ID (Chat ID)**

---

## ✅ Step 4: Edit `index.html`

1. Open the `index.html` file in any text editor  
2. Find the lines:

   ```js
   const botToken = "YOUR_BOT_TOKEN"; // Replace with your Bot token
   const chatId = "YOUR_CHAT_ID";     // Replace with your Chat ID
   ```

3. Replace `YOUR_BOT_TOKEN` and `YOUR_CHAT_ID` with your actual Bot Token and Chat ID

---

## ✅ Step 5: Test Locally

1. Double-click the `index.html` file to open it in your browser  
2. Allow location permission  
3. Check your Telegram — you should get a location message!

---

## ✅ Step 6: Host it Online (GitHub Pages)

1. Push your project to a GitHub repository  
2. Go to **Repository Settings** → **Pages**  
3. Under **Source**, select the `main` branch and `/root` folder  
4. Click **Save** — GitHub will give you a **public URL**  
5. Open that URL in your browser  
6. Allow location permission — done!

---

# ✅ Example Message

```
📍 New Location:
Latitude: 28.7041
Longitude: 77.1025
Accuracy: 20 meters
https://maps.google.com/?q=28.7041,77.1025
```

---


# ✅ Author

Made with ❤️ by Vicky Chauhan
