# Sunday Class Attendance App

A single-file web app for tracking Sunday school attendance.  
All data is saved in the **browser's local storage** — no server or database needed.

---

## 📁 Files Included

| File | Description |
|------|-------------|
| `sunday_attendance_app.html` | The complete app (open this to run it) |
| `README.md` | This guide |

---

## 🔑 Default Login

| User ID | Password | Role |
|---------|----------|------|
| admin | admin123 | Admin (full access + user management) |
| teacher1 | pass1 | Teacher (attendance + reports) |

> **Change these passwords immediately after first login!**  
> Go to ⚙️ Manage → User Management → Change Your Own Password

---

## 👤 User Management

- **Admin** users can add, edit, and delete other users
- **Teacher** users can mark attendance and view reports
- To manage users: log in as admin → go to **⚙️ Manage** tab → **User Management** section

---

## 🖥️ How to Open / Install

### Option 1 — Open directly on Computer (Windows / Mac)
1. Double-click `sunday_attendance_app.html`
2. It will open in your default web browser (Chrome, Edge, Firefox, Safari)
3. That's it — no installation needed!

> 💡 **Tip for Mac**: Right-click the file → Open With → Google Chrome (recommended)

### Option 2 — Install as App on Desktop (Windows / Mac / Linux)
Using **Google Chrome** or **Microsoft Edge**:
1. Open the file in Chrome/Edge
2. Click the **⋮ menu** (top right) → **Cast, Save and Share** → **Install page as app** (Chrome) or **Apps → Install this site as an app** (Edge)
3. The app will appear in your taskbar/dock and can be opened like any desktop app

### Option 3 — Use on Phone (Android / iPhone)

**Android (Chrome):**
1. Open the file in Chrome (you can email it to yourself and tap it)
2. Tap the **⋮ menu** → **Add to Home Screen**
3. It appears on your home screen like a normal app

**iPhone / iPad (Safari):**
1. AirDrop or email the file to yourself, then open it in Safari
2. Tap the **Share** button (box with arrow) → **Add to Home Screen**
3. It appears on your home screen like a normal app

---

## ☁️ Host Online (Free — Access from Anywhere)

### Option A — Google Drive (Simplest, but preview only)
1. Upload `sunday_attendance_app.html` to **Google Drive**
2. Right-click → **Share** → Anyone with link can view
3. Open the link — it shows a preview. Click **Open** to run the app
> ⚠️ Google Drive preview mode may limit localStorage. Better to use GitHub Pages below.

### Option B — GitHub Pages (Free, Best for Sharing)
1. Create a free account at [github.com](https://github.com)
2. Click **New Repository** → name it `sunday-class` → set to **Public** → Create
3. Click **Add file** → **Upload files** → Upload `sunday_attendance_app.html`
4. **Rename** the file to `index.html` (click the pencil icon after upload)
5. Go to **Settings** → **Pages** → Source: **main branch** → Save
6. Your app will be live at: `https://YOUR-USERNAME.github.io/sunday-class/`

### Option C — Netlify Drop (Easiest free hosting)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Rename the file to `index.html` first
3. Drag and drop it onto the Netlify Drop page
4. Get a free URL instantly (e.g. `https://random-name.netlify.app`)
5. You can customize the URL in Netlify settings

### Option D — Firebase Hosting (Google Cloud)
1. Install [Node.js](https://nodejs.org)
2. Run: `npm install -g firebase-tools`
3. Run: `firebase login` → `firebase init hosting`
4. Put `index.html` (renamed from the app file) in the `public` folder
5. Run: `firebase deploy`
6. Get a URL like `https://your-project.web.app`

---

## 💾 Data Backup

Since data is stored in the browser:
- Use **⚙️ Manage → Export Students (CSV)** to back up student data
- Use **Export Attendance (CSV)** to back up attendance records
- If you change browsers or devices, re-import your CSV files

---

## ⚠️ Important Notes

- Data is saved **per browser per device** — different browsers on the same computer do NOT share data
- Clearing browser cache/cookies will erase app data — export CSV backups regularly
- For multi-device access, use the online hosting options above (but note each device still has its own local storage — use CSV export/import to sync)
