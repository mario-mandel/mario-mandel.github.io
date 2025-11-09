# Dev Learning Hub 📚

A personal learning hub for documenting technical tutorials, projects, and learning journeys. Built with simple HTML/CSS for easy maintenance and fast loading.

## 🌟 Live Site

Visit the site at: `https://mario-mandel.github.io/dev-learning-hub/`

(Replace with your actual GitHub Pages URL after deployment)

## 📝 Current Content

- **Docker Mastery - Week 1**: Complete 7-day learning plan from zero to containerized applications

## 🚀 Quick Start (Local Development)

1. Clone this repository
2. Open `index.html` in your browser
3. That's it! No build step needed.

## 📦 Deploying to GitHub Pages

### Option 1: GitHub Web Interface (Easiest)

1. **Create a new repository on GitHub**
   - Go to https://github.com/new
   - Name it `dev-learning-hub` (or whatever you prefer)
   - Make it public
   - Don't initialize with README (we already have one)

2. **Upload files**
   - Click "uploading an existing file"
   - Drag and drop all files from this folder
   - Commit the changes

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll down to "Pages" section (left sidebar)
   - Under "Source", select "Deploy from a branch"
   - Under "Branch", select `main` and `/ (root)`
   - Click Save

4. **Wait a few minutes**
   - Your site will be live at `https://yourusername.github.io/dev-learning-hub/`

### Option 2: Command Line (If you have Git installed)

```bash
# Navigate to the site directory
cd path/to/site

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Docker tutorial site"

# Add your GitHub repository as remote
# (Create the repo on GitHub first)
git remote add origin https://github.com/yourusername/dev-learning-hub.git

# Push to GitHub
git branch -M main
git push -u origin main

# Enable GitHub Pages (do this in GitHub Settings as described above)
```

## 📁 Project Structure

```
dev-learning-hub/
├── index.html           # Homepage with all tutorials
├── docker-week1.html    # Docker Week 1 tutorial
├── README.md           # This file
└── (future tutorials)
```

## ✨ Adding New Content

### Adding a New Tutorial

1. **Create a new HTML file** (e.g., `kubernetes-basics.html`)
   - Copy the structure from `docker-week1.html`
   - Update the content
   - Keep the same styling for consistency

2. **Update `index.html`**
   - Add a new card in the `posts-grid` section:

```html
<a href="your-tutorial.html" class="post-card">
    <span class="tag">Technology Name</span>
    <h3>Tutorial Title</h3>
    <p>Brief description of what this tutorial covers.</p>
    <div class="meta">Duration • Difficulty Level</div>
    <span class="read-more">Read Tutorial →</span>
</a>
```

3. **Commit and push** to update your live site

```bash
git add .
git commit -m "Add new tutorial: [Tutorial Name]"
git push
```

GitHub Pages will automatically rebuild (takes 1-2 minutes).

## 🎨 Customization

### Change Colors

Edit the CSS in both HTML files. Main colors are:
- Primary: `#667eea` (purple-blue gradient start)
- Secondary: `#764ba2` (purple gradient end)

### Update Personal Info

In `index.html`, update:
- Header title and tagline
- Footer links (GitHub, email)
- "About" section content

### Add Your Own Styling

All styles are in `<style>` tags in the HTML files. Feel free to customize!

## 🔧 Technical Details

- **No build process**: Pure HTML/CSS, no JavaScript frameworks
- **No dependencies**: Works offline, loads instantly
- **Mobile responsive**: Looks great on all devices
- **SEO friendly**: Semantic HTML, proper meta tags
- **Accessible**: Good contrast, semantic structure

## 📈 Future Additions

Ideas for expanding your learning hub:

- [ ] Add search functionality
- [ ] Create a blog section for shorter posts
- [ ] Add project showcases
- [ ] Include code syntax highlighting library
- [ ] Add comments system (e.g., utterances.es)
- [ ] Create tags/categories for filtering
- [ ] Add RSS feed
- [ ] Dark mode toggle

## 📄 License

Feel free to use this template for your own learning hub! No attribution required.

## 🤝 Contributing

If you spot any errors in the tutorials or have suggestions:
1. Open an issue on GitHub
2. Or submit a pull request

## 💡 Tips for Learning in Public

- Document as you learn, not after
- Don't wait for perfection - publish and iterate
- Share your mistakes and how you fixed them
- Engage with others learning the same things
- Update content as you learn more

---

Built with ❤️ for learning in public

**Questions?** Open an issue or reach out!
