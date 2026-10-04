# ♟️ Thindal Grandmaster Trophy — Event Certificate Generator

A web-based certificate generator built to celebrate **Thindal Grandmaster Trophy**, held at **PILA SCHOOL, Parvesh International Learners Academy**, organized by **ChessKidoo Chess Academy**.

Participants can enter their name, preview a personalized **Memorable Appreciation Certificate**, and print it — all from the browser with zero setup.

---

## ✨ Features

- 🏠 **Landing Page** — Beautiful front page featuring legendary Chess Grandmasters (Magnus Carlsen, Viswanathan Anand, Garry Kasparov, Bobby Fischer, Gukesh Damothiran, Rathanvel V S)
- 📝 **Name Entry** — Simple form to enter participant name
- 🏅 **Category Selection** — Choose **Junior** (Under 9 / Under 12 / Under 15) or **Senior – Open**; the category is printed as a badge on the certificate
- 🏆 **Entry Type & Place** — Mark the entry as **Participant** or **Winner**; winners additionally type their place `1`–`5`, which resolves to First / Second / Third / Fourth / Fifth Place on the certificate
- 🔒 **Winner Code** — Winner certificates stay locked until the organiser code is entered; Download / Print re-check it, and places 1–3 print `PRIZE : WINNER TROPHY`
- 🔠 **Auto Uppercase** — Names are automatically converted to uppercase for a professional look
- 📜 **Live Certificate Preview** — Instantly generates a personalized certificate with the entered name
- 🖨️ **Print-Optimized** — One-click printing with edge-to-edge landscape layout, no wasted space
- 🎨 **Rich Design** — Gold gradient text, decorative borders, organization logos, and GM photos

---

## 🚀 How to Use

### Option 1: Open Directly
Simply open `index.html` in any modern browser — no server required!

### Option 2: Local Dev Server
```bash
npx -y http-server -p 8080 -c-1
```
Then visit [http://localhost:8080](http://localhost:8080)

### Workflow
1. Open `index.html` → Enter your name → Choose Participant or Winner → Pick a category (Junior → age group, or Senior – Open) → If winner, type the place `1`–`#5` → Click **"Generate Certificate"**
2. Preview the personalized certificate
3. Click **🖨 Print** to print or save as PDF
4. Click **← Back** to generate another certificate

---

## 📁 Project Structure

```
├── index.html                    # Landing page with name entry form
├── Chess Certificate 2026.html   # Certificate template with print layout
├── carlsen.png                   # Magnus Carlsen photo
├── anand.png                     # Viswanathan Anand photo
├── gukesh.png                    # Gukesh Damothiran photo
├── kasparov.png                  # Garry Kasparov photo
├── fischer.png                   # Bobby Fischer photo
├── rathanvel.png                 # Rathanvel V S photo
├── logo2.png                     # ChessKidoo logo
├── logo3.png                     # MSME logo
├── pila-logo.JPEG                # PILA School (venue) logo — renamed from "pila school  logo.JPEG"
├── .gitignore
├── README.md
└── LICENSE
```

---

## 🛠️ Tech Stack

- **HTML5** — Structure and layout
- **CSS3** — Styling, gradients, responsive print media queries
- **Vanilla JavaScript** — Name processing, toolbar, print handling
- **Google Fonts** — Outfit, Playfair Display, Pinyon Script

No frameworks. No build tools. No dependencies. Just open and run.

---

## 🎓 Event Details

| Detail | Info |
|--------|------|
| **Event** | Thindal Grandmaster Trophy |
| **Date** | 19th July 2026 |
| **Venue** | PILA SCHOOL, Parvesh International Learners Academy |
| **Organizer** | ChessKidoo Chess Academy |
| **Categories** | Junior — Under 9 / Under 12 / Under 15 · Senior — Open |
| **Director** | Ranjith A.S. |
| **Founder** | Rathanvel V S (India's 99th Grandmaster) |

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Credits

- **Chess Grandmaster Photos** — Used for educational/event purposes
- **Certificate Design** — ChessKidoo Chess Academy
- **Built with** ♟️ by [THAMARAISELVAM-A](https://github.com/THAMARAISELVAM-A)
