# Jerra Stemmle, MFTC - Private Practice Website

A calm, professional website for marriage and family therapy practice, hosted on GitHub Pages using Jekyll.

## Site Structure

- **Home** (`index.md`) - Headshot, bio, and contact link
- **About & Approach** (`about.md`) - Therapeutic approach and credentials
- **Services** (`services.md`) - Individual and couples therapy offerings
- **Contact** (`contact.md`) - Contact information and FAQs

## Setup Instructions

### Local Development

1. Install Ruby and Bundler if not already installed
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run the site locally:
   ```bash
   bundle exec jekyll serve
   ```
4. View at `http://localhost:4000`

### Customization

#### 1. Add Your Headshot
- Place your professional headshot as `headshot.jpg` in `/assets/images/`
- Recommended: Square format (400x400px minimum)

#### 2. Update Contact Information
Edit `_config.yml` and `contact.md` with your:
- Email address
- Phone number
- Office address
- Office hours

#### 3. Personalize Content
Update the following files with your information:
- `index.md` - Your bio and welcome message
- `about.md` - Your education, training, and supervisor information
- `services.md` - Your fee structure and insurance details
- `contact.md` - Your specific contact details and policies

#### 4. Customize Colors (Optional)
Edit `/assets/css/style.scss` to adjust the color palette if desired.

## Color Palette

The site uses a calm, zen-inspired color scheme:
- Sage Green: `#7ba591` (primary accent)
- Deep Teal: `#5a7d6f` (headings)
- Warm Cream: `#f5f3ed` (background)
- Soft Grey: `#666666` (body text)

## Deployment

This site is automatically deployed via GitHub Pages when you push to the `main` branch.

## Theme

Uses the Minima Jekyll theme with custom styling for a warm, welcoming aesthetic.