# Faculty Course Template – Lab Environment

## Overview

This repository is a standardized template used for course delivery, lab activities, and assignment submission using GitHub.

It is designed to support a fork-based workflow, where students:

- Fork the repository
- Complete lab work in their own copy
- Submit work via pull requests

This model mirrors real-world development and collaboration practices.

---

## Learning Objectives

By using this repository, students will:

- Configure GitHub and SSH authentication  
- Work with a structured academic code repository  
- Follow a branch-based development workflow  
- Submit assignments using pull requests  
- Collaborate using industry-standard version control practices  

---

## Repository Structure

## Repository Structure

```
faculty-course-template/
├── labs/
│   ├── lab-01-template.md
│   ├── lab-02-template.md
│   └── ...
├── assignments/
│   └── (optional future use)
├── resources/
│   └── (supporting materials, guides, datasets)
└── README.md
```

### Key Directories

- labs/  
  Contains all lab templates students will complete

- assignments/  
  Reserved for larger projects or graded submissions

- resources/  
  Supporting documentation, reference material, or datasets

---

## Student Workflow (Required)

All work in this course follows a fork-based submission model.

### Step 1 – Fork the Repository

Go to:
https://github.com/ECPI/faculty-course-template

Click "Fork" to create your own copy.

---

### Step 2 – Clone Your Fork

git clone git@github.com:<your-username>/faculty-course-template.git  
cd faculty-course-template

---

### Step 3 – Add Upstream Repository

git remote add upstream git@github.com:ECPI/faculty-course-template.git  
git remote -v

---

### Step 4 – Create a Branch

git checkout -b lastname-lab01

---

### Step 5 – Complete the Lab

Edit the file:

labs/lab-01-template.md

---

### Step 6 – Commit and Push

git add .  
git commit -m "Complete Lab 01"  
git push origin lastname-lab01

---

### Step 7 – Submit a Pull Request

Go to your repository on GitHub and click:

"Compare & pull request"

Make sure:

- Base repository: ECPI/faculty-course-template  
- Base branch: main  
- Head repository: your fork  
- Compare branch: lastname-lab01  

Then submit the pull request.

---

## Deliverables

For each lab, students must:

- Create a branch  
- Modify the correct lab file  
- Commit changes  
- Push to their fork  
- Submit a pull request  

---

## Authentication Requirements

This repository requires SSH authentication.

Verify your setup using:

ssh -T git@github.com

---

## Notes for Instructors

- This repository is public and read-only for students  
- All submissions should come through pull requests  
- Review work directly in GitHub  

---

## Academic Integrity

- Each student must use their own GitHub account  
- Work must be completed individually unless instructed otherwise  
- Sharing accounts or submissions is not permitted  

---

## Summary

This repository is part of the learning process.

Students are expected to demonstrate:

- Proper Git usage  
- Structured workflow discipline  
- Clear and traceable submissions  

Lab 01 Complete

Lab 01 Complete
