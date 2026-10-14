# ELVARON GLOBAL website

Static website deployed with GitHub Pages and GitHub Actions.

## Publish

1. Add the homepage file from the supplied website package to this repository's root and name it `index.html`.
2. In **Settings → Pages**, choose **GitHub Actions** as the build and deployment source.
3. Configure the custom domain `elvaronglobal.com` in **Settings → Pages** if it is not already detected from `CNAME`.
4. At your domain registrar, configure DNS for GitHub Pages. For the apex domain, use GitHub's currently documented A records and optionally an AAAA record set; add a `www` CNAME to `elvaronglobal-droid.github.io` if you want the www subdomain. Check GitHub's official Pages custom-domain documentation for current values.
5. After DNS validation completes, enable **Enforce HTTPS** in Settings → Pages.

The site will not show the intended homepage until `index.html` is added to the repository root.
