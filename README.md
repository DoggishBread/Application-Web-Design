# Application Web Design

## Student information
- **Name:** Luis Ramses Calderon Martinez
- **ID:** 03099028
- **Degree:** Software engineer
- **Semester:** Sixth semester

## Subject information
- **Subject:** Application Web Design
- **Professor:** Jose Ricardo Zapata Solis

---

## About markdown
Markdown is a lightweight markup language used to format text in a simple way using special characters (like asterisks or hashes) instead of complex editing menus. It is widely used in programming README files to document projects efficiently.

---

## Markdown tagging options
The most common formatting options available in markdown:

### Text formatting
- **Bold:** Use `**text**` or `__text__` → **Bold text**
- *Italics:* Use `*text*` or `_text_` → *Italic text*
- ~~Strikethrough:~~ Use `~~text~~` → ~~Crossed out~~

### Headers
Use `#` for titles. The number of hashes indicates the hierarchy:
- `# H1` (Main title)
- `## H2` (Subtitle)
- `### H3` (Section)

### Lists
- **Unordered list:** Use `-`, `*`, or `+` followed by a space.
- **Ordered list:** Use numbers followed by a dot (`1.`, `2.`).

### Links and images
- **Link:** `[Title](URL)`
- **Image:** `![Alt text](ImageURL)`

### Code blocks
- Inline code: Use backticks `` `code` ``.
- Block code: Use triple backticks (` ``` `) to create a box like this one.

---

## Git commands reference
Below is a list of essential Git commands used to manage this repository.

### 1. Check Status
Check the state of the working directory and the staging area (see which files have changed).
```bash
git status

---

### 2. Add files (Staging)

Prepare files to be committed before saving changes.

- Add a specific file:
git add filename.txt

- Add all changed files globally:
git add .

---

### 3. Commit changes

Save the staged changes with a descriptive message.
git commit -m "Add markdown and git commands documentation"

---

### 4. Upload changes to remote repository

Send local commits to the remote repository (GitHub).
git push origin main

---

### 5. Branch management

Create, view, switch, and delete branches.

- Create a new branch:
git branch new-branch

- Switch to a branch:
git checkout new-branch

- List all branches:
git branch

- Delete a branch:
git branch -d new-branch

---

### 6. Roll back to a specific commit

Return the repository to a previous commit.

- View commit history:
git log

- Reset to a specific commit (hard reset):
git reset --hard commit_hash