## Getting started

0. Install the deps: `yarn && bundle install`.

1. Run postcss to compile tailwind: `yarn build`

2. Tell jekyll to serve the site: `jekyll serve`


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
