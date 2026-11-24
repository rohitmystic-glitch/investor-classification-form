# Investor Classification Form

This is the static HTML, CSS, and JavaScript source used for the investor classification form. It runs in a browser without a build step or backend.

## Open it on your computer

1. Extract this folder to a location you can find, such as `Documents\Investor Classification Form`.
2. In VS Code, choose **File → Open Folder** and select the extracted folder.
3. To preview the form, open `index.html` in a browser. You can also use the VS Code **Live Server** extension if you already have it installed.
4. Edit `index.html`, `style.css`, or `app.js` to change the form.

## Publish a shareable link with GitHub Pages

You need a GitHub account and a new GitHub repository. On GitHub Free, use a public repository for a publicly accessible Pages site. The source files will also be visible to the public.

1. Create a repository on GitHub. Do not add a README or other files during repository creation.
2. In VS Code, open the extracted folder and open **Terminal → New Terminal**.
3. Run the following commands, replacing `YOUR-USERNAME` and `YOUR-REPOSITORY` with your GitHub details:

   ```powershell
   git init
   git add .
   git commit -m "Add investor classification form"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

4. On GitHub, open the repository and choose **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then select **Save**.
7. Wait for GitHub Pages to finish publishing. Your site will appear at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

When you change the form later, save the files, then run:

```powershell
git add .
git commit -m "Update investor form"
git push
```

## Prototype limits

This form is front-end only. It does not save form responses, send them to a server, or upload selected documents. The file picker is for demonstration. Do not enter real investor, identity, banking, or document data.
