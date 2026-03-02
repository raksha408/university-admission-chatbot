# 🎓 University Admission Chatbot

An AI-powered chatbot built using **Rasa (3.x)** that provides information about university admissions, available courses, fee structure, and general queries.

This project demonstrates core Conversational AI concepts including intents, stories, domain configuration, response handling, and conversation flow management.

---

## 🚀 Features

- 👋 Greets users
- 📚 Provides course list
- 📝 Explains admission process
- 💰 Shares fee details
- ℹ️ Gives course-specific information
- 🚫 Handles out-of-scope queries
- 👋 Ends conversation politely

---

## 🛠️ Tech Stack

- Python
- Rasa 3.x
- YAML
- VS Code
- Git & GitHub

---

## 📂 Project Structure (Descriptive)

### 1️⃣ `actions/`
This folder contains custom action files.
- `actions.py` – Used to define any custom Python actions (if required).

### 2️⃣ `data/`
This folder contains training data for the chatbot.
- `nlu.yml` – Contains intents and example user messages.
- `stories.yml` – Defines conversation flows between user intents and bot actions.
- `rules.yml` – Contains rule-based conversation handling.

### 3️⃣ `models/`
This folder stores trained Rasa models generated after running `rasa train`.

### 4️⃣ `domain.yml`
Defines:
- Intents
- Responses
- Actions
- Session configuration

### 5️⃣ `config.yml`
Contains the NLU pipeline and policies configuration used for training the chatbot.

### 6️⃣ `endpoints.yml`
Defines endpoints for action server or external integrations.

### 7️⃣ `credentials.yml`
Stores configuration for connecting the chatbot to messaging platforms (if integrated).

### 8️⃣ `README.md`
Project documentation file.

---

## 🖼️ Chatbot Preview

![Rasa Chatbot Screenshot](Screenshot/rasa_chatbot_1.png)

> Make sure the image is placed inside:
> `Screenshot/rasa_chatbot_1.png`

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/raksha408/university-admission-chatbot.git
cd university-admission-chatbot
```

### Step 2: Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install rasa
```

### Step 4: Train the Model

```bash
rasa train
```

### Step 5: Run the Chatbot

```bash
rasa shell
```

---

## 💬 Example User Queries

- Hi
- What courses are available?
- Tell me about the admission process
- What are the fees?
- Goodbye

---

## 📌 Future Improvements

- Add web interface
- Integrate database for dynamic responses
- Deploy on cloud (Render / Railway / AWS)
- Add multilingual support

---

## 👩‍💻 Author

Shriraksha Kulkarni

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.
