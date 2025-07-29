
#  Video\_Connect\_Agora

**Video\_Connect\_Agora** is a real-time video calling web application powered by [Agora.io](https://www.agora.io/). It allows users to initiate or join secure video calls with low latency and high quality, all from the browser.

---

## 🚀 Features

* One-to-one and group video calls
* Unique room generation for each call
* Real-time communication with WebRTC via Agora SDK
* Responsive UI for both desktop and mobile browsers
* Easy room sharing via URL

---

## 🛠 Tech Stack

* HTML / CSS / JavaScript
* [Agora Web SDK](https://docs.agora.io/en/)
* Node.js (for running the server)
* Express.js

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Video_Connect_Agora.git
cd Video_Connect_Agora
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Add Agora App ID

Create a file named `.env` in the root directory and add your Agora App ID:

```
AGORA_APP_ID=your_agora_app_id_here
```

You can get the App ID from the [Agora Developer Console](https://console.agora.io/).

### 4. Run the App

```bash
node server.js
```

Open your browser and navigate to:
**[http://localhost:3000](http://localhost:3000)**

---

## 📁 Project Structure

```
Video_Connect_Agora/
├── public/                # Frontend assets (HTML, CSS, JS)
├── server.js              # Main backend server using Express
├── .env                   # Environment variables (Agora App ID)
├── package.json           # Node.js dependencies
└── README.md              # Project documentation
```

🤝 Contributing

Pull requests and issues are welcome! If you’d like to contribute:

    Fork the repository

    Make your changes

    Submit a pull request


