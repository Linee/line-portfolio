## This is Line's data science feelancing website.

# Start the local development server

Every time you want to work on your site and see changes live:
`hugo server -D`

-D includes drafts (important when working on new posts).

Open in browser localhost.

Hugo automatically reloads when you edit files.

# Customize site settings

Open hugo.yaml and edit:

- Profile info: name, bio, image

- Social links: GitHub, LinkedIn, Twitter, etc.

- Skills & experience

- Projects

- Theme colors


# Customize layout and styling

- Theme templates are in themes/hugo-profile/layouts/

- CSS/SCSS is in themes/hugo-profile/assets/

You usually only need to edit hugo.yaml and content files for a personal site.
Customizing templates or CSS is optional unless you want a unique look.

# Test your changes

Every time you save a file while hugo server is running, refresh your browser — Hugo live reloads automatically.

# Build for production

When ready to deploy:

`hugo


This creates a public/ folder with your static site.
You can upload public/ to Netlify, Vercel, GitHub Pages, or any static host.

# Recommended workflow

1. hugo server -D → preview site locally

2. Edit content/pages/images → auto-refresh in browser

3. Edit config.toml/params.toml → update theme settings

4. Commit changes to Git → optional

5. hugo → deploy static site
