# Template website
[![MrurBo - Website-Template](https://img.shields.io/static/v1?label=MrurBo&message=Website-Template&color=blue&logo=github)](https://github.com/MrurBo/Website-Template "Go to GitHub repo")
[![stars - Website-Template](https://img.shields.io/github/stars/MrurBo/Website-Template?style=social)](https://github.com/MrurBo/Website-Template)
[![forks - Website-Template](https://img.shields.io/github/forks/MrurBo/Website-Template?style=social)](https://github.com/MrurBo/Website-Template)

[![Build and Deploy Jekyll Site](https://github.com/MrurBo/Website-Template/workflows/Build%20and%20Deploy%20Jekyll%20Site/badge.svg)](https://github.com/MrurBo/Website-Template/actions?query=workflow:"Build+and+Deploy+Jekyll+Site")
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![issues - Website-Template](https://img.shields.io/github/issues/MrurBo/Website-Template)](https://github.com/MrurBo/Website-Template/issues)

This is a Jekyll Template website that combines SCSS + Jekyll.

<div align="center">

[![View site - GH Pages](https://img.shields.io/badge/View_site-GH_Pages-2ea44f?style=for-the-badge)](https://mrurbo.github.io/Website-Template/)

</div>

## Cloning
Run:
- On Windows:
    ```bash
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
    ```bash
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

## License

Released under [MIT](/LICENSE) by [@MrurBo](https://github.com/MrurBo).