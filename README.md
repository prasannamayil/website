# Prasanna Mayilvahanan's Academic Website

This is the source code to Prasanna Mayilvahanan's academic website hosted at [www.prasannamayil.com](https://www.prasannamayil.com).

## Contact
- Email: prasanna.mayilvahanan@uni-tuebingen.de
- Alternative: prasanna.mayilvahanan@gmail.com

## Features

- Personal academic portfolio
- Publications list with links
- Blog section for articles and thoughts
- CV download
- Social media links

## Structure

- `index.html` - Main homepage with bio and publications
- `blog.html` - Blog listing page
- `blog/` - Directory for individual blog posts
- `data/` - Directory for CV and other documents
- `images/` - Directory for images and figures

## Setup for Custom Domain

1. The `CNAME` file is already configured for `www.prasannamayil.com`
2. Configure your domain's DNS settings:
   - Add a CNAME record pointing `www` to `[your-github-username].github.io`
   - Optionally, add A records for the apex domain pointing to GitHub's IP addresses

## Adding Content

### Blog Posts
Create new HTML files in the `blog/` directory and link them from `blog.html`.

### CV
Place your CV PDF in the `data/` directory as `CV_Prasanna_Mayilvahanan.pdf`.

### Paper Figures
Add figure images to the `images/` directory and update the image sources in `index.html`.

---

Based on Jon Barron's website template: https://jonbarron.info/