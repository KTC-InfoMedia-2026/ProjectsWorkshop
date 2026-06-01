# 📁 ProjectsWorkshop

A shared space for our group to store, share, and discover each other's personal and side projects. Browse the `projects/` folder to see what everyone is working on, or follow the steps below to add your own.

---

## 📂 Structure

```
ProjectsWorkshop/
└── projects/
    └── your-project-name/
        ├── README.md        ← required
        └── (your files)
```

Every project lives in its own folder under `projects/`. Nothing goes in the root of the repo.

---

## ➕ Adding Your Project

### 1. Clone the repo
```bash
git clone https://github.com/your-org/ProjectsWorkshop.git
cd ProjectsWorkshop
```

### 2. Create your project folder
Use a short, lowercase, hyphenated name. No spaces.
```bash
mkdir projects/your-project-name
```

### 3. Add your files
Copy or create your project files inside that folder. At minimum you need a `README.md` — the automated check will reject your PR without one.

Your project README should cover:
- What the project does
- How to run or use it
- Any dependencies

### 4. Commit and push to a new branch
```bash
git checkout -b add/your-project-name
git add projects/your-project-name/
git commit -m "Add your-project-name"
git push origin add/your-project-name
```

### 5. Open a Pull Request
Go to the repo on GitHub and open a PR from your branch into `main`. Fill out the PR template. At least one other group member needs to approve it before it merges.

---

## ✅ Requirements Checklist

Before opening a PR, make sure:

- [ ] Your project is inside `projects/your-project-name/`
- [ ] You have a `README.md` in your project folder
- [ ] You haven't modified anyone else's folder
- [ ] Your folder name is lowercase and hyphenated (no spaces)

The automated check will flag any of these issues and block the merge until they're fixed.

---

## 🚫 Rules

- Don't push directly to `main` — it's branch-protected
- Don't edit other people's project folders without their involvement
- Keep your folder self-contained — don't add dependencies that affect the whole repo

---

## 👥 Maintainers

| Name | GitHub |
|------|--------|
| (LukasPW) | @LukasPW |
