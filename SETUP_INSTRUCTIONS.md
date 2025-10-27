# Making This Repository a GitHub Template

To use this MERN scaffold as a reusable template for new projects:

## Option 1: Make it a GitHub Template (Recommended)

1. Go to your repository on GitHub: https://github.com/marcoanicosta/simple_mern_folder_start
2. Click **Settings** tab
3. Scroll down to the **"Template repository"** section
4. Check the box: **"Template repository"**
5. Click **Save**

Now when you create a new project:
- Visit your repository page
- Click the green **"Use this template"** button
- Create a new repository from this template
- Clone the new repository to your local machine

**Benefits:**
- Clean history for each new project
- No connection between projects
- Designed specifically for this use case

## Option 2: Clone Without History

If you prefer command-line approach:

```bash
# Clone the repository
git clone https://github.com/marcoanicosta/simple_mern_folder_start.git my-new-project

# Remove git history
cd my-new-project
rm -rf .git

# Initialize new repository
git init
git add .
git commit -m "Initial commit"

# Add your new project's remote
git remote add origin https://github.com/yourusername/my-new-project.git
git push -u origin main
```

## Option 3: Fork via GitHub CLI

If you have GitHub CLI installed:

```bash
gh repo fork https://github.com/marcoanicosta/simple_mern_folder_start.git --clone new-project-name
cd new-project-name
```

**Note:** Forking maintains connection to original repo, which isn't ideal for starting fresh projects.

