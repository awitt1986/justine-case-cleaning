# Setup Instructions for GitHub Pages Custom Domain Configuration

## Step 1: Set Up Your GitHub Pages
1. Go to your repository on GitHub.
2. Click on `Settings`.
3. In the left sidebar, click on `Pages`.
4. Under `Source`, select the branch (usually `main`) and the folder (usually `/ (root)`) you want to use for GitHub Pages.
5. Click `Save`.

## Step 2: Configure Your Custom Domain
1. Purchase a domain from a domain registrar (e.g., GoDaddy, Namecheap).
2. In your GitHub Pages settings, find the `Custom domain` section.
3. Enter your custom domain (e.g., `www.yourdomain.com`) and click `Save`.
4. GitHub will now provide DNS instructions for configuring your domain.

## Step 3: Update DNS Settings
1. Log in to your domain registrar's website.
2. Find the DNS management or settings section.
3. Add the following records:
   - **A Records**: Point your domain to GitHub's IP addresses.
   - **CNAME Record**: Point www.yourdomain.com to yourusername.github.io (replace `yourusername` with your GitHub username).
4. Save your changes.

## Step 4: Verify your domain
1. Go back to your GitHub Pages settings.
2. Wait for a few minutes for the DNS changes to propagate.
3. Refresh the page, and you should see a confirmation message that your custom domain is set up correctly.

## Additional Information
- Make sure to enable HTTPS for your custom domain in GitHub Pages settings if available.