# Chenyi Zhang's Personal Website

This is a GitHub Pages website created with HTML and CSS, based on your Wix website.

## Website Sections

- **HOME** - About you and your background
- **Research** - Your research interests and description
- **Publications & Presentations** - Papers and talks/presentations
- **Teaching** - Teaching experience and courses
- **Services** - Professional service, committee memberships, and mentoring

## How to Customize Your Website

### 1. Update Personal Information

Edit `index.html` and replace the following:
- Email: `your.email@stanford.edu` → your actual email
- Social links: GitHub, LinkedIn, Twitter URLs
- Advisor names and links
- University/Institution details

### 2. Add Your Publications

In the "Publications & Presentations" section, replace the placeholder papers with your actual publications:
```html
<div class="paper-item">
    <h4>Your Paper Title</h4>
    <p><strong>Authors:</strong> Your names</p>
    <p><strong>Conference/Journal:</strong> Conference/Journal Name, Year</p>
    <p><a href="link-to-arxiv" target="_blank">View on arXiv</a> | <a href="link-to-paper" target="_blank">Full Paper</a></p>
</div>
```

### 3. Add Your Talks

Add your presentation details in the "Talks & Presentations" section:
```html
<div class="talk-item">
    <h4>Your Talk Title</h4>
    <p><strong>Event:</strong> Conference/Seminar Name</p>
    <p><strong>Date:</strong> Month Year</p>
    <p><strong>Location:</strong> City, Country</p>
</div>
```

### 4. Update Teaching Information

Add your teaching experience in the "Teaching" section with course names, institution, and semesters.

### 5. Update Professional Services

Update the "Services" section with:
- Committee memberships
- Conference review activities
- Workshop organization
- Mentoring roles

### 6. Change Colors

Edit `styles.css` to customize the color scheme:
- Line 85-86: Change `#667eea` and `#764ba2` for the hero gradient
- Line 129: Change `#667eea` for accent color

Current colors: Purple/Blue gradient

### 7. Add Profile Photo (Optional)

1. Create an `images/` folder in your repository
2. Upload a profile photo (e.g., `profile.jpg`)
3. Add to the HOME section in `index.html`:
```html
<img src="images/profile.jpg" alt="Chenyi Zhang" style="width: 200px; border-radius: 10px; margin: 1rem 0;">
```

### 8. Add CV (Optional)

1. Upload a `cv.pdf` file to your repository root
2. Add a link in the HOME section:
```html
<p><a href="cv.pdf" class="btn">Download CV (PDF)</a></p>
```

## Files Structure

```
chenyizhangling.github.io/
├── index.html          # Main website content
├── styles.css          # Styling and layout
├── README.md           # This file
├── cv.pdf              # Your CV (optional)
└── images/             # Profile photo (optional)
    └── profile.jpg
```

## Features

- ✅ Clean, professional academic design
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Easy to customize
- ✅ No dependencies or build process
- ✅ Fast load times
- ✅ Free hosting with GitHub Pages

## Your Website URL

**https://chenyizhangling.github.io**

The site will be live in a few minutes!

## Need Help?

- GitHub Pages Docs: https://docs.github.com/en/pages
- HTML/CSS Guide: https://www.w3schools.com/
- GitHub Documentation: https://docs.github.com/

Enjoy your new GitHub Pages website! 🚀
