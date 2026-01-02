# 🗺️ Complete Roadmap: Setting Up Your GitHub Pages Academic Website

This guide assumes you have zero experience with Git/GitHub. Follow each step exactly.

---

## 📋 Pre-Flight Checklist

Before you start, gather these materials:

- [ ] A professional headshot photo (JPG or PNG format)
- [ ] Your CV as a PDF file
- [ ] Your Google Scholar profile URL
- [ ] Your Bluesky handle (if you have one)
- [ ] Your ORCID ID (if you have one)

---

## 🚀 PHASE 1: Create the Repository (10 minutes)

### Step 1.1: Go to GitHub
1. Open your browser
2. Go to: `https://github.com`
3. Make sure you're logged in as `lord-richie`

### Step 1.2: Create New Repository
1. Click the **green "New" button** (top left area) OR click the **"+"** icon in the top-right corner → select **"New repository"**

2. You'll see a form. Fill it in EXACTLY like this:

   | Field | What to Type/Select |
   |-------|---------------------|
   | Repository name | `lord-richie.github.io` |
   | Description | `My academic portfolio website` |
   | Public / Private | ⚪ Select **Public** |
   | Add a README file | ☑️ **Check this box** |
   | Add .gitignore | Leave as "None" (we'll add our own) |
   | Choose a license | Leave as "None" (we'll add our own) |

3. Click the green **"Create repository"** button

4. ✅ **Success!** You should now see your new repository page at:
   `https://github.com/lord-richie/lord-richie.github.io`

---

## 📁 PHASE 2: Upload Website Files (15 minutes)

### Step 2.1: Download and Extract the Template
1. Download the `academic-site-template.zip` file I provided
2. Find it in your Downloads folder
3. **Extract/Unzip** it:
   - **Windows**: Right-click → "Extract All..."
   - **Mac**: Double-click the zip file
4. Open the extracted `site` folder. You should see:
   ```
   site/
   ├── index.html
   ├── cv.html
   ├── blog.html
   ├── README.md
   ├── LICENSE
   ├── .gitignore
   ├── css/
   │   └── style.css
   ├── blog/
   │   └── sample-post.html
   ├── images/
   │   └── (empty - you'll add your photo)
   └── files/
       └── (empty - you'll add your CV)
   ```

### Step 2.2: Upload Files to GitHub
1. Go to your repository: `https://github.com/lord-richie/lord-richie.github.io`

2. Click **"Add file"** button (near the top) → **"Upload files"**

3. **Drag and drop ALL files and folders** from inside the `site` folder into the upload area:
   - index.html
   - cv.html
   - blog.html
   - README.md
   - LICENSE
   - .gitignore
   - css/ (the whole folder)
   - blog/ (the whole folder)
   - images/ (the whole folder)
   - files/ (the whole folder)

4. Wait for all uploads to complete (you'll see checkmarks)

5. Scroll down to "Commit changes":
   - In the text box, type: `Initial website upload`
   - Leave "Commit directly to the main branch" selected

6. Click the green **"Commit changes"** button

7. ✅ **Success!** Your files are now on GitHub

### Step 2.3: Verify Your Files
1. Go back to your repository main page
2. You should see all your files listed:
   ```
   📁 blog/
   📁 css/
   📁 files/
   📁 images/
   📄 .gitignore
   📄 LICENSE
   📄 README.md
   📄 blog.html
   📄 cv.html
   📄 index.html
   ```

---

## 🌐 PHASE 3: Enable GitHub Pages (5 minutes)

### Step 3.1: Open Settings
1. In your repository, click the **"Settings"** tab (top right area, has a gear icon)

### Step 3.2: Navigate to Pages
1. In the left sidebar, scroll down and click **"Pages"**

### Step 3.3: Configure Pages
1. Under **"Build and deployment"**:
   
   | Setting | Select |
   |---------|--------|
   | Source | **Deploy from a branch** |
   | Branch | **main** |
   | Folder | **/ (root)** |

2. Click **"Save"**

### Step 3.4: Wait and Visit
1. A blue banner may appear saying "GitHub Pages source saved"
2. **Wait 2-3 minutes** (GitHub needs time to build your site)
3. Refresh the page
4. You should see a green box at the top saying:
   > "Your site is live at https://lord-richie.github.io"
5. Click that link!

6. ✅ **Success!** Your website is now live on the internet!

---

## 🖼️ PHASE 4: Add Your Photo (5 minutes)

### Step 4.1: Prepare Your Photo
1. Find a professional headshot photo
2. Rename it to exactly: `headshot.jpg`
   - If it's a PNG, rename to `headshot.png` and you'll need to edit index.html later
3. Ideal size: around 400×533 pixels (3:4 ratio), but any reasonable size works

### Step 4.2: Upload to Images Folder
1. In your repository, click on the **`images`** folder
2. Click **"Add file"** → **"Upload files"**
3. Drag your `headshot.jpg` into the upload area
4. Type commit message: `Add headshot photo`
5. Click **"Commit changes"**

### Step 4.3: Verify
1. Wait 1-2 minutes
2. Refresh your website: `https://lord-richie.github.io`
3. Your photo should now appear!

---

## 📄 PHASE 5: Add Your CV PDF (5 minutes)

### Step 5.1: Prepare Your CV
1. Find your CV PDF file
2. Rename it to exactly: `Richie_Li_CV.pdf`

### Step 5.2: Upload to Files Folder
1. In your repository, click on the **`files`** folder
2. Click **"Add file"** → **"Upload files"**
3. Drag your `Richie_Li_CV.pdf` into the upload area
4. Type commit message: `Add CV PDF`
5. Click **"Commit changes"**

### Step 5.3: Verify
1. Go to your website's CV page: `https://lord-richie.github.io/cv.html`
2. Click the "Download PDF" button
3. Your CV should download!

---

## ✏️ PHASE 6: Update Your Personal Links (10 minutes)

### Step 6.1: Edit index.html
1. In your repository, click on **`index.html`**
2. Click the **pencil icon** (✏️) in the top right to edit

### Step 6.2: Find and Update Social Links
1. Press `Ctrl+F` (Windows) or `Cmd+F` (Mac) to open search
2. Search for `YOUR_ID` - you'll find three places to update:

**Google Scholar** (around line 85):
```html
<!-- FIND THIS: -->
<a href="https://scholar.google.com/citations?user=YOUR_ID" ...>

<!-- CHANGE TO (example): -->
<a href="https://scholar.google.com/citations?user=abc123xyz" ...>
```

**Bluesky** (around line 90):
```html
<!-- FIND THIS: -->
<a href="https://bsky.app/profile/YOUR_HANDLE" ...>

<!-- CHANGE TO (example): -->
<a href="https://bsky.app/profile/richieli.bsky.social" ...>
```

**ORCID** (around line 95):
```html
<!-- FIND THIS: -->
<a href="https://orcid.org/YOUR_ORCID" ...>

<!-- CHANGE TO (example): -->
<a href="https://orcid.org/0000-0001-2345-6789" ...>
```

### Step 6.3: Save Changes
1. Scroll down to "Commit changes"
2. Type: `Update social media links`
3. Click **"Commit changes"**

### Step 6.4: Verify
1. Wait 1-2 minutes
2. Refresh your website
3. Click each social link to make sure it works

---

## ✅ PHASE 7: Final Checklist

Visit your website and check everything:

- [ ] Homepage loads at `https://lord-richie.github.io`
- [ ] Your photo appears (not a placeholder)
- [ ] Navigation links work (About, Research, Publications, CV, Blog, Contact)
- [ ] CV page loads at `/cv.html`
- [ ] CV PDF downloads correctly
- [ ] Blog page loads at `/blog.html`
- [ ] Sample blog post loads
- [ ] Email link works
- [ ] Google Scholar link goes to your profile
- [ ] Bluesky link goes to your profile
- [ ] ORCID link goes to your profile
- [ ] PERIL profile link works
- [ ] Site looks good on mobile (resize your browser to test)

---

## 🔄 PHASE 8: Making Future Updates

### To Edit Text Content:
1. Go to your repository
2. Click on the file you want to edit (e.g., `index.html`)
3. Click the pencil icon (✏️)
4. Make your changes
5. Scroll down, add a commit message describing your change
6. Click "Commit changes"
7. Wait 1-2 minutes for the site to update

### To Add a New Blog Post:
1. Go to the `blog` folder
2. Click "Add file" → "Create new file"
3. Name it something like `my-new-post.html`
4. Copy the content from `sample-post.html` as a template
5. Edit the content
6. Commit the file
7. Edit `blog.html` to add a link to your new post

### To Update Your CV:
1. Go to the `files` folder
2. Click on `Richie_Li_CV.pdf`
3. Click the trash icon to delete it
4. Upload your new CV with the same filename

---

## 🆘 Troubleshooting

### "404 - Page Not Found"
- Make sure `index.html` is in the ROOT of your repository (not inside a folder)
- Check Settings → Pages → make sure branch is set to `main`
- Wait 5 minutes and try again

### Photo Not Showing
- Make sure the file is named exactly `headshot.jpg` (lowercase)
- Make sure it's inside the `images` folder
- Check that the file actually uploaded (click into images folder to verify)

### Site Not Updating After Changes
- GitHub Pages can take 2-5 minutes to update
- Try hard-refreshing: `Ctrl+Shift+R` (Windows) or `Cmd+Shift+R` (Mac)
- Check the "Actions" tab in your repository to see if the build is still running

### Links Not Working
- Make sure you saved/committed your changes
- Check for typos in the URLs
- Make sure links start with `https://`

---

## 📞 Quick Reference Card

| Task | How |
|------|-----|
| View your site | Go to `https://lord-richie.github.io` |
| Edit a file | Click file → pencil icon → edit → commit |
| Upload a file | "Add file" → "Upload files" → drag & drop → commit |
| Delete a file | Click file → trash icon → commit |
| Check build status | Repository → "Actions" tab |
| Site settings | Repository → "Settings" → "Pages" |

---

## 🎉 Congratulations!

You now have a professional academic website! 

Bookmark these links:
- **Your website**: https://lord-richie.github.io
- **Your repository**: https://github.com/lord-richie/lord-richie.github.io

---

*Last updated: January 2026*
