# buildingboulder-site

The Boulder Builders website, published at **www.buildingboulder.com** with GitHub Pages.

- `public/` is the site exactly as served (`index.html` at its root). `public/CNAME` sets the custom domain.
- Every push to `main` deploys through `.github/workflows/deploy.yml`.
- The page carries `noindex` until Boulder Builders approves the launch.
- Forms post to Boulder Builders' own CRM.
