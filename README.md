# Hexo GitHub Pages Site

This is a Hexo site prepared for deployment with GitHub Pages and GitHub Actions.

## Local commands

```sh
npm install
npm run server
npm run build
```

## Deploy to GitHub Pages

1. Create a GitHub repository.
   - For a personal site, name it `YOUR_GITHUB_USERNAME.github.io`.
   - For a project site, any repository name works, for example `blog`.
2. Edit `_config.yml`.
   - Personal site: set `url` to `https://YOUR_GITHUB_USERNAME.github.io` and keep `root: /`.
   - Project site: set `url` to `https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPOSITORY_NAME` and set `root: /YOUR_REPOSITORY_NAME/`.
3. Push this project to the repository's `main` branch.
4. In GitHub, open repository `Settings` > `Pages`.
5. Set `Build and deployment` > `Source` to `GitHub Actions`.
6. Wait for the `Pages` workflow to finish, then open the URL shown in the workflow deployment summary.

The generated `public/` folder is intentionally ignored. GitHub Actions builds it during deployment.
