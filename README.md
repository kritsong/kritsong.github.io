# Personal Profile Website

This is a personal profile website built with Jekyll.

## Deployment to GitHub Pages

To deploy this website to GitHub Pages, follow these steps:

1.  **Create a new public repository on GitHub.** The repository name should be `kritsong.github.io`.
2.  **Push the code to the repository.**
    ```bash
    git init
    git add .
    git commit -m "Initial commit"
    git branch -M main
    git remote add origin https://github.com/kritsong/kritsong.github.io.git
    git push -u origin main
    ```
3.  **Enable GitHub Pages.** In your repository's settings, go to the "Pages" section and select the `main` branch as the source.

Your website should be live at `https://kritsong.github.io` within a few minutes.

## Local Development

To run the website locally, you need to have Ruby, Jekyll, and Bundler installed.

1.  **Install dependencies:**
    ```bash
    bundle install
    ```
2.  **Start the server:**
    ```bash
    bundle exec jekyll serve
    ```
3.  **View the website:** Open your web browser and go to `http://127.0.0.1:4000`.
