## jaredcroyle.com

Built with [Gatsby](https://www.gatsbyjs.com/) and deployed via [Netlify](https://www.netlify.com/).

## Overview

This repo contains the source for my personal website at [jaredcroyle.com](https://jaredcroyle.com)!

Content is managed primarily via Markdown under the `content/` directory (jobs, projects, posts) and rendered with Gatsby.

## Tech Stack

- **Framework:** Gatsby (React)
- **Styling:** styled-components
- **Content:** Markdown (`content/`)
- **Images:** `gatsby-plugin-image`, `gatsby-remark-images`
- **Deployment:** Netlify

## Development

```bash
# install dependencies
npm install

# run dev server
npm run develop  # http://localhost:8000

# build production assets
npm run build
```

## Attribution

This site is heavily based on
[bchiang7/v4](https://github.com/bchiang7/v4) by [Brittany Chiang](https://brittanychiang.com).

I adapted the design, layout, and build setup for my own use, updated legacy code, and customized:

- Site content (jobs, projects, copy)
- Styling/theme values
- GraphQL queries and build configuration

If you reuse significant portions of this code or design, please credit both Brittany’s original work and this repo.
