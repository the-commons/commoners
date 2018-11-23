# Commoners

A website resource for residents of The Commons

### Running locally in development

You can skip this and just deploy your changes straight away if you'd like, but it will be useful if you need to debug any issues.

- If you don't have it, install [yarn](https://yarnpkg.com) (along with Node)
- `yarn install`
- `yarn run dev`

### Updating content

All of the content is created via [Markdown](https://www.markdownguide.org/) files that sit in the `docs` folder. The home page content is in the `README.md` directly under `docs`. When you add a new Markdown file, just give it an appropriate filename and add the corresponding nav for that filename in `.vuepress/config.js`. It will then appear in the menu bar.

### Deploying changes

- Push changes to Github
- Wait for Now to work it's magic
