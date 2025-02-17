# Git Operations Task

## Tasks Performed:

1. **Create a new folder and files:**
   - Created a new folder named `Assignment1`.
   - Added the following files in the folder:
     - `Code.txt`
     - `Log.txt`
     - `Output.txt`

2. **Git Operations:**
   - Staged `Code.txt` and `Output.txt`.
   - Committed the changes.
   - Pushed the changes to GitHub.

---

## Commands Used:

### 1. **Create a New Folder:**
```bash
mkdir Assignment1
cd Assignment1

2. Create Files:
touch Code.txt Log.txt Output.txt

ls  # Verify that files are created

3. Initialize Git in the Folder:
git init

4. Stage Files (Code.txt and Output.txt):
git add Code.txt Output.txt

5. Commit the Staged Files:
git commit -m "Added Code.txt and Output.txt"

6. Connect to GitHub:
git remote add origin https://github.com/Vaishnavi-Golhar/git3.git
git branch -M main  # Rename default branch to main
git remote -v  # Verify remote URL

7. Push the Files to GitHub:
git push -u origin main


Conclusion:
This task involved creating a new folder, adding files, performing basic Git operations (staging, committing, and pushing), and then pushing the changes to GitHub.
