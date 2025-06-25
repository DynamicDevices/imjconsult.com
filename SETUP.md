# GitHub Pages Setup Instructions for IMJ Consulting Ltd Website

Follow these step-by-step instructions to get your website live on GitHub Pages.

## 🚀 Quick Start (5 minutes)

### Step 1: Create GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create a free account
3. Verify your email address

### Step 2: Create Repository
1. Click the green "New" button (or the "+" icon in top right)
2. Repository name: `imj-consulting-website` (or any name you prefer)
3. Description: "Official website for IMJ Consulting Ltd"
4. Make sure "Public" is selected (required for free GitHub Pages)
5. Check "Add a README file"
6. Click "Create repository"

### Step 3: Upload Website Files
1. In your new repository, click "uploading an existing file"
2. Upload the `index.html` file (drag and drop or click to browse)
3. Scroll down and add commit message: "Add IMJ Consulting website"
4. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. In your repository, click "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Branch: Select "main"
5. Folder: Select "/ (root)"
6. Click "Save"

### Step 5: Get Your Website URL
1. After a few minutes, your site will be available at:
   `https://[your-username].github.io/[repository-name]/`
2. For example: `https://johnsmith.github.io/imj-consulting-website/`

## 📧 Setting Up Contact Form

### Step 1: Create Formspree Account
1. Go to [formspree.io](https://formspree.io)
2. Click "Get Started" and sign up for free account
3. Verify your email

### Step 2: Create Contact Form
1. In Formspree dashboard, click "New Form"
2. Form name: "IMJ Consulting Contact Form"
3. Copy the form endpoint URL (looks like: `https://formspree.io/f/abcd1234`)

### Step 3: Update Website
1. Go back to your GitHub repository
2. Click on `index.html` file
3. Click the pencil icon (Edit this file)
4. Find line with `action="https://formspree.io/f/YOUR_FORM_ID"`
5. Replace `YOUR_FORM_ID` with your actual Formspree form ID
6. Scroll down and click "Commit changes"

## 🔧 Customisation Tasks

### Essential Updates Needed:

#### 1. Update Contact Information
Replace these placeholder details with real information:
- **Phone:** Change `+44 (0) 1234 567890` to actual business number
- **Email:** Confirm `info@imjconsulting.co.uk` is the preferred email
- **Address:** Update "Serving businesses across the UK" if you want to show specific location

#### 2. Business Details
- Verify all service descriptions are accurate
- Update the "About" section with specific business background
- Add any certifications or qualifications

#### 3. Optional Enhancements
- Add business logo (replace text logo)
- Include client testimonials
- Add business photos
- Set up Google Analytics for visitor tracking

## 🌐 Custom Domain (Optional)

If you want your own domain (e.g., www.imjconsulting.co.uk):

### Step 1: Buy Domain
1. Purchase domain from provider like Namecheap, GoDaddy, etc.
2. Note down the domain name

### Step 2: Configure GitHub Pages
1. In repository Settings > Pages
2. Under "Custom domain", enter your domain
3. Check "Enforce HTTPS"
4. Click "Save"

### Step 3: Update DNS Settings
1. In your domain provider's control panel
2. Add these DNS records:
   - Type: `A` | Name: `@` | Value: `185.199.108.153`
   - Type: `A` | Name: `@` | Value: `185.199.109.153`
   - Type: `A` | Name: `@` | Value: `185.199.110.153`
   - Type: `A` | Name: `@` | Value: `185.199.111.153`
   - Type: `CNAME` | Name: `www` | Value: `[your-username].github.io`

## 📞 Support

If you need help with any of these steps:
1. GitHub has excellent documentation: [docs.github.com](https://docs.github.com)
2. Formspree support: [help.formspree.io](https://help.formspree.io)
3. Contact your web developer who created this for you

## ✅ Checklist

- [ ] GitHub account created
- [ ] Repository created and files uploaded
- [ ] GitHub Pages enabled
- [ ] Website loads correctly
- [ ] Contact form configured with Formspree
- [ ] Contact information updated
- [ ] Business details verified
- [ ] Custom domain configured (optional)

**Estimated setup time:** 15-30 minutes

Once complete, your professional website will be live and accessible to customers worldwide!