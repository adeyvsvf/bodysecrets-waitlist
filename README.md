# Body Secrets Waitlist Website

A professional one-page waitlist website for Body Secrets skincare brand with integrated Mailchimp form.

## Features

✅ **Modern Design**: Clean, spa-like aesthetic with nature-inspired green color palette
✅ **Fully Responsive**: Mobile-first design that works on all devices
✅ **Mailchimp Integration**: Custom-styled form that submits directly to your mailing list
✅ **Interactive Slideshow**: Auto-rotating banner with manual navigation
✅ **Smooth Animations**: Hover effects and transitions throughout
✅ **Form Validation**: Built-in validation with loading states and success feedback

## Brand Colors

- **Primary Green**: #4A7C59 (forest green from logo)
- **Secondary Green**: #8FAA8B (sage green background)
- **Accent Green**: #2D5016 (darker green)

## File Structure

```
/Users/admin/BodysecretsWaitlist/
├── index.html                                     # Complete website file
├── WhatsApp Image 2025-09-13 at 13.59.57.jpeg   # Brand logo (used for slideshow too)
└── README.md                                      # This file
```

## Setup Instructions

1. **Local Development**: Simply open `index.html` in your web browser
2. **Web Hosting**: Upload both files to your web hosting service
3. **Custom Domain**: Configure your domain to point to the hosting location

## Mailchimp Integration

The form is connected to your Mailchimp list with the following details:

- **List ID**: c2b632fa68
- **User ID**: 8948c01c39daae9f13a0a250b
- **Form Fields**:
  - Email Address (required)
  - Full Name
  - Phone Number / WhatsApp
  - Excitement Level (radio buttons)
  - Early Access Preference (radio buttons)

### Form Features

- **Custom Styling**: Matches Body Secrets brand perfectly
- **Responsive Design**: Radio buttons stack on mobile devices
- **Loading States**: Shows "Joining..." while submitting
- **Success Feedback**: Beautiful modal popup on successful submission
- **Client-side Validation**: Ensures proper email format before submission

## Technical Specifications

- **Framework**: HTML5 + Tailwind CSS + Vanilla JavaScript
- **Fonts**: Inter (Google Fonts)
- **Icons**: Unicode emojis for lightweight loading
- **Dependencies**: 
  - Tailwind CSS (CDN)
  - jQuery (for Mailchimp validation)
  - Google Fonts

## Browser Support

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Mobile**: iOS Safari, Chrome Mobile, Samsung Internet
- **Responsive Breakpoints**:
  - Mobile: 320px - 768px
  - Tablet: 768px - 1024px
  - Desktop: 1024px+

## Customization

### Updating Images
Replace `WhatsApp Image 2025-09-13 at 13.59.57.jpeg` with your preferred images. For the slideshow, you can:
1. Add new image files to the directory
2. Update the `src` attributes in the slide elements
3. Maintain aspect ratios for best results

### Modifying Colors
Update the Tailwind config in the `<script>` section:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                'primary-green': '#YourColor',
                'secondary-green': '#YourColor',
                'accent-green': '#YourColor'
            }
        }
    }
}
```

### Adding Social Links
Add social media icons to the footer section by updating the footer HTML.

## Performance

- **Load Time**: Optimized for fast loading with CDN resources
- **Image Optimization**: Consider compressing images for web use
- **Mobile Performance**: Lightweight design with minimal JavaScript

## Support

For technical issues or customizations:
1. Check browser console for any JavaScript errors
2. Verify Mailchimp form is receiving submissions in your dashboard
3. Test form submission with valid email addresses

## Security

- **Spam Protection**: Includes hidden honeypot field for bot protection
- **HTTPS Ready**: Works with SSL certificates for secure form submission
- **Client-side Validation**: Prevents invalid data submission

---

**Ready to Launch!** 🚀

Your Body Secrets waitlist website is ready to collect email signups and build excitement for your upcoming product launch.
