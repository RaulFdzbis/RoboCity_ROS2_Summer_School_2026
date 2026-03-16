# RoboCity ROS 2 Summer School 2026

This repository contains the event static website (HTML pages, CSS, and images).

## Requirements

- Git
- Python 3

## Clone the repository

1. On GitHub, open the repository and copy the URL from the **Code** button.
2. Clone it on your machine:

```bash
git clone <REPOSITORY_URL>
cd RoboCity_ROS2_Summer_School_2026
```

Repository URL examples (use whichever applies to you):

```text
https://github.com/<ORG_OR_USER>/RoboCity_ROS2_Summer_School_2026.git
git@github.com:<ORG_OR_USER>/RoboCity_ROS2_Summer_School_2026.git
```

## Run locally

Since this is a static website, you can serve it with Python’s built-in web server from the project root folder:

```bash
python3 -m http.server 8000
```

Then open in your browser:

- http://localhost:8000/

To open the homepage directly:

- http://localhost:8000/index.html

To stop the server, press `Ctrl+C` in the terminal.

## Contributing (via Pull Request)

If you’re not familiar with GitHub, the typical contribution flow is:

### 1) Fork the repository

- On GitHub, go to the original repository and click **Fork** (top-right).
- This creates a copy of the repository under your account.

### 2) Clone your fork

On your fork page (in your account), copy the URL from **Code** and clone it:

```bash
git clone <YOUR_FORK_URL>
cd RoboCity_ROS2_Summer_School_2026
```

### 3) Create a branch for your changes

It’s important not to work directly on the main branch. Create a new branch with a descriptive name:

```bash
git checkout -b my-change
```

### 4) Make your changes and test locally

- Edit the necessary files.
- If you changed the website, you can test it with:

```bash
python3 -m http.server 8000
```

### 5) Commit your changes

```bash
git status
git add -A
git commit -m "Briefly describe the change"
```

### 6) Push your branch to your fork

```bash
git push -u origin my-change
```

### 7) Open the Pull Request

- Go back to GitHub (your fork).
- GitHub often shows a prompt/button to open a Pull Request from the newly pushed branch.
- If it doesn’t show up, go to the **Pull requests** tab and click **New pull request**.
- Make sure that:
	- **base repository** points to the original repository,
	- **head repository** points to your fork,
	- and select your branch (`my-change`).
- Describe what you changed and why.

That’s it! The team will review your Pull Request and, if everything looks good, merge it.