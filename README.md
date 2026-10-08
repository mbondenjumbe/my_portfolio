# Felix Mbonde Njumbe - Professional Portfolio

This repository hosts a responsive, production-ready software engineering resume website deployed via GitHub Pages.

## Live Website Link
View the live project here: [https://github.io](https://github.io)

## How to Update and Republish the Site
If you want to modify the resume details or styles without disrupting the live domain, follow these simple steps:

1. **Open the Project:** Clone this repository or open the project folder in VS Code.
2. **Make Changes:** 
   - Open `index.html` to update text, project descriptions, or contact profile links.
   - Open `style.css` to adjust layouts, spacing, fonts, or colors.
3. **Save and Review Locally:** Press `Ctrl + S` to save your work. You can preview it using the VS Code Live Server extension.
4. **Publish Changes to the Live Site:** Open your built-in VS Code terminal and run the following three commands in sequence:
   ```powershell
   git add .
   git commit -m "Update resume content"
   git push origin main
   ```
*The second you press Enter on `git push`, GitHub Actions will automatically catch your changes and redeploy them to the live URL within 60 seconds.*
