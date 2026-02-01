<!-- need bufftek title center div -->
<div align="center"><h1>BuffTeks Commit Ritual</h1></div>

# <div align="center"><img src="https://buffteks.org/media/49d17137a37f59fb62acc5b5d87273bfff50039da527e3a2df5474c4.png" alt="BuffTeks Logo" width="300" /></div>


Welcome to the **BuffTeks Commit Ritual** — a digital rite of passage for new members of the **BuffTeks Student Organization** at **West Texas A&M University**.  

This interactive CLI (Command Line Interface) experience teaches you how to use **Git** and **GitHub** while earning your place in the official **BuffTeks Hall of Fame** 🏆.  

Every new member’s name is etched into this README — forever part of our shared developer legacy.

---

## ⚙️ What Is This?

The **Commit Ritual** is a hands-on onboarding application that simulates real-world software development practices.  
It’s built with ❤️ using **Python**, **Rich**, and **GitHub’s API**, combining education with a BuffTeks experience.

🧠 Learn:
- How to use **version control** (Git + GitHub)
- How to **branch, commit, and push**
- How to collaborate and **merge your work safely**
- How automation can update live documentation (like this one!)

---

## 🧱 Project Structure

````

buffteks-commit-ritual/
│
├── main.py          # Entry point – orchestrates the ritual
├── ritual/          # Contains all ritual-related files
│   ├── __init__.py  # Makes this a Python package
│   ├── ui.py            # Handles Rich visuals (progress bars, banners)
│   ├── logic.py         # Adds users to the Hall of Fame
│   └── validator.py     # Runs system and dependency checks
│
├── README.md        # You’re reading it right now
├── HOW-TO-GUIDE.md  # Step-by-step contributor instructions
└── requirements.txt # Required packages

````


## 🔧 Environment Setup (Windows, macOS, Linux)

To ensure everyone can run the Commit Ritual smoothly, follow these steps to create a **Python virtual environment**, install dependencies, and run the application.

This keeps your environment clean and prevents dependency conflicts.

### 🪟 Windows Setup (PowerShell)

```powershell
# 1. Navigate to project folder
cd buffteks-commit-ritual

# 2. Create a virtual environment
python -m venv venv

# 3. Activate virtual environment
.env\Scripts\Activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the ritual
python main.py
```

### 🍎 macOS Setup (Terminal)

```bash
# 1. Navigate to project folder
cd buffteks-commit-ritual

# 2. Create a virtual environment
python3 -m venv venv

# 3. Activate virtual environment
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the ritual
python main.py
```

### 🐧 Linux Setup (Ubuntu/Debian/Fedora/Arch)

```bash
# 1. Navigate to project folder
cd buffteks-commit-ritual

# 2. Create a virtual environment
python3 -m venv venv

# 3. Activate virtual environment
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the ritual
python main.py
```

### ❗ Important Notes

- You **must activate** the virtual environment every time you run the ritual.
    
- To **exit** the virtual environment:
    
    ```bash
    deactivate
    ```
    
- If `python` doesn’t work, try `python3`.
    
- If `pip` doesn’t work, try `pip3`.


---

## 🚀 How It Works

1. **Run the ritual**
   ```bash
   python main.py
   ````

2. The system will:
   * Validate your environment 🔍
   * Load the BuffTeks Ritual Workshop ⚙️
   * Verify your GitHub username via API 🌐
   * Append your name to the Hall of Fame 🏆
   * Display your successful initiation 🎉

3. Then you’ll see your name appear **right here** ↓
   *(yes, in this very README!)*

---

## 🏆 BuffTeks Hall of Fame

> *Where every commit is a contribution...*

| Name         | GitHub                                       | Join Date  |
| ------------ | -------------------------------------------- | ---------- |
| Seth Crump | [@scrump05](https://github.com/scrump05) | 2025-10-28 |
| Benjamin Mosley | [@benny-ui-ux](https://github.com/benny-ui-ux) | 2025-11-10 |
| Abubacar "AD" Diallo | [@ad1135773](https://github.com/ad1135773) | 2025-11-20 |
| Haylee Torres | [@htorres38](https://github.com/htorres38) | 2025-12-02 |
| Jody Holt | [@ricearoni1245](https://github.com/ricearoni1245) | 2026-01-31 |

---

## 🧩 Want to Join?

We welcome **new members**, **mentors**, and **contributors** from all majors and experience levels.

👉 To begin your journey, read the **[HOW-TO-GUIDE.md](HOW-TO-GUIDE.md)** for setup and contribution steps.
It’s beginner-friendly, fast, and fully automated.

<!-- ---

## 💡 Why We Built This

We believe learning Git and GitHub shouldn’t be intimidating — it should be **interactive, visual, and fun**.
The BuffTeks Commit Ritual turns version control into a shared experience that celebrates collaboration.

Every new commit is a new BuffTeks story.
Every contribution strengthens our community.
And every name here marks a moment of growth. -->

---

## 🧰 Tech Stack

| Component        | Description                |
| ---------------- | -------------------------- |
| **Python 3.10+** | Base language              |
| **Rich**         | CLI visuals and animations |
| **Inquirer**     | User input prompts         |
| **Requests**     | GitHub API integration     |
| **Git**          | Version control backbone   |

---

## 📜 License & Ownership

This project is maintained by the **BuffTeks Student Organization**
West Texas A&M University – Paul & Virginia Engler College of Business

📄 Licensed under the **MIT License**
© 2025 BuffTeks Organization

---

## 👥 Team & Acknowledgments

**Project Leads:** Jesus Torres & Benjamin Mosley
**Faculty Advisor:** Dr. Carl Zhang
**Contributors:** The BuffTeks Family 💻
**Special Thanks:** Every student who commits to learn, grow, and share.
**Visit us at:** [buffteks.org](https://buffteks.org)

---

### 🐃 “Commit your name. Join the legacy. Leave your mark.”
