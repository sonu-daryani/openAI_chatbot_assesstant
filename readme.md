# 💬 Flask Chatbot UI (OpenAI + Tailwind CSS)

A lightweight chatbot UI built with **Flask**, styled using **Tailwind CSS**, and powered by **OpenAI GPT** (`gpt-3.5-turbo` by default). Uses [`uv`](https://github.com/astral-sh/uv) for fast Python dependency and environment management.

---

## ✨ Features

- ⚡ Fast environment & package setup using `uv`
- 💬 Real-time chatbot interface powered by OpenAI
- 🎨 Clean, responsive UI with Tailwind CSS (via CDN)
- 🧠 Easily switch between GPT models (gpt-3.5 / gpt-4)

---

![image]('/demo.png')

## 📦 Requirements

- Python 3.8+
- OpenAI API key → https://platform.openai.com/account/api-keys
- [`uv`](https://github.com/astral-sh/uv) (optional but recommended)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/flask-chatbot-ui.git
cd flask-chatbot-ui
````

### 2. Create Environment and Install Dependencies (with `uv`)

> If you don't have `uv` installed:

```bash
curl -Ls https://astral.sh/uv/install.sh | sh
```

Then run:

```bash
uv venv .venv
source .venv/bin/activate        # On Windows: .venv\Scripts\activate
uv pip install -r requirements.txt
```

> ✅ You can also use `pip` and `python -m venv` if you prefer.

---

### 3. Add Your OpenAI API Key

Create a `.env` file in the root:

```
OPENAI_API_KEY=your_openai_key_here
```

---

### 4. Run the App

```bash
python app.py
```

Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧪 Example Conversation

```
You: How do I center a div in Tailwind?
Bot: You can use 'flex justify-center items-center' on the parent container.
```

---

## 📁 Project Structure

```
flask-chatbot-ui/
├── app.py
├── .env
├── requirements.txt
├── templates/
│   └── index.html
└── static/         # (optional)
```

---

## 🧠 Tech Stack

| Tool         | Purpose                    |
| ------------ | -------------------------- |
| Flask        | Backend Web Server         |
| OpenAI API   | Chatbot Engine (GPT)       |
| Tailwind CSS | UI Styling                 |
| uv           | Dependency/venv management |

---

## 🧹 Cleanup / Deactivation

```bash
deactivate           # exit virtual environment
rm -rf .venv         # delete environment (optional)
```

---

## 📄 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙌 Contributing

Contributions welcome! Fork it and open a PR.

---

## ✨ Coming Soon

* Chat history per session
* Streaming responses (real-time typing)
* Authentication (login to save conversations)

---

## 📬 Contact

Feel free to reach out via issues or [@sonu7524](https://github.com/sonu7524)

```

---

Let me know if you’d like:

- A deployable version on Render/Vercel/Replit
- Dark mode support
- Streamed typing UI

Happy coding!
