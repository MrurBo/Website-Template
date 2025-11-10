---
layout: default
---

# Template website
[![MrurBo - Website-Template](https://img.shields.io/static/v1?label=MrurBo&message=Website-Template&color=blue&logo=github)](https://github.com/MrurBo/Website-Template "Go to GitHub repo")
[![stars - Website-Template](https://img.shields.io/github/stars/MrurBo/Website-Template?style=social)](https://github.com/MrurBo/Website-Template)
[![forks - Website-Template](https://img.shields.io/github/forks/MrurBo/Website-Template?style=social)](https://github.com/MrurBo/Website-Template)

[![Build and Deploy Jekyll Site](https://github.com/MrurBo/Website-Template/workflows/Build%20and%20Deploy%20Jekyll%20Site/badge.svg)](https://github.com/MrurBo/Website-Template/actions?query=workflow:"Build+and+Deploy+Jekyll+Site")
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![issues - Website-Template](https://img.shields.io/github/issues/MrurBo/Website-Template)](https://github.com/MrurBo/Website-Template/issues)

## Configuration
1. Edit `_config.yml` with your details.
2. Edit `CNAME` if you have your own domain.
3. Edit `src/index.md`, `src/js/main.js`, and `src/_sass/*` for all styles.
4. When your done, push files to github.
5. In github, after the action completes, go to your repository, `settings -> pages` and set `Source` to `Deploy from a branch`. Then under it, set Branch to `gh-pages` and the folder to `/ (root)`. Then click save.

### Screenshot of github pages configuration:
![Screenshot of github pages configuration]({{ "/assets/ss.png" | relative_url }})

## Commands:
* Test: `jekyll serve`
* Build: `jekyll build`
* Deploy: Push to github and actions will automatically upload to branch `gh-pages`

## License

Released under [MIT](/LICENSE) by [@MrurBo](https://github.com/MrurBo).