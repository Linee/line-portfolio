## This is Line's data science feelancing website.

1️⃣ Start the local development server

Every time you want to work on your site and see changes live:
`hugo server -D`


-D includes drafts (important when working on new posts).

Open in browser: http://localhost:55770/

Hugo automatically reloads when you edit files.

2️⃣ Add new content

*Blog posts:*
`hugo new posts/my-first-post.md`

This creates a file under content/posts/.
Open it (nano, VS Code, etc.) and edit the front matter and content.

*Pages (like About or Projects):*
`hugo new about.md`

Creates a page under content/.
Update config.toml menus if you want it in the navigation.

3️⃣ Customize site settings

Open config.toml (or _default/params.toml) and edit:

- Profile info: name, bio, image

- Social links: GitHub, LinkedIn, Twitter, etc.

- Skills & experience

- Projects

- Theme colors

Most Hugo Profile settings live in config/_default/params.toml.

4️⃣ Customize layout and styling

- Theme templates are in themes/hugo-profile/layouts/

- CSS/SCSS is in themes/hugo-profile/assets/

You usually only need to edit config.toml and content files for a personal site.
Customizing templates or CSS is optional unless you want a unique look.

5️⃣ Test your changes

Every time you save a file while hugo server is running, refresh your browser — Hugo live reloads automatically.

6️⃣ Build for production

When ready to deploy:

`hugo


This creates a public/ folder with your static site.
You can upload public/ to Netlify, Vercel, GitHub Pages, or any static host.

7️⃣ Recommended workflow

1. hugo server -D → preview site locally

2. Edit content/pages/images → auto-refresh in browser

3. Edit config.toml/params.toml → update theme settings

4. Commit changes to Git → optional

5. hugo → deploy static site
