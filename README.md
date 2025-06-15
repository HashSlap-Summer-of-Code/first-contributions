# 🚀 First Contributions Guide

Welcome to your first open source contribution! This guide will walk you through making your first pull request to the [First Contributions](https://github.com/HashSlap-Summer-of-Code/first-contributions) repository.

## 🌟 Getting Started

### Prerequisites
- A GitHub account
- Git installed on your computer
- Basic command line knowledge

## 📋 Step-by-Step Instructions

### 1️⃣ Fork the Repository
1. Go to [First Contributions](https://github.com/HashSlap-Summer-of-Code/first-contributions)
2. Click the "Fork" button in the top-right corner
3. Wait for the fork to complete (you'll be redirected to your copy)

### 2️⃣ Clone Your Fork Locally
```bash
git clone https://github.com/YOUR-USERNAME/first-contributions.git
cd first-contributions
```

### 3️⃣ Set Up Upstream Remote
```bash
git remote add upstream https://github.com/HashSlap-Summer-of-Code/first-contributions.git
```

### 4️⃣ Create a New Branch
```bash
git checkout -b add-your-name
```

### 5️⃣ Make Your Changes
1. Open `Contributors.md` in a text editor
2. Add your name in this format at the end of the file:
```markdown
- [Your Name](https://github.com/your-username)
```
3. Save the file

### 6️⃣ Commit Your Changes
```bash
git add Contributors.md
git commit -m "Add my name to Contributors.md"
```

### 7️⃣ Push Your Changes
```bash
git push origin add-your-name
```

### 8️⃣ Create a Pull Request
1. Go to your forked repository on GitHub
2. Click "Compare & pull request"
3. Ensure:
   - Base repository: HashSlap-Summer-of-Code/first-contributions
   - Base branch: main
   - Head repository: your-username/first-contributions
   - Compare branch: add-your-name
4. Add a descriptive title and comment
5. Click "Create pull request"

## 🎉 Congratulations!
You've just made your first open source contribution! The maintainers will review your PR and merge it soon.

## 🔄 Keeping Your Fork Updated
To sync your fork with the original repository:
```bash
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```

## 🆘 Need Help?
- Check out the [First Contributions tutorial](https://github.com/firstcontributions/first-contributions)
- Join our [Discord community](https://discord.gg/hashslap)
- Read GitHub's [pull request documentation](https://docs.github.com/en/pull-requests)

Happy coding! 🚀
