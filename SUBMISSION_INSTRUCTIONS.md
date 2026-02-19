# Submission Instructions

## Step 1: Set Up Git (if not already done)

### Configure Git (if first time):
```powershell
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## Step 2: Initialize Git Repository and Commit Code

### Initialize Git repository:
```powershell
cd "C:\Users\Ted Simwa\Desktop\tfjzl-final-cloud-app-with-database-main"
git init
```

### Add all files:
```powershell
git add .
```

### Commit the changes:
```powershell
git commit -m "Complete Django online course application with exam functionality"
```

## Step 3: Create GitHub Repository

1. Go to https://github.com and log in
2. Click the "+" icon in the top right → "New repository"
3. Repository name: `tfjzl-final-cloud-app-with-database` (or your preferred name)
4. Make sure it's set to **Public**
5. **DO NOT** initialize with README, .gitignore, or license (you already have code)
6. Click "Create repository"

## Step 4: Connect Local Repository to GitHub

### Get your repository URL from GitHub (it will look like):
`https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database.git`

### Add remote and push:
```powershell
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database.git
git push -u origin main
```

**Note:** You'll be prompted for:
- Username: Your GitHub username
- Password: Use a **Personal Access Token** (not your GitHub password)
  - To create one: GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic) → Generate new token
  - Give it `repo` permissions

## Step 5: Prepare Submission Materials

### Option 1: AI-Graded Submission (Recommended)

You need to submit **GitHub URLs** for each file. Here's what you need:

#### 1. models.py URL
- Go to: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/models.py`
- Copy the URL
- Save it in a text file

#### 2. admin.py URL
- Go to: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/admin.py`
- Copy the URL
- Save it in a text file

#### 3. Admin Site Screenshot
- Visit: `http://127.0.0.1:8000/admin/`
- Log in with admin credentials
- Take a screenshot showing:
  - "Authentication and Authorization" section
  - "OnlineCourse" section
- Save as: `03-admin-site.png` or `03-admin-site.jpeg`

#### 4. course_details_bootstrap.html URL
- Go to: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/templates/onlinecourse/course_detail_bootstrap.html`
- Copy the URL
- Save it in a text file

#### 5. views.py URL
- Go to: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/views.py`
- Copy the URL
- Save it in a text file

#### 6. urls.py URL
- Go to: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/urls.py`
- Copy the URL
- Save it in a text file

#### 7. Final Exam Screenshot
- Visit: `http://127.0.0.1:8000/onlinecourse/`
- Log in and enroll in "Learning Django"
- Take the exam (select "Yes" for the question)
- Submit the exam
- Take a screenshot showing:
  - "Congratulations" message
  - Score (should be 100/100)
  - Detailed exam results
- Save as: `07-final.png` or `07-final.jpeg`

### Option 2: Peer-Graded Submission

You need to take **screenshots** of each file. Here's what you need:

#### 1. models.py Screenshot
- Open: `onlinecourse/models.py`
- Show the Question, Choice, and Submission models
- Save as: `01-models.png` or `01-models.jpeg`

#### 2. admin.py Screenshot
- Open: `onlinecourse/admin.py`
- Show all imports and registrations
- Save as: `02-admin-file.png` or `02-admin-file.jpeg`

#### 3. Admin Site Screenshot
- Same as Option 1, Step 3
- Save as: `03-admin-site.png` or `03-admin-site.jpeg`

#### 4. course_details_bootstrap.html Screenshot
- Open: `onlinecourse/templates/onlinecourse/course_detail_bootstrap.html`
- Show the exam form code
- Save as: `04-course-details.png` or `04-course-details.jpeg`

#### 5. views.py Screenshot
- Open: `onlinecourse/views.py`
- Show the submit and show_exam_result functions
- Save as: `05-views.png` or `05-views.jpeg`

#### 6. urls.py Screenshot
- Open: `onlinecourse/urls.py`
- Show the submit and show_exam_result routes
- Save as: `06-urls.png` or `06-urls.jpeg`

#### 7. Final Exam Screenshot
- Same as Option 1, Step 7
- Save as: `07-final.png` or `07-final.jpeg`

## Step 6: Verify Before Submission

### Checklist:
- [ ] All code is committed to GitHub
- [ ] GitHub repository is Public
- [ ] All GitHub URLs open correctly (for Option 1)
- [ ] All screenshots are clear and show required content (for Option 2)
- [ ] Admin site screenshot shows both sections
- [ ] Final exam screenshot shows congratulations message and score

## Step 7: Submit

Follow your course platform's submission instructions and upload:
- **Option 1:** GitHub URLs (saved in text file) + Screenshot 03 + Screenshot 07
- **Option 2:** All 7 screenshots

## Quick Reference: GitHub URLs Format

Replace `YOUR_USERNAME` with your actual GitHub username:

- models.py: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/models.py`
- admin.py: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/admin.py`
- course_detail_bootstrap.html: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/templates/onlinecourse/course_detail_bootstrap.html`
- views.py: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/views.py`
- urls.py: `https://github.com/YOUR_USERNAME/tfjzl-final-cloud-app-with-database/blob/main/onlinecourse/urls.py`
