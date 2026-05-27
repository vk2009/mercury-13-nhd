# Mercury 13 — NHD Website

**National History Day | Senior Individual Website**  
**Theme:** Rights & Responsibilities in History

---

## Project Structure

```
mercury13/
├── index.html                  # Tab 1: Home (thesis, metadata, navigation)
├── biological-myth.html        # Tab 2: The Biological Myth (1960 Life magazine)
├── policy-lock.html            # Tab 3: The Policy Lock (1962 Congressional Hearing)
├── technological-solution.html # Tab 4: Technological Solution (1983 Space Shuttle)
├── documentation.html          # Tab 5: Process Paper & Annotated Bibliography
├── css/
│   └── style.css
├── js/
│   └── main.js
├── netlify.toml
└── README.md
```

---

## Deploying to Netlify via GitHub

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it `mercury13-nhd` (or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2: Upload Your Files
Option A — GitHub web interface:
1. Click **uploading an existing file** on the repository page
2. Drag all files and folders into the upload area (maintain the folder structure)
3. Click **Commit changes**

Option B — Git command line:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/mercury13-nhd.git
git push -u origin main
```

### Step 3: Deploy on Netlify
1. Go to [app.netlify.com](https://app.netlify.com) and sign in (free account)
2. Click **Add new site** → **Import an existing project**
3. Choose **GitHub** and authorize Netlify
4. Select your `mercury13-nhd` repository
5. Build settings:
   - **Build command:** *(leave blank)*
   - **Publish directory:** `.`
6. Click **Deploy site**

Netlify will give you a URL like `https://mercury13-nhd.netlify.app`

### Step 4: Custom Domain (Optional)
In Netlify: Site settings → Domain management → Add custom domain

---

## Before Submitting to NHD

### Update the Homepage Metadata
In `index.html`, replace the placeholder values:
- `[Your Name Here]` → your actual name
- `[Update Before Submission]` for word counts → count your student-composed words and update

### Complete the Documentation Page
In `documentation.html`:
- Write your **Process Paper** (max 500 words) in the four labeled sections
- Complete all **Annotation** fields for each source
- Add any additional primary and secondary sources

### Word Count Reminder
Student-composed words (max 1,200):
- Direct quotes from sources do NOT count
- Your analytical commentary, thesis, historical context, and captions DO count
- Use a word processor to track your count as you write

### Media Rules
- Total audio/video embedded on site: max 3 minutes combined
- No external links that take judges away from your site (except PDF downloads)

---

## Primary Sources Used

| Source | URL |
|--------|-----|
| *Life* Magazine, Aug 29, 1960 | https://www.life.com/history/jerrie-cobb-had-the-right-stuff-but-at-the-wrong-time/ |
| 1962 Congressional Hearing Transcript | https://hdl.handle.net/2027/uc1.a0000094904 |
| Wally Funk NASA Oral History, 1999 | https://www.nasa.gov/wp-content/uploads/2025/08/funkw-7-18-99.pdf |
