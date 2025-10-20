# Technical Portfolio Workshop

This repository contains materials for a 90-minute workshop teaching participants how to build a professional technical portfolio using GitHub Pages. Designed for the re:Invent All Builders Welcome workshop.

## Project Structure
```
technical-portfolio/
├── README.md                           # This file
├── my-portfolio/                       # Working example portfolio (instructor's)
│   ├── index.html
│   ├── about.html
│   ├── projects.html
│   ├── blog.html
│   ├── contact.html
│   ├── she-builds-episodes.html
│   └── styles.css
├── templates/                          # Clean templates for participants
│   ├── index.html
│   ├── about.html
│   ├── projects.html
│   ├── blog.html
│   ├── contact.html
│   └── styles.css
└── workshop-materials/                 # Workshop guides and resources
    ├── WORKSHOP-DELIVERY-GUIDE.md     # Main 90-minute workshop plan
    ├── Q-PORTFOLIO-PROMPT.md          # Q Developer master prompt
    └── q-developer-rules/             # Q Developer workflow rules
        └── portfolio-workflow.md
```

## Workshop Overview

**Duration:** 90 minutes  
**Target Audience:** Early career technologists (All Builders Welcome grant recipients)  
**Goal:** Every participant leaves with a working 3-page portfolio

### Three Workshop Paths

1. **Path 1: Local Development** (Recommended for most)
   - No tools required beyond text editor and browser
   - Download templates, edit locally, view immediately
   - Can deploy to GitHub Pages later

2. **Path 2: AI-Powered with Q Developer**
   - For those with Amazon Q Developer installed
   - Use guided prompts to generate personalized portfolio
   - Learn AI-assisted development

3. **Path 3: GitHub Pages**
   - For those with GitHub accounts
   - Fork template, edit, deploy immediately
   - Live site at username.github.io

## Quick Start for Instructors

1. **Review** `workshop-materials/WORKSHOP-DELIVERY-GUIDE.md`
2. **Prepare** your example portfolio (`my-portfolio/`)
3. **Package** templates folder as ZIP for Path 1 participants
4. **Test** all three paths before workshop
5. **Send** pre-workshop information gathering worksheet to participants

## Quick Start for Participants

### Path 1: Local Development
1. Download `templates/` folder
2. Open files in any text editor
3. Replace placeholders with your information
4. Open `index.html` in browser to view

### Path 2: Q Developer
1. Install Amazon Q Developer
2. Use master prompt from `Q-PORTFOLIO-PROMPT.md`
3. Provide your information
4. Iterate with Q to customize

### Path 3: GitHub Pages
1. Fork this repository
2. Edit files in `templates/` folder
3. Enable GitHub Pages in repository settings
4. Visit `username.github.io` to see live site

## Key Features

- **Responsive design** - Works on mobile and desktop
- **WCAG accessible** - Meets accessibility standards
- **Modern styling** - Clean, professional appearance
- **Easy customization** - Simple color scheme changes
- **No dependencies** - Pure HTML/CSS, no frameworks

## Success Criteria

By workshop end, participants will have:
- [ ] Working portfolio with their real content
- [ ] At least 3 pages (home, about, projects)
- [ ] Contact information
- [ ] Mobile-responsive design
- [ ] Knowledge of how to update it

## Post-Workshop Resources

- Example portfolio: `my-portfolio/`
- Troubleshooting guide in workshop materials
- AWS integration opportunities for advanced users
- Community support links

## Contributing

This workshop is designed for re:Invent All Builders Welcome. For questions or improvements, please open an issue.

## License

MIT License - Feel free to use and adapt for your own workshops.

---

*Built with ❤️ for the AWS community*
