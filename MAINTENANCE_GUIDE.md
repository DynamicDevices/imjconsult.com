# Website Maintenance Guide for IMJ Consulting Ltd

This guide explains how to make common updates to your website without needing technical expertise.

## 🔧 Making Basic Updates

### How to Edit Your Website

1. **Go to your GitHub repository**
   - Visit github.com and sign in
   - Go to your repository (imj-consulting-website)

2. **Edit the main file**
   - Click on `index.html`
   - Click the pencil icon (✏️) that says "Edit this file"

3. **Make your changes**
   - Use Ctrl+F (Windows) or Cmd+F (Mac) to find text you want to change
   - Make your edits carefully

4. **Save your changes**
   - Scroll to bottom of page
   - Add a description of what you changed
   - Click "Commit changes"
   - Your website will update automatically within a few minutes

## 📞 Common Updates

### Changing Contact Information

**To update phone number:**
1. Search for: `+44 (0) 1234 567890`
2. Replace with your actual phone number
3. Keep the same format for consistency

**To update email address:**
1. Search for: `info@imjconsulting.co.uk`
2. Replace with your preferred email
3. Make sure to update it in both the contact section and contact form

**To update business hours:**
1. Search for: `Monday - Friday: 9:00 AM - 5:00 PM`
2. Replace with your actual operating hours

**To update address/location:**
1. Search for: `Serving businesses across the UK`
2. Replace with your specific location or service area

### Updating Service Information

**To modify service descriptions:**
1. Find the service you want to update (search for the service name)
2. Look for the text under each service card
3. Edit the description to better reflect your offering

**To add a new service:**
1. Find an existing service card section
2. Copy the entire service card code
3. Paste it and modify the title, icon, and description

### Changing Business Information

**To update the "About" section:**
1. Search for: `About IMJ Consulting Ltd`
2. Find the paragraphs below this heading
3. Edit the text to better describe your business background and experience

**To update company qualifications:**
1. Search for: `Why Choose Us?`
2. Edit the bullet points to reflect your specific credentials and advantages

## 📧 Contact Form Management

### Checking Form Submissions
1. Log into your Formspree account at formspree.io
2. Go to your dashboard to see all form submissions
3. You'll receive emails for each new enquiry

### Updating Form Fields
1. In the HTML file, search for `contact-form`
2. You can add, remove, or modify form fields
3. Each field needs both a label and an input element

**Adding a new field example:**
```html
<div class="form-group">
    <label for="newfield">New Field Name</label>
    <input type="text" id="newfield" name="newfield">
</div>
```

## 🎨 Simple Design Changes

### Changing Colours
The website uses these main colours:
- Blue header: `#1e3c72` and `#2a5298`
- Yellow accent: `#ffd700`
- White backgrounds: `#ffffff`

To change colours:
1. Search for the colour code (e.g., `#1e3c72`)
2. Replace with your preferred colour code
3. Use a colour picker tool online to find colour codes

### Updating Text Content
- **Main headline:** Search for "Professional Health & Safety Solutions"
- **Subheading:** Search for "Protecting your business and workforce"
- **Call-to-action button:** Search for "Get Your Free Consultation"

## 📱 Testing Your Changes

After making updates:
1. **Visit your website** to see if changes appear correctly
2. **Test on mobile** by viewing on your phone
3. **Test contact form** by submitting a test enquiry
4. **Check all links** work properly

## ❗ Important Notes

### What NOT to change:
- Don't modify code within `<style>` tags unless you understand CSS
- Don't change file structure or HTML tags
- Don't remove quotation marks or brackets from code

### Safe changes:
- Text content between HTML tags
- Contact information
- Service descriptions
- Company information
- Colour codes (if you know what you're doing)

### If something goes wrong:
1. GitHub keeps a history of all changes
2. Click "History" to see previous versions
3. You can revert to a previous working version
4. Contact your web developer for help

## 🔄 Regular Maintenance Tasks

### Monthly:
- [ ] Check contact form is working
- [ ] Review contact information for accuracy
- [ ] Test website on different devices

### Quarterly:
- [ ] Update service information if offerings change
- [ ] Review and update business description
- [ ] Check for any broken links

### Annually:
- [ ] Update copyright year in footer
- [ ] Review all content for accuracy
- [ ] Consider adding client testimonials or case studies

## 📈 Improving Your Website

### Adding Testimonials
1. Find a good location in the HTML (perhaps after the About section)
2. Add customer quotes and names
3. This builds trust with potential clients

### Adding Photos
1. Upload images to your repository
2. Reference them in the HTML using `<img>` tags
3. Make sure images are optimised for web (small file sizes)

### SEO Improvements
- Keep content up-to-date and relevant
- Add blog posts about health & safety topics
- Include local area keywords if you serve specific regions

## 🆘 Getting Help

If you're unsure about any changes:
1. **Make a backup:** Copy your current website files before making major changes
2. **Test carefully:** Make small changes and test them before making more
3. **Contact support:** Reach out to your web developer for complex modifications
4. **Use GitHub's help:** GitHub has extensive documentation and community support

Remember: It's better to make small, careful changes than to try to modify everything at once!