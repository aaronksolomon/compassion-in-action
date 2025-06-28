# Compassion in Action Site

A simple, fast website built with Astro for collecting Plum Village community compassionate action support for Palestine-Israel. Uses Netlify Forms.

## Quick Start

1. Clone this repository
2. Install dependencies: `npm install`
3. Start development server: `npm run dev`
4. Visit `http://localhost:4321`

## Customizing Your Statement

Edit `src/pages/index.ast1pro` to replace the placeholder text with your actual statement.

## Deployment to Netlify

### Option 1: GitHub + Netlify (Recommended)

1. Push this code to a GitHub repository
2. Connect your GitHub repo to Netlify
3. Netlify will auto-detect Astro and deploy
4. Enable form detection in Netlify dashboard
5. Your site is live!

### Option 2: Direct Deploy

1. Run `npm run build`
2. Upload the `dist` folder to Netlify
3. Enable form detection in Netlify dashboard

## Form Submissions

- Form submissions appear in your Netlify dashboard under "Forms"
- You can export submissions as CSV
- Set up email notifications in Netlify settings

## Project Structure

```plaintext
├── src/
│   ├── layouts/
│   │   └── Layout.astro          # Main page template
│   ├── components/
│   │   └── SupportForm.astro     # The support form
│   └── pages/
│       ├── index.astro           # Homepage with statement
│       └── success.astro         # Form success page
├── netlify.toml                  # Netlify configuration
└── package.json                  # Dependencies
```

## Features

- ⚡ Lightning fast (static HTML/CSS)
- 📱 Mobile responsive
- 📝 Working contact form (via Netlify)
- 🎨 Clean, minimal design
- 🚀 Zero JavaScript (except form enhancement)

Built with [Astro](https://astro.build) and deployed on [Netlify](https://netlify.com).
