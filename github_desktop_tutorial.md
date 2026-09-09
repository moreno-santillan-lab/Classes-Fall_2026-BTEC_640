# Bash cheat sheet using Github desktop



**Goal:** build a personal cheat sheet of everything you learn this semester. Even though this file will count for participation points, the main goal is you start creating your own cheat sheet. This is made by you for you!

---

## 1. Download GitHub Desktop

GitHub Desktop is the GUI app that manage your GitHub repository from your computer.

- Go to `desktop.github.com` and download the version for your operating system.
- Install it like any other application, then open it.

## 2. Connect your GitHub account

The first time you open GitHub Desktop, it needs to know who you are so it can push your work to *your* account.

- Go to `File → Options` (Windows) or `GitHub Desktop → Settings` (Mac) → `Accounts`.
- Click **Sign in to GitHub.com** and follow the prompts, this opens your browser to log in and authorize the app.
- Sign in with the GitHub account that you created in the first assignment.

## 3. Open your BTEC repository

A **repository** ("repo") is just a project folder that GitHub keeps track of. **Cloning** means downloading your own working copy of it onto your computer.

- In GitHub Desktop, go to `File → Clone repository`.
- Find your **BTEC** repository in the list (or paste its URL under the "URL" tab), choose where to save it on your computer, and click **Clone**.
  

## 4. Create your directory with Markdown

**Markdown** is a very simple way of formatting plain text using a few symbols (this tutorial is made with Markdown).
For example: a `#` makes a heading, three backticks wrap a block of code, a `-` makes a list. Any plain text editor can write it. Almost every README file on GitHub is a Markdown file. The extension for these type of files is `.md` (just like .pdf .doc .xls .ppt).

>:bulb: Everything in programming and coding language has a learning curve, just dive in! Explore all the tools and formats that you can make with Markdown:
>
>- This is a cool [hands-on  Markdown tutorial](https://www.markdowntutorial.com/) that I encourage you to try. 
>- This is the Markdown guide website.
>- There are hundreds of cheat sheets and cool tutorials in the web, just go for it and play with it.

Inside the **BTEC** repository folder, create one new file named exactly `bash_dictionary.md`. This is the file you will be working during all the semester.

> **Important:** GitHub Desktop doesn't have a text editor built in, it only tracks and uploads changes. To actually *write* the file, we will use **VS Code** (the editor you already installed for the 1st assignment).

## 5. Edit the file in VS Code

- In GitHub Desktop, with the **BTEC** repository selected, go to `Repository → Open in Visual Studio Code` (there's usually a matching button in the toolbar too). This opens the whole repo folder in VS Code.
- In VS Code's file explorer on the left, right-click the repository's folder name and choose **New File**.
- Name it exactly `bash_dictionary.md`, the `.md` extension is what tells VS Code and GitHub this is Markdown.

## 6. Add the title and subtitle

At the very top of the file, type:

```
##### Bash dictionary
### Sept 9
```

In Markdown, `#` makes a heading, the more `#` symbols, the smaller the heading. `#####` (five) gives the title, `###` (three) gives a slightly bigger subtitle for the date. 
Try it and play with it! This is your cheat sheet use your own creativity to organize it.

## 7. Document code with triple backticks

To show a block of terminal commands (as opposed to regular notes), start a new line with three backticks ` ``` `, write the commands, then close it with three backticks again on their own line. Everything between them displays as code.

Just like we saw in class, every command gets a short `#` comment explaining what it does:

```
# To change directories:
cd /Documents/BTEC    

# To list files and directories:

ls   

#To create a new directory called results:

mkdir results            
```

**Why bother:** this is the same documentation habit we saw in class, a short comment on *why* a command is there, will make anyone (including future you) able to follow the reasoning.

## 8. Commit before leaving class

**Committing** saves a your changes with a short message describing what you did; **pushing** sends that new file up to GitHub.com. This is how it counts for the day:

1. Save the file in VS Code (`Cmd/Ctrl + S`).
2. Switch to GitHub Desktop: `bash_dictionary.md` will be listed under **Changes**.
3. In the box at the bottom left, write a one-line summary, with each class date. *"Add bash dictionary: Sept 9"*.
4. Click **Commit to main**, then **Push origin** at the top.

> **Participation:** students need to commit and push before the end of class to get their participation point for the day.

---

## How to update your file in the future?

1. Open GitHub Desktop → select **BTEC** → `Repository → Open in Visual Studio Code`.
2. In VS Code, open `bash_dictionary.md` and add today's date heading + notes.
3. Save the file.
4. Back in GitHub Desktop: write a commit message → **Commit to main** → **Push origin**.

---
