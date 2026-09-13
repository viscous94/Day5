# Day 5 Assignment: Technical Writing

---

# A) User Manual Procedure

## SETTING UP A GITHUB REPOSITORY AND A PYTHON VIRTUAL ENVIRONMENT: A STEP-BY-STEP GUIDE

This guide walks you through two related tasks:

1. **Part A** — Creating a GitHub repository from scratch and making your first commit.
2. **Part B** — Creating and activating a Python virtual environment and installing a package inside it.

Each step in this guide does exactly **one thing** and states the **expected result** so you can confirm you are on track before moving to the next step.

---

## PREREQUISITES

Before you begin, ensure you have all of the following. Do not start the numbered steps until you have every item listed below:

* **A computer** (Windows, macOS, or Linux) with administrator privileges to install software.
* **Active Internet connection.**
* **A terminal / command-line application** opened and accessible:
  * **Windows:** *Command Prompt*, *PowerShell*, or *Windows Terminal*
  * **macOS:** *Terminal* (found in Applications → Utilities)
  * **Linux:** Your distribution's native terminal application
* **A free GitHub account.** If you do not have one, create it at [https://github.com/join](https://github.com/join) before starting Part A.
* **Git installed on your computer.** Verify by typing `git --version` in your terminal. If installed, it returns a version number (e.g., `git version 2.43.0`). If not, download and install it from [https://git-scm.com/downloads](https://git-scm.com/downloads).
* **Python 3 installed on your computer.** Verify by typing `python3 --version` (or `python --version` on Windows). If installed, it returns a version number (e.g., `Python 3.11.6`). If not, download it from [https://www.python.org/downloads/](https://www.python.org/downloads/)—**on Windows, ensure the box "Add Python to PATH" is checked during installation.**
* **A plain text editor or code editor** (e.g., VS Code, Notepad++, or Notepad/TextEdit).
* **A target project directory location** decided in advance (e.g., `Documents/projects`).

---

## Part A: Creating a GitHub Repository and Making Your First Commit

**Step 1. Create a new repository on GitHub**
Go to [https://github.com](https://github.com/), log in, click the **"+"** icon in the top-right corner, and select **"New repository."**
* **Expected result:** You are taken to a page titled "Create a new repository."

**Step 2. Name your repository**
In the **"Repository name"** field, type a short name with no spaces (e.g., `my-first-repo`).
* **Expected result:** The name appears in the field, and GitHub displays a green checkmark indicating availability.

**Step 3. Set the repository visibility**
Select **"Public"** (visible to anyone) by clicking its radio button.
* **Expected result:** The "Public" option radio button is selected with a filled circle.

**Step 4. Initialize the repository with a README**
Tick the checkbox labeled **"Add a README file."**
* **Expected result:** The checkbox shows a checkmark.

**Step 5. Create the repository**
Click the green **"Create repository"** button at the bottom of the page.
* **Expected result:** You are redirected to your new repository's main page showing a file list with `README.md`.

**Interface Screenshot Description 1:**
> **Visual Reference:** A annotated interface diagram of the main GitHub repository page immediately following repository creation.
> * **What it shows:** The top bar displays `username/my-first-repo`, the branch dropdown shows `main`, and the main workspace list displays `README.md`. A bold callout highlights the bright green **"Code"** dropdown button located near the upper-right section of the file display.

**Step 6. Copy the repository's HTTPS URL**
Click the green **"Code"** button, ensure the **"HTTPS"** tab is selected, and click the copy icon next to the URL shown.
* **Expected result:** The repository URL (e.g., `https://github.com/your-username/my-first-repo.git`) is copied to your clipboard.

**Step 7. Open your terminal**
Launch the terminal application identified in the Prerequisites section.
* **Expected result:** A terminal window opens displaying a command prompt prompt line (e.g., `C:\Users\YourName>` or `yourname@computer ~ %`).

**Step 8. Navigate to your project directory**
Type `cd` followed by a space and the path to your target project folder, then press Enter:
```bash
cd Documents/projects