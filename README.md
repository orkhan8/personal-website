# Personal Website

Welcome to your personal website project! Here's everything you need to know to get started.

## Project Structure

```
personal-website/
├── index.html      # Main HTML file - the structure of your website
├── styles.css      # CSS file - controls the look and feel
├── scripts.js      # JavaScript file - adds interactivity
└── README.md       # This file
```

## How to View Your Website

### Option 1: Direct File Opening (Simplest)
1. Open `index.html` in your file explorer
2. Double-click it to open in your default browser
3. Your website will load!

### Option 2: Using a Code Editor
1. Open the `personal-website` folder in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server" (if installed) or "Open in Default Browser"

### Option 3: Using Python (if installed)
```bash
cd personal-website
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser

### Option 4: Using Jekyll (recommended for homework bonus)

If your teacher gives bonus for using Jekyll, you can build and preview the site locally using Jekyll. You'll need Ruby and Bundler installed on your machine.

Windows (PowerShell) quick steps:

```powershell
cd "c:\Users\Orkhan Shahmuradli\personal-website"
# install bundler (run once)
gem install bundler
# install gems from the provided Gemfile
bundle install
# run local server
bundle exec jekyll serve --host 127.0.0.1
```

Open `http://127.0.0.1:4000` in your browser. The site uses the Jekyll layout in `_layouts/default.html` so Jekyll will render your page and you can get the bonus.

Notes:
- If you don't want to install Ruby locally you can push this repository to GitHub and enable GitHub Pages — GitHub will build the Jekyll site for you automatically (no local install required).
- Keep `styles.css` and `scripts.js` in the project root — the Jekyll layout references them with `relative_url`.

## Customizing Your Website

### Change Your Name
- Open `index.html`
- Find the text "Hi, I'm Orkhan Shahmuradli" and replace "Orkhan Shahmuradli" with your name

### Update Your Description
- In `index.html`, find "A passionate learner exploring web development..."
- Replace it with your own description

### Add Your Projects
- Find the "Projects" section in `index.html`
- Update the project titles, descriptions, and links

### Update Contact Information
- Find the contact section with Email, LinkedIn, GitHub
- Replace `mailto:your.email@example.com` with your actual email
- Replace the LinkedIn and GitHub URLs with your profiles

### Change Colors
- Open `styles.css`
- Look for color codes like `#667eea` or `#764ba2`
- These are hex color codes - visit [color-picker](https://htmlcolorcodes.com/) to choose new colors

## Key HTML Concepts

- `<section>` - Groups related content
- `<h1>`, `<h2>`, etc. - Headings (h1 is biggest, h6 is smallest)
- `<p>` - Paragraphs
- `<a>` - Links to other pages
- `<div>` - Container for grouping elements
- `<ul>` - Unordered list (bullet points)

## Key CSS Concepts

- `color:` - Text color
- `background-color:` - Background color
- `padding:` - Space inside an element
- `margin:` - Space outside an element
- `font-size:` - Text size
- `display: flex;` - Arranges items in a row or column
- `border-radius:` - Rounded corners

## Key JavaScript Concepts

The JavaScript in this project adds:
- **Smooth scrolling** - When you click a navigation link, the page smoothly scrolls
- **Scroll effects** - The navbar changes appearance as you scroll
- **Page load animations** - Sections fade in when the page loads

## Tips for Learning

1. **Small changes first** - Try changing text or colors to see immediate results
2. **Inspect in browser** - Right-click → "Inspect" to see how elements work
3. **Google is your friend** - Search for "HTML [what you want]" to learn more
4. **Take breaks** - Learning web development takes time and practice

## Next Steps

After you're comfortable with this website:
1. Add more projects as you build them
2. Create separate pages for different sections
3. Learn about forms to collect visitor messages
4. Deploy your website to make it available online (Netlify, GitHub Pages, etc.)

If you want the Jekyll bonus and prefer GitHub Pages:

1. Create a GitHub repository and push this project to it.
2. On the repo's GitHub Settings → Pages, set the source to the `main` branch (root) and save.
3. GitHub will build the Jekyll site and make it available at `https://<your-username>.github.io/<repo>` (or at `https://<your-username>.github.io` if using a username repo).

If you'd like, I can initialize git for you and help push the repository and enable Pages.

## Common Questions

**Q: How do I add images?**
A: Use `<img src="path/to/image.jpg" alt="description">` in your HTML

**Q: How do I add links to projects?**
A: Replace the `#` in `href="#"` with your project URL

**Q: How do I make the website look better?**
A: Experiment with `styles.css` - change colors, fonts, spacing, and sizes

**Q: Can I make my website live online?**
A: Yes! Use services like Netlify, GitHub Pages, or Vercel (all free)

Happy coding! 🚀
