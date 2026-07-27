
If you've created a new repository on GitHub and want to push your local project to it for the first time, use these steps:


# 1. Open terminal in your project folder

# 2. Initialize Git (only if not already initialized)
git init

# 3. Add all files
git add .

# 4. Commit the files
git commit -m "Initial commit"

# 5. Connect your local project to the GitHub repository
git remote add origin https://github.com/<your-username>/<repository-name>.git

# 6. Rename the branch to main (if needed)
git branch -M main

# 7. Push the project to GitHub
git push -u origin main






# For future updates to the same repository use these steps only :

git add updatedFileName
git commit -m "Describe your changes"
git push origin main