# Showcase

A throwaway demo site whose only purpose is to show off live, voice driven web
building. It is hosted on Netlify and redeploys automatically on every push to
`main`, usually within a few seconds, so changes appear live almost as fast as
they are spoken.

## What this repo is for
- Demoing the Showcase agent: speak or chat an instruction, watch the page
  update live on Netlify moments later.
- Nothing here is precious. The page gets cleared and rebuilt over and over.
  Whatever is on it does not matter and can be replaced at any time.

## Rules for working here
- Keep it a plain static site: `index.html` plus optional CSS and JS in the
  repo root. No build step, no framework, no backend, no CI/CD. Netlify serves
  the files as they are, which is what makes deploys instant.
- Do not add package.json, bundlers, or a `netlify.toml` build command unless
  asked. A build step would slow deploys down and defeats the point.
- When asked to "clear", "reset", or "empty" the page, return `index.html` to a
  minimal page showing a single line like "Showcase hosted on Netlify".
- Never use dash characters in any user facing text. No hyphens, en dashes, or
  em dashes. Use a comma, a period, or the word "to" instead.
- Keep replies short: say plainly what you changed in a sentence or two, no
  code dumps.
