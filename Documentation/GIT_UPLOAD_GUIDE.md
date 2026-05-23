# 🚀 How to Upload This Project to GitHub

## Step 1 — Install Git
Download from: https://git-scm.com/downloads
Verify: Open CMD → type `git --version`

## Step 2 — Create GitHub Account
Go to: https://github.com → Sign Up (free)

## Step 3 — Create New Repository on GitHub
1. Click the **+** icon (top right) → **New repository**
2. Repository name: `UiPath-Invoice-Automation`
3. Description: `Automated Invoice Processing Bot using UiPath REFramework + Document Understanding`
4. Set to **Public** ✅
5. Do NOT check "Initialize with README" (we already have one)
6. Click **Create repository**
7. Copy the repository URL shown (e.g. `https://github.com/YourUsername/UiPath-Invoice-Automation.git`)

## Step 4 — Open Command Prompt / Terminal
Navigate to your project folder:
```
cd C:\Users\YourName\Documents\UiPath-Invoice-Automation
```

## Step 5 — Initialize Git & Upload
Run these commands ONE BY ONE:

```bash
# Initialize git in your project folder
git init

# Add all project files
git add .

# Create your first commit
git commit -m "Initial commit: UiPath Invoice Automation Bot v1.0"

# Connect to your GitHub repository (paste your URL here)
git remote add origin https://github.com/YourUsername/UiPath-Invoice-Automation.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 6 — Verify Upload
Go to: `https://github.com/YourUsername/UiPath-Invoice-Automation`
You should see all your files and the README displayed beautifully!

## Step 7 — Add Topics to Your Repo
On GitHub → Your repo → Click the ⚙️ next to "About"
Add topics: `uipath` `rpa` `automation` `reframework` `document-understanding` `invoice-automation`
This helps recruiters find your project!

## Step 8 — Add to LinkedIn Featured Section
Copy your GitHub repo URL and paste it in:
LinkedIn → Your Profile → Featured → Add Link
