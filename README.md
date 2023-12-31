# 🍞 Bun Blog

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fonsclom%2Fbun-blog&project-name=my-bun-blog&repository-name=my-bun-blog&demo-title=Bun%20Blog&demo-description=A%20simple%20and%20extensible%20statically%20generated%20blog.&demo-url=https%3A%2F%2Fbun-blog.vercel.app%2F)

[ 🔨 STILL UNDER CONSTRUCTION ]

A simple and extendable static site generator built with [Bun](https://bun.sh/).

Similar to the awesome [Bear Blog](https://bearblog.dev/), but as a static site
generator that you own instead of a service.

## Features

- Perfect page speed scores out of the box
- Deploy your own blog to Vercel in seconds
  - Or deploy to any CDN that accepts static files
- Super tiny, optimized pages that look great on all devices (inspired by
  [Bear Blog](https://bearblog.dev/))
- Great defaults that can be tweaked without touching code ... maybe\*
- Everything in Bun Blog is customizeable
  - `index.ts` is optimized for modification
  - Add your own features or completely change how existing features work!

\* I'm debating whether to leave settings in the code. Editing `index.ts`
directly would be intimidating to new coders, but it would be an exciting
introduction to the code for more experienced coders.

## TODO

- add asset workflow
- add RSS feed generation
- rewrite readme
- write documentation
  - for people who want a no-code bear blog like experience
  - for people who want to do local dev with bun
- figure out local dev server solution

## idea brainstorming

- maybe JSX could be nice?
- make a hono version with SSRd pages?
- make a discovery service bun blog users can opt into, like bear blog's
  discover
  - maybe it could just poll RSS feeds?
  - could have comments and other fun stuff
- i should look into webmentions
