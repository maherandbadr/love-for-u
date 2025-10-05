# 💖 My Heart's Apology 💖

A beautiful, interactive romantic website created with love and HTML/CSS/JavaScript. This is a personal project to express feelings through code and multimedia.

## 🌟 Features

- **Interactive Apology Section**: Heart animations and promises
- **Music Player**: Personal playlist with romantic songs
- **Video Gallery**: Special videos for your loved one
- **Photo Gallery**: Memories with fullscreen viewing
- **Love Letter Generator**: Dynamic love letters

## 🚀 Quick Start

1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd "sorry baby"
   ```

2. **Install Git LFS** (if not already installed):
   ```bash
   git lfs install
   ```

3. **Add your media files**:
   - Place your `.mp3` music files in the root directory
   - Add your `.mp4` video files
   - Include your `.jpg` images

4. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server: `python -m http.server 8000`

## 📁 File Structure

```
sorry baby/
├── index.html              # Main website file
├── *.mp3                   # Music files (tracked with Git LFS)
├── *.mp4                   # Video files (tracked with Git LFS)
├── *.jpg                   # Image files (tracked with Git LFS)
├── .gitignore              # Excludes large files from regular Git
├── .gitattributes          # Configures Git LFS tracking
└── README.md               # This file
```

## 🎵 Media Files Required

### Music Files:
- `Mitski - My Love Mine All Mine.mp3`
- `we fell in love in octobor.mp3`
- `Eyedress - Something About You.mp3`
- `cafune - Tek it.mp3`
- `Those eyes.mp3`
- `A New Kind Of Love.mp3`

### Video Files:
- `video-1.mp4`
- `video-2.mp4`
- `video-3.mp4`

### Image Files:
- `pic1.jpg`
- `pic2.jpg`
- `pic3.jpg`
- `video-calls.jpg`
- `future-plans.jpg`
- `dreams-together.jpg`

## 🔧 Troubleshooting GitHub Upload Issues

If you're getting "file too large" errors on GitHub:

### Option 1: Use Git LFS (Recommended)
```bash
# Install Git LFS
git lfs install

# Track large files
git lfs track "*.mp3"
git lfs track "*.mp4"
git lfs track "*.jpg"

# Add and commit
git add .gitattributes
git add .
git commit -m "Add romantic website with LFS"
git push
```

### Option 2: Host Media Files Externally
1. Upload media files to a cloud service (Google Drive, Dropbox, etc.)
2. Get public links
3. Update the `src` attributes in `index.html` to use the external URLs

### Option 3: Use GitHub Pages with External Hosting
1. Host media files on a CDN or cloud storage
2. Update the file paths in your HTML
3. Deploy to GitHub Pages for free hosting

## 💝 Customization

Edit `index.html` to:
- Change the name "Arina" to your loved one's name
- Update the romantic messages
- Add more songs, videos, or images
- Modify the color scheme in the CSS

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Enable GitHub Pages in repository settings
2. Set source to "Deploy from a branch"
3. Select "main" branch
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify (Free)
1. Connect your GitHub repository
2. Set build command: (leave empty)
3. Set publish directory: (root)
4. Deploy!

### Vercel (Free)
1. Import your GitHub repository
2. Framework preset: Other
3. Deploy!

## 📝 Notes

- The website is fully responsive and works on mobile devices
- All animations are CSS-based for smooth performance
- The music player requires user interaction to play (browser autoplay policy)
- Media files are handled with fallbacks if files are missing

## 💖 Made with Love

This project was created as a heartfelt apology and expression of love. Every line of code was written with care and emotion.

---

*"Distance means nothing when someone means everything."* 💕


