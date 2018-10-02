## Getting started

1. Install the deps: `yarn && bundle install`.

2. Run postcss to compile tailwind: `yarn build`.

3. Tell jekyll to serve the site: `jekyll serve`.


## Developing

If you're going to be editing styles, you probably want to run `yarn watch`,
which will rebuild tailwind when relevant files change.

Otherwise, you probably just want `jekyll serve`, which will rebuild the html
as you change the markdown, and also hosts a server for you on
`localhost:4000`.

## Deploying

The site is deployed automatically by Netlify when things are pushed to master.

It runs the above steps and then deploys.

Configure Netlify things here:

https://app.netlify.com/sites/pair-programming-guide/overview

## Todos

- [x] Newsletter signup
- [x] GH source link (ask folks to fix typos)
- [ ] Form field looks off on mobile
- [ ] Horizontal scrolling on mobile with long title
- [ ] Wire up DNS for permanent home (tuple.app/pair-programming-guide ?)
- [ ] Next article button
- [ ] Let people link directly to h2s
- [ ] Maybe add subnav on right

