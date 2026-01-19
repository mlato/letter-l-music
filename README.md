# Matt Latourelle Music

Minimal music website

## Setup

1. **structure:**
   ```
   your-repo/
   ├── _config.yml
   ├── _data/
   │   └── tracks.yml
   ├── _layouts/
   │   └── default.html
   ├── assets/
   │   ├── css/
   │   │   └── style.css
   │   └── music/
   │       ├── track1.mp3
   │       ├── track2.mp3
   │       └── track3.mp3
   ├── index.html
   └── README.md
   ```

2. **files:**
   - Place your MP3 files in the `assets/music/` folder
   - Update `_data/tracks.yml` with your track information

3. **content:**
   - Edit `index.html` to update the About section
   - Update social links and footer links
   - Modify `_config.yml` with your GitHub username

4. **deploy**
   - Go to your repository Settings
   - Navigate to Pages
   - Select "main" branch as source
   - Your site will be live at `https://yourusername.github.io/repo-name`

##add files

To add new tracks, edit `_data/tracks.yml`:

```yaml
- title: "Your Song Title"
  artist: "Matt Latourelle"
  file: "/assets/music/your-song.mp3"
```

##email integration

Replace the form in `index.html` with your email service provider's embed code (Mailchimp, Buttondown, ConvertKit, etc.)

##license

© Matt Latourelle. All rights reserved.
