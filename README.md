# Notes of Benedek Toth

Super simple static blog-style site.

## Structure

- `index.html`: homepage + post list
- `style.css`: minimal styling + automatic light/dark theme support
- `posts/*.html`: individual notes with visible creation dates
- `.nojekyll`: ensures GitHub Pages serves raw static files

## Publish on GitHub Pages

1. Create a GitHub repository and push this folder.
2. In GitHub, open `Settings -> Pages`.
3. Under `Build and deployment`, set `Source` to `Deploy from a branch`.
4. Choose `main` branch and `/ (root)` folder.
5. Save.

Your site will be live at `https://<username>.github.io/<repository>/`.
