# g9n Blog

This folder is a website published by [EtherPK](https://etherpk.com) from the publication
`g9n-blog`. Every file in it except `CNAME` and `robots.txt` is regenerated on each
publish, so edit the notes, the publication page, its include pages and its theme in the EtherPK app,
not here.

- Preview: open `index.html` in a browser; search works from disk too.
- GitHub Pages: push this folder to a repository and set Settings → Pages → Source to
  "GitHub Actions"; `.github/workflows/pages.yaml` deploys every push to `main`.
- Cloudflare: `npx wrangler deploy` uses `wrangler.jsonc`, or connect the repository in the
  Workers dashboard with no build command.
- Netlify, GitLab Pages, Vercel, S3 or your own server: the folder is plain files, so any of
  them serves it as it is. Step by step for each: https://docs.etherpk.com/hosting-a-published-site
