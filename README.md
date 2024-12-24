# 🌟 Shortify: Your URL Wizard

Welcome to **Shortify**, a modern and interactive URL shortener! This project allows users to convert long URLs into short, shareable links while tracking their click statistics. 🚀

---

## ✨ Features
- 🔗 **Generate short and shareable URLs**
- 📊 **Track the number of clicks** for each URL
- 🎨 **Beautiful, responsive, and interactive UI**
- 💡 **Easy-to-use** with validations for URL inputs

---

## 🚀 How to Run the Project

Follow these steps to get **Shortify** up and running on your local machine:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/shortify-url-wizard.git

```
### 2️⃣ Navigate to the Project Directory
```bash
cd shortify-url-wizard
```
### 3️⃣ Install Dependencies
Ensure you have [Node.js](https://nodejs.org/) installed, then run:
```bash
npm install
```

### 4️⃣ Start the Server
```bash
npm start
```

### 5️⃣ Open in Your Browser
The application will be running at:
```bash
http://localhost:8001
```
Click the link above or copy it easily: [📋 Copy URL](javascript:void(0);)

---

## 📁 Project Structure

```
shortify-url-wizard/
├── controllers/         # Contains the logic for URL handling (e.g., url.js)
├── models/              # Database models (e.g., url.js)
├── node_modules/        # Project dependencies
├── routes/              # Application routes (e.g., staticRouter.js, url.js)
├── views/               # EJS templates (e.g., home.ejs)
├── connect.js           # Database connection setup
├── index.js             # Main server entry point
├── package.json         # Project metadata and dependencies
├── package-lock.json    # Dependency lock file
└── README.md            # Project documentation
```

---

## 📋 API Routes

| HTTP Method | Endpoint           | Description                     |
|-------------|--------------------|---------------------------------|
| `POST`      | `/url`             | Create a new short URL          |
| `GET`       | `/url/:shortId`    | Redirect to the original URL    |
| `GET`       | `/`                | Home page with URL statistics   |

---

## 🎯 Prerequisites
- **Node.js** (v14 or higher) 🌐
- **npm** (v6 or higher) 📦

---

## 👩‍💻 Technologies Used
- **Node.js** for backend development.
- **Express.js** for server-side routing.
- **EJS** for templating.
- **MongoDB** for database storage.
- **Postman** for testing APIs.
- **CSS3** for styling.
- **JavaScript** for interactivity.

---


## ✍️ How to Contribute
We ❤️ contributions! Follow these steps to contribute:

1. Fork this repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Added a cool feature"
   ```
4. Push your changes:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request. 🎉

---

## 🛠️ Troubleshooting

- If you encounter issues, ensure all dependencies are installed by running:
  ```bash
  npm install
  ```

- Double-check that you are running the server on the correct port: **8001**.



---

## 🌟 Show Your Support
If you liked this project, please ⭐ the repository and share it with your friends! 😊

---

## 🤝 Connect With Me
- **GitHub**: [TOHIDKHAN4844](https://www.github.com/TOHIDKHAN4844)
- **LinkedIn**: [Tohid Khan](https://www.linkedin.com/in/tohid-khan-937509258/)

---

### 🛡️ Made with ❤️.
```
