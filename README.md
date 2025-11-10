# Template website

This template is a template that combines scss with Jekyll. This will be used for all my future websites.

## Cloning
Run:
- On Windows:
    ```
    git clone https://github.com/MrurBo/Template-Website/
    rename Template-Website/ (your-repo-name)/
    cd (your-repo-name)/
    git remote remove origin
    git remote add https://github.io/(your-name)/(your-repo-name)
    git add .
    git commit -m "Initial Commit"
    git push origin main
    ```
- On Linux:
    ```
    git clone https://github.com/MrurBo/Template-Website/
    mv Template-Website/ (your-repo-name)/
    cd (your-repo-name)/
    git remote remove origin
    git remote add https://github.io/(your-name)/(your-repo-name)
    git add .
    git commit -m "Initial Commit"
    git push origin main
    ```

## Commands:
* Test: `jekyll serve`
* Build: `jekyll build`
* Deploy: Automatically via github actions.
