# SimplePace ⛳️

**SimplePace** is a lightweight web-based application that helps golf course staff — especially marshals and starters — monitor pace of play by tracking cart start times and estimating their location on the course.

---

## 🔧 Features

- 🕐 **Cart Start Time Logging**  
  Marshals enter each cart's start time manually.

- ⛳ **Hole Estimation Engine**  
  Calculates the cart's estimated location on the course based on elapsed time:
  - 0–4 min = Tee (`T`)
  - 5–9 min = Fairway (`F`)
  - 10–14 min = Green (`G`)
  - Every 15 minutes = progress to the next hole

- 🔁 **Live Refresh Button**  
  Updates all cart hole estimates with one click.

- 🧹 **Auto Clear After 6 Hours**  
  Each cart record auto-resets 6 hours after its start time.

- 🎨 Branded Interface  
  Includes logo, golf-friendly styling, and clean table layout.

---

## 🚀 Deployment

This is a static HTML application — no build steps required.

### Host on Netlify
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Upload the ZIP containing `index.html` and `fulllogo_nobuffer.jpg`
3. Done!

### Or Use Your Own Hosting
Upload both files to your server’s public folder.

---

## 📁 Files

- `index.html` – the main app
- `fulllogo_nobuffer.jpg` – your branded logo

---

## 🧠 Philosophy

SimplePace is designed to be:
- Easy to use on smartphones
- Free of GPS or expensive integrations
- Focused on user clarity and golf course operations

---

## 📬 Questions or Feedback?

Built by [Pathway Golf](https://www.pgigolf.golf)  
For suggestions, email [timothytobin@pgigolf.golf](mailto:timothytobin@pgigolf.golf)
