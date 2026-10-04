# ♟️ Thindal Grandmaster Trophy — Event Certificate Generator

A web-based certificate generator built to celebrate **Thindal Grandmaster Trophy**, held at **PILA SCHOOL, Parvesh International Learners Academy**, organized by **ChessKidoo Chess Academy**.

Participants can enter their name, preview a personalized **Memorable Appreciation Certificate**, and print it — all from the browser with zero setup.

---

## ✨ Features

- 🏠 **Landing Page** — Beautiful front page featuring legendary Chess Grandmasters (Magnus Carlsen, Viswanathan Anand, Garry Kasparov, Bobby Fischer, Gukesh Damothiran, Rathanvel V S)
- 🏛️ **Organiser Credit** — Event *Managed & Coordinated by **Hindusthan Chess Cell***, with venue and date shown up front
- 📝 **Name Entry** — Simple form to enter participant name
- 🏅 **Category Selection** — Choose **Junior** (Under 9 / Under 12 / Under 15) or **Senior – Open**; the category is printed as a badge on the certificate
- 🏆 **Entry Type & Place** — Mark the entry as **Participant** or **Winner**; winners type their place, which resolves to First / Second / Third … on the certificate. **Junior** awards 5 places, **Senior – Open** awards 10
- 🔒 **Winner Code** — The organiser code field is always visible on the form (with a Show/Hide toggle so you can see what you typed). Winner certificates stay locked until the code is entered; Download / Print re-check it, and places 1–3 print `PRIZE : WINNER TROPHY`
- 🔢 **Certificate Number** — Every certificate gets a unique, random serial printed in the bottom bar, e.g. `CK/041026/137` (`CK` prefix · issue date `DDMMYY` · random number 1–500). The number is remembered per participant, so reloading never changes it
- 🔠 **Title Case Name** — Names are automatically normalised for a clean, formal look
- 📜 **Live Certificate Preview** — Instantly generates a personalized certificate with the entered name
- 📱 **Mobile First** — On phones the controls move to a thumb‑reachable bottom bar with 44px+ tap targets; the certificate scales to the screen with no sideways scroll
- ⬇️ **Download PDF** — Renders the certificate to a high‑resolution image and wraps it in a landscape PDF. Web fonts are embedded so the PDF matches the screen, and the raster step automatically retries at a lower resolution on memory‑constrained phones
- 🖨️ **Print-Optimized** — One-click printing with edge-to-edge landscape layout, no wasted space
- 🎨 **Rich Design** — Gold gradient text, decorative borders, larger organisation logos, and GM photos

> **Note on downloading:** the PDF export needs the page served over `http(s)` (the published link, or a local server such as `npx -y http-server`). Opening the files directly as `file://` works for viewing and printing, but browsers block reading local images for the export.

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
1. Open `index.html` → Enter your name → Choose Participant or Winner → Pick a category (Junior → age group, or Senior – Open) → If winner, type your place (`1`–`5` for Junior, `1`–`10` for Open) → Click **"Generate Certificate"**
2. Preview the personalized certificate (note the certificate number in the bottom bar)
3. Click **⬇ Download PDF** to save it, or **🖨 Print** to print
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
- **Google Fonts** — Outfit, Playfair Display, Pinyon Script (participant names are set in Times New Roman for maximum legibility)

No frameworks. No build tools. No dependencies. Just open and run.

---

## 🎓 Event Details

| Detail | Info |
|--------|------|
| **Event** | Thindal Grandmaster Trophy |
| **Date** | 4th October 2026 |
| **Venue** | PILA SCHOOL, Parvesh International Learners Academy |
| **Managed & Coordinated by** | Hindusthan Chess Cell |
| **Organizer** | ChessKidoo Chess Academy |
| **Categories** | Junior — Under 9 / Under 12 / Under 15 (5 places) · Senior — Open (10 places) |
| **Joint Secretary** | Vishnu |
| **Secretary** | Ranjith A.S. |
| **Founder** | Rathanvel V S (India's 99th Grandmaster) |
| **Certificate No. format** | `CK/DDMMYY/NNN` — e.g. `CK/041026/137` |

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Credits

- **Chess Grandmaster Photos** — Used for educational/event purposes
- **Certificate Design** — ChessKidoo Chess Academy
- **Built with** ♟️ by [THAMARAISELVAM-A](https://github.com/THAMARAISELVAM-A)
