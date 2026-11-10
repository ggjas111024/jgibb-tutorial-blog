# STAT 386 Statistics Blog

A Quarto website featuring a college-football quarterback analysis and an API tutorial for STAT 386 students.

## Preview locally

Install the Python dependencies if you want to execute the tutorial code. To preview the existing content without making live API requests, run:

```bash
python3 -m pip install -r requirements.txt
quarto preview --no-execute
```

## Publish with GitHub Pages

Render the site and commit the generated `docs/` directory:

```bash
quarto render --no-execute
git add .
git commit -m "Publish statistics blog"
git push origin main
```

In the repository's GitHub settings, choose **Pages**, set the source to **Deploy from a branch**, and select the **main** branch and **/docs** folder. The published site will be available at:

<https://ggjas111024.github.io/jgibb-tutorial-blog/>
