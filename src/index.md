---
layout: default
---

# Template website

## Configuration
1. Edit `_config.yml` with your details.
2. Edit `CNAME` if you have your own domain.
3. Edit `src/index.md`, `src/js/main.js`, and `src/_sass/*` for all styles.
4. When your done, push files to github.
5. In github, after the action completes, go to your repository, `settings -> pages` and set `Source` to `Deploy from a branch`. Then under it, set Branch to `gh-pages` and the folder to `/ (root)`. Then click save.

### Screenshot of github pages configuration:
![Screenshot of github pages configuration]({{ "/assets/ss.png" | relative-url }})

## Commands:
* Test: `jekyll serve`
* Build: `jekyll build`
* Deploy: Push to github and actions will automatically upload to branch `gh-pages`
