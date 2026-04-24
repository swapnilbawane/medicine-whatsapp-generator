# 💊 Medicine App (WhatsApp List Generator)

A simple tool to generate and send medicine lists on WhatsApp in seconds.

---

## 🚀 What this does

- Select preset (patient + doctor)
- Adjust medicines & quantity
- Generate formatted message
- Send directly on WhatsApp

Also supports manual entry if needed.

---

## 🧩 Setup (Follow step-by-step)

### Step 1: Copy the template (IMPORTANT)

Open this Google Sheet:

<a href="https://docs.google.com/spreadsheets/d/1CfkIzPTlsnh0Z4ApwJw3GOII7dBkwGl--nQEcOpvBRk/edit?usp=sharing" target="_blank">  
Open Template Sheet
</a>

Click:  
File → Make a copy
👉 Tip: Use Ctrl + Click (Windows/Linux) or Cmd + Click (Mac) to open in a new tab

This creates your personal version.

---

### Step 2: Set access (view-only)

In your copied sheet:

Click:  
Share

Set:  
Anyone with the link → Viewer

Click Done

---

### Step 3: Publish the sheet

Click:

File → Share → Publish to web

Settings:
- Entire document
- CSV

Click Publish

This step is required for the app to load your data.

---

### Step 4: Copy your Sheet ID

From your copied sheet URL:

https://docs.google.com/spreadsheets/d/XXXXXXXXXXXX/edit

Copy the part between `/d/` and `/edit`

Example:
XXXXXXXXXXXX

(This is your Sheet ID)

---

### Step 5: Update the app

Open index.html in a text editor (Notepad / VS Code)

Find:

    const SHEET_ID = "XXXXX";

Replace XXXXX with your Sheet ID

Save the file.

---

### Step 6: Open the app

Double-click index.html  
(or open it in Chrome)

Done 👍

---

## 📱 How to use

### Preset Mode
- Select preset  
- Adjust medicines if needed  
- Click Open in WhatsApp  

### Manual Mode
- Enter patient name and doctor  
- Type medicines (one per line)  
- Click Open in WhatsApp  

---

## 🖥️ Does this run locally?

Yes 👍

- No installation needed  
- No server required  
- Just open index.html in your browser  

Works best in Chrome.

---

## 🌐 Do I need to deploy it?

No ❌  
Deployment is not required.

---

### When should you deploy?

Only if you want:

- To share with family via a link  
- To use it across multiple devices  

---

### Optional: How to deploy

Upload the index.html file to:

- Netlify (drag & drop)
- GitHub Pages

You will get a link like:

https://your-app.netlify.app

---

## 🧠 Notes

- You can edit medicines anytime in your Google Sheet  
- Changes reflect automatically in the app  
- Internet is required to fetch data  

---

## ⚠️ Common issue

### Nothing is loading?

Make sure you did:

File → Share → Publish to web

---

## 💡 Example Use Cases

- Monthly medicine refill  
- Family prescriptions  
- OTC purchases  

---

## 🙌 That’s it

No login. No install. Just open and use.
