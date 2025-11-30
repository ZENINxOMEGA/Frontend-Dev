<p align="center">
  <img src="https://raw.githubusercontent.com/ZENINxOMEGA/Frontend-Dev/main/Banner%20Image.png" width="100%">
</p>

<h1 align="center">🚀 Frontend-Dev Repository</h1>
<p align="center">A structured, topic-wise frontend learning repository where each topic lives in its own branch.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frontend-Development-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/HTML-CSS-JS-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/GLA-University-red?style=for-the-badge">
</p>

---

## 📦 Repository Structure (Branch ↔ Folder Mapping)

| Branch Name | Folder Name | Description |
|------------|-------------|-------------|
| javascript | Javascript | JavaScript basics, DOM, events |
| responsive-css | ResponsiveCss | Responsive design, media queries |
| intro-to-web-dev | IntroToWebDev | Basics of web development |
| html-iframes | HTMLIframes | Working with iFrames |
| html-block-inline-elements | HTMLBlock&InlineElement | Block vs inline elements |
| html | HTML | HTML basic concepts |
| flex | CSSFlexbox | Flexbox layouts |
| css-model | CSSModel | CSS box model |
| css-classes | CSSClasses | CSS selectors and classes |
| css | CSS | Pure CSS topics |
| bootstrap | Bootstrap | Bootstrap utilities & components |

---

## 🛠 Clone the Repository
```
git clone https://github.com/ZENINxOMEGA/Frontend-Dev.git
cd Frontend-Dev
```

---

## 🔄 Fetch All Branches
```
git fetch --all
```

---

## 🔀 Switch to Any Branch

### If branch exists on GitHub:
```
git checkout --track origin/<branch-name>
```

### If already fetched:
```
git checkout <branch-name>
```

### If branch does NOT exist:
```
git checkout -b <branch-name>
```

---

## 📤 Upload Topic Files to Its Branch

1. Switch to the correct branch  
2. Copy your topic folder files into the repo  
3. Push using:

```
git add .
git commit -m "Added <topic> files"
git push -u origin <branch-name>
```

**Example**
```
git checkout javascript
git add .
git commit -m "Added JavaScript files"
git push -u origin javascript
```

---

## ▶️ Run Any Project

Open:
```
index.html
```

Or use VS Code →  
Right-click → **Open with Live Server**

---

## ⚠️ Common Git Errors & Fixes

### ❗ Error:
`pathspec '<branch>' did not match any file(s) known to git`

✔ Fix:
```
git fetch --all
git checkout --track origin/<branch-name>
```

### ❗ Branch exists remotely but not locally
```
git fetch --all
git branch -r
git checkout --track origin/<branch-name>
```

---

## 🧩 Best Practices

✔ One topic = one branch  
✔ Keep folder name and branch name same  
✔ Commit with clean messages  
✔ Keep repo organized & beginner-friendly  

---

## 👑 Maintainer

**ZENINxOMEGA**  
CSE Student • Frontend Developer • Esports Enthusiast  

<p align="center">❤️ Happy Learning & Coding</p>
