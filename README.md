Faculty Course Template – Lab Environment
Overview

This repository is a standardized template used for course delivery, lab activities, and assignment submission using GitHub.

It is designed to support a fork-based workflow, where students:

Fork the repository
Complete lab work in their own copy
Submit work via pull requests

This model mirrors real-world development and collaboration practices.

Learning Objectives

By using this repository, students will:

Configure GitHub and SSH authentication
Work with a structured academic code repository
Follow a branch-based development workflow
Submit assignments using pull requests
Collaborate using industry-standard version control practices
Repository Structure
faculty-course-template/
│
├── labs/
│   ├── lab-01-template.md
│   ├── lab-02-template.md
│   └── ...
│
├── assignments/
│   └── (optional future use)
│
├── resources/
│   └── (supporting materials, guides, datasets)
│
└── README.md
Key Directories
labs/
Contains all lab templates students will complete
assignments/
Reserved for larger projects or graded submissions
resources/
Supporting documentation, reference material, or datasets
Student Workflow (Required)

All work in this course follows a fork-based submission model.

Step 1 – Fork the Repository

Click Fork on the main repository:

https://github.com/ECPI/faculty-course-template

This creates your personal copy.

Step 2 – Clone Your Fork
git clone git@github.com:<your-username>/faculty-course-template.git
cd faculty-course-template
Step 3 – Add Upstream Repository
git remote add upstream git@github.com:ECPI/faculty-course-template.git
git remote -v
Step 4 – Create a Branch
git checkout -b lastname-lab01

Use your actual last name.

Step 5 – Complete the Lab

Edit the appropriate file in:

labs/lab-01-template.md
Step 6 – Commit and Push
git add .
git commit -m "Complete Lab 01"
git push origin lastname-lab01
Step 7 – Submit a Pull Request

From your GitHub fork:

Click Compare & pull request
Ensure:
Base repo: ECPI/faculty-course-template
Base branch: main
Head repo: your fork
Compare branch: lastname-lab01

Submit the PR.

Deliverables

For each lab, students must:

Create a branch
Modify the correct lab file
Commit changes
Push to their fork
Submit a pull request

Failure to follow this workflow may result in loss of credit.

Authentication Requirements

This repository requires SSH authentication for Git operations.

Students must:

Generate an SSH key
Add it to GitHub
Verify access using:
ssh -T git@github.com
Notes for Instructors
This repository is public and read-only for students
All student work should come through pull requests
Review submissions directly in GitHub
Provide feedback inline when appropriate
Academic Integrity
Each student must use their own GitHub account
Work must be completed individually unless otherwise specified
Sharing repositories or credentials is not permitted
Summary

This repository is not just for submitting labs—it is part of the learning process.

Students are expected to demonstrate:

Proper Git usage
Structured workflow discipline
Clear and traceable submissions
