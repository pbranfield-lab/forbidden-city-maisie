# forbidden-city-maisie — moved

This repository is a redirect stub. The project was renamed to **China 2026**
once it covered more than one trip, and now lives at:

- Repo: https://github.com/pbranfield-lab/china-2026
- Site: https://pbranfield-lab.github.io/china-2026/

## Why this stub exists

Renaming a repository on GitHub redirects the old `github.com` URL and any git
remotes automatically — but it does **not** redirect the old GitHub Pages URL,
which just 404s. This stub keeps the old public site address working.

`index.html` and `404.html` are identical: `404.html` is what catches deep
paths, because GitHub Pages serves it for any path that isn't a real file. Both
preserve the sub-path, query string and hash, so an old link such as
`.../forbidden-city-maisie/map.html?trip=xian&loc=pit-1` lands on the matching
page rather than the home page.

Keeping this stub is the trade-off for losing GitHub's automatic repo-URL
redirect: a repository existing at the old name overrides it. Delete this repo
if the old links stop mattering, and the automatic redirect resumes.
