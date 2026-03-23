# 🎢 Themed Entertainment at UC San Diego Website 🎢

**Live Site:** [https://tea-at-ucsd.github.io/teaatucsdsite/](https://tea-at-ucsd.github.io/teaatucsdsite/)

## Overview

This is the official website for the Themed Entertainment Association (TEA) at UC San Diego. The site showcases our club's projects, board members, alumni, and provides information about how to get involved.

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Styling:** Tailwind CSS + Custom CSS
- **Animations:** Animate.css
- **Icons:** Font Awesome
- **Deployment:** GitHub Pages (automatic from `main` branch)

## Project Structure

```
teaatucsdsite/
├── assets/                    # Static assets and data
│   ├── board_photos/          # Board member photos
│   │   ├── Becca.jpg
│   │   ├── Ben.jpg
│   │   ├── Cristin.jpg
│   │   ├── Elisa.jpg
│   │   ├── Kaitlin_B.jpg
│   │   ├── Naomika.jpg
│   │   ├── Ryan.jpg
│   │   └── Sophia.jpg
│   ├── favicon.png            # Site favicon
│   ├── GroupAll.jpg           # Group photo
│   ├── TEA_logo.png           # Club logo
│   ├── project_meeting.jpg    # Project work photo
│   ├── boardmembers.json      # Board member data
│   └── alumni.json            # Alumni data
├── project1/                  # Project 1: Audio Animatronic
│   ├── Taro.png               # Project thumbnail
│   └── index.html             # Project page
├── project2/                  # Project 2: Haunted Maze (this one does not have a page just links to the Haunted Maze IG)
│   └── HauntedMaze.png        # Project thumbnail    
├── index.html                 # Main homepage
├── script.js                  # JavaScript functionality
├── style.css                  # Custom CSS styles
└── README.md                  # This file
```

## Key Features

- **Responsive Design:** Mobile-first approach with Tailwind CSS
- **Dynamic Content:** Board members and alumni loaded from JSON files
- **Smooth Animations:** Scroll-triggered animations and hover effects
- **Navigation:** Sticky navbar with smooth scrolling
- **Social Integration:** Links to LinkedIn, Instagram, Discord, and YouTube
- **Project Showcase:** Featured projects with dedicated pages/links

## Configuration

### Updating Board Members

Edit `assets/boardmembers.json` to update board member information:

```json
[
    {
        "name": "Full Name",
        "title": "Position",
        "major": "Major/Department",
        "image": "assets/board_photos/photo.jpg",
        "linkedin": "https://linkedin.com/in/username"
    }
]
```

### Updating Alumni

Edit `assets/alumni.json` to update alumni information:

```json
[
    {
        "name": "Full Name",
        "title": "Former Position",
        "major": "Major/Department",
        "image": "assets/board_photos/photo.jpg",
        "linkedin": "https://linkedin.com/in/username",
        "company": "Company Name"
    }
]
```

## Development Workflow

1. **Clone the repository**
   ```bash
   git clone https://github.com/tea-at-ucsd/teaatucsdsite.git
   cd teaatucsdsite
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make changes** using your preferred editor (VS Code recommended)

4. **Stage and commit changes**
   ```bash
   git add .
   git commit -m "Descriptive commit message"
   ```

5. **Push to remote**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** on GitHub

7. **Merge to main** after review to trigger automatic deployment

## Deployment

This site uses GitHub Pages for automatic deployment:

- **Source:** `main` branch
- **Trigger:** Automatic on push/merge to `main`
- **Deployment Time:** 1-5 minutes
- **URL:** https://tea-at-ucsd.github.io/teaatucsdsite/

## Local Development

Use the live server extension in VS Code to run the site locally.

## Troubleshooting

### Images Not Loading
- Check file paths in HTML and JSON files
- Verify image files exist in the correct directories
- Ensure image names match exactly (case-sensitive)

### JSON Data Not Loading
- Validate JSON syntax using an online validator
- Check for trailing commas
- Ensure proper file encoding (UTF-8)

