# STAT 386 Tutorial Blog

A Quarto website featuring the tutorial **“From API to DataFrame: Collecting College Football Scores with Python.”**

## Preview locally

Install the Python dependencies, then start Quarto's preview server:

```bash
python3 -m pip install -r requirements.txt
quarto preview
```

## Publish with GitHub Pages

Render the site and commit the generated `docs/` directory:

```bash
quarto render
git add .
git commit -m "Publish tutorial website"
git push origin main
```

In the repository's GitHub settings, choose **Pages**, set the source to **Deploy from a branch**, and select the **main** branch and **/docs** folder. The published site will be available at:

<https://ggjas111024.github.io/jgibb-tutorial-blog/>
