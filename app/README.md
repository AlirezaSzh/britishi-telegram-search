Sure! Here's a clean and professional `README.md` file in **English** for your Telegram Keyword Search project:

---

### 📄 `README.md`

````markdown
# 🔍 Telegram Keyword Search API

A FastAPI-based project that allows you to search for a specific keyword in Telegram channels or groups and download the results as a Word document (.docx).

## 🚀 Features

- Search public Telegram channels or groups for any keyword
- Export results to a styled Word (.docx) document
- Simple and user-friendly HTML interface
- Built with FastAPI and Telethon

## 🛠 Requirements

- Python 3.8+
- Telegram API credentials (get from [https://my.telegram.org](https://my.telegram.org))

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/telegram-keyword-search.git
cd telegram-keyword-search
````

2. **Create and activate a virtual environment (optional but recommended):**

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

3. **Install dependencies:**

```bash
pip install -r requirements.txt
```

4. **Create a `.env` file and add your Telegram API credentials:**

```env
API_ID=your_api_id
API_HASH=your_api_hash
PHONE_NUMBER=+1234567890
```

> **Important**: Make sure you’ve verified your number on [https://my.telegram.org](https://my.telegram.org) and enabled 2FA if needed.

## ▶️ Run the App

```bash
uvicorn main:app --reload
```

Then open your browser and go to [http://localhost:8000](http://localhost:8000)

## 🧪 How It Works

1. Enter a Telegram channel or group link (e.g., `https://t.me/examplechannel` or `@examplegroup`)
2. Enter the keyword you want to search for
3. Choose the number of messages to scan (e.g., 1000)
4. Click the "Search & Download" button
5. The app will search messages and generate a Word document with results

## 📂 Project Structure

```
telegram-keyword-search/
├── main.py               # Main FastAPI app
├── downloads/            # Folder where Word files are saved
├── requirements.txt      # Python dependencies
├── .env                  # API credentials (not committed to Git)
├── .gitignore
└── README.md
```

## 📌 Notes

* Only public Telegram channels/groups are supported.
* Make sure the account you're using has access to the target channel/group.

## 🛡 Security

* Do **NOT** share your `.env` or `.session` files publicly.
* Use `.gitignore` to avoid committing sensitive files.

## 📄 License

MIT License

```

---

Let me know if you want a shorter version or a version with deployment instructions (like for **Render**, **Docker**, or **Heroku**).
```
