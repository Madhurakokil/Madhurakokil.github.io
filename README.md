# Madhurakokil.github.io

# 📝 How to Host a Blog on GitHub Pages

A simple step-by-step guide to host your HTML blog on GitHub Pages for free.

---

## 📁 Step 1: Prepare Your Files

Make sure your blog folder has these files:

```
your-folder/
├── index.html       ← Home page
├── blog.html        ← Full blog page
├── AI image.jpg     ← Image used in index.html
└── AI image2.jpg    ← Image used in blog.html
```

---

## 🐙 Step 2: Create a GitHub Account

- Go to [https://github.com](https://github.com)
- Sign up for a free account

---

## 📦 Step 3: Create a New Repository

- Click the **+** button → **New Repository**
- Name it: `yourusername.github.io`
- Set it to **Public**
- Click **Create Repository**

> ⚠️ Replace `yourusername` with your actual GitHub username.

---

## 💻 Step 4: Open Git Bash and Run Commands

Open **Git Bash** inside your blog folder and run these commands one by one:

```bash
git init
git add .
git commit -m "Add AI blog"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

---

## ⚙️ Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings**
3. Click **Pages** (on the left side)
4. Under **Source**, select `main` branch and `/ (root)`
5. Click **Save**

---

## 🌐 Step 6: Visit Your Blog

After a few minutes, your blog will be live at:

```
https://yourusername.github.io
```

---

## ➕ Step 7: Adding New Posts Later

1. Create a new `.html` file in your folder
2. Add a link to it in `index.html`
3. Run these commands:

```bash
git add .
git commit -m "Add new post"
git push
```

---



