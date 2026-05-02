# Skyways Travel Solutions — Website

## 📁 File Structure
```
skyways-github-site/
├── index.html        ← Main website
├── 404.html          ← Custom error page
├── _config.yml       ← GitHub Pages settings
├── _headers          ← Security headers
├── robots.txt        ← Controls search engine & bot access
├── sitemap.xml       ← Helps Google index your site
└── README.md         ← This file
```

---

## 🚀 How to Publish on GitHub Pages

### Step 1 — Create a GitHub Account
- Go to https://github.com and sign up for free

### Step 2 — Create a New Repository
- Click the **+** button → **New repository**
- Name it exactly: `skyways-travel` (or any name you like)
- Set it to **Public**
- Click **Create repository**

### Step 3 — Upload Your Files
- Click **uploading an existing file**
- Drag and drop ALL files from this folder
- Click **Commit changes**

### Step 4 — Enable GitHub Pages
- Go to your repo → **Settings** → **Pages** (left sidebar)
- Under **Source**, select **Deploy from a branch**
- Select branch: **main**, folder: **/ (root)**
- Click **Save**
- Your site will be live at `https://yourusername.github.io/skyways-travel`

### Step 5 — Connect Your Custom Domain (from Hostinger)
- In GitHub Pages settings, type your domain e.g. `www.skywaystravels.com`
- Click **Save** — GitHub shows you 4 IP addresses
- Log into Hostinger → **Domains** → **DNS Zone**
- Add 4 x **A records** pointing to GitHub's IPs:
  ```
  185.199.108.153
  185.199.109.153
  185.199.110.153
  185.199.111.153
  ```
- Add 1 x **CNAME record**:
  - Name: `www`
  - Value: `yourusername.github.io`
- Wait 10–30 minutes
- Tick **Enforce HTTPS** in GitHub Pages settings ✅

---

## 🔒 Security Features Included

| Feature | What it does |
|---|---|
| **No database** | Nothing to hack — pure HTML |
| **No third-party ads/scripts** | Zero risk of injected malware |
| **Content Security Policy** | Blocks unauthorised scripts from running |
| **X-Frame-Options: DENY** | Prevents your site being embedded in a fake site |
| **X-XSS-Protection** | Blocks cross-site scripting attacks |
| **X-Content-Type-Options** | Prevents MIME type attacks |
| **HTTPS enforced** | All traffic encrypted via free SSL |
| **robots.txt** | Blocks known malicious bots and scrapers |

---

## ✏️ How to Update the Website

To edit text, phone numbers, addresses etc:
1. Go to your GitHub repo
2. Click `index.html`
3. Click the **pencil icon** (Edit)
4. Make your changes
5. Click **Commit changes**
— Site updates automatically within ~1 minute

---

## 📞 Need Help?
Contact your web manager or refer back to your Claude chat for assistance.
