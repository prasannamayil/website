# Setup Notes for www.prasannamayil.com

## Custom Domain Configuration

1. **GitHub Pages Setup**:
   - Go to your repository Settings → Pages
   - Enable GitHub Pages from page branch
   - The CNAME file is already configured for www.prasannamayil.com

2. **Domain DNS Configuration**:
   You need to configure your domain registrar's DNS settings:
   
   **For www subdomain (recommended):**
   - Add a CNAME record: `www` → `[your-github-username].github.io`
   
   **For apex domain (prasannamayil.com):**
   - Add A records pointing to GitHub's IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

3. **SSL Certificate**:
   - GitHub Pages automatically provides HTTPS once DNS is configured
   - May take up to 24 hours to provision

## Important Files to Add

1. **CV**: Place your CV as `data/CV_Prasanna_Mayilvahanan.pdf`
2. **Paper Figures**: Add images to `images/` directory
3. **Profile Photo**: The avatar.jpg is already in place
4. **Favicon**: Optionally add a custom favicon to `images/favicon/`

## Email Addresses

Primary email: `prasanna.mayilvahanan@uni-tuebingen.de`
Secondary email: `prasanna.mayilvahanan@gmail.com`

Currently using the university email on the website. To change, update the mailto link in index.html.

## Blog Posts

To add a new blog post:
1. Copy `blog/template.html` to `blog/your-post-name.html`
2. Edit the content
3. Add an entry in `blog.html` linking to your new post

## Deployment Checklist

- [ ] Configure DNS at your domain registrar
- [ ] Add CV PDF to data directory
- [ ] Replace placeholder images with actual paper figures
- [ ] Test all links work correctly
- [ ] Verify custom domain is working (may take 24-48 hours) 