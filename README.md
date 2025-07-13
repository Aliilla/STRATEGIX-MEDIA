# Strategix Media Landing Page

A high-converting, modern single landing page for Strategix Media SMMA, targeting Moroccan real estate agents and agencies.

## 🎯 Features

### ✅ Language Support
- **Arabic (Default)** - Modern Arabic font (Cairo) with RTL layout
- **French** - Complete French translation with LTR layout
- **Language Toggle** - Easy switch between languages

### ✅ Conversion Elements
- **Hero Section** - Compelling headline and subheadline
- **WhatsApp CTA** - Primary call-to-action optimized for Morocco
- **Lead Capture Form** - Complete form with all requested fields
- **Floating WhatsApp Chat** - Always accessible contact option

### ✅ Trust & Social Proof
- **Trust Section** - Moroccan cities (Casablanca, Rabat, Marrakech)
- **Testimonials** - Real estate agent testimonials
- **Client Results** - Quantified success metrics

### ✅ Benefits Section
- **Local Market Understanding** - فهمنا للسوق المحلي
- **Done-For-You Service** - خدمة كاملة دون جهد من العميل
- **Precise Targeting** - استهداف دقيق للمشترين المهتمين

### ✅ How It Works
1. **Audit** - تدقيق شامل
2. **Ad Creation** - إنشاء الإعلانات
3. **Lead Generation** - جلب العملاء المحتملين
4. **Continuous Support** - دعم مستمر

## 🎨 Design Features

- **Modern & Mobile-First** - Responsive design for all devices
- **Green & Yellow Branding** - As requested color scheme
- **Moroccan-Inspired** - Subtle geometric patterns
- **Professional Typography** - Cairo font for Arabic, Inter for French
- **Smooth Animations** - Hover effects and transitions

## 📱 WhatsApp Integration

- **Primary CTA** - Direct WhatsApp booking links
- **Floating Chat Icon** - Always visible contact option
- **Pre-filled Messages** - Customized for each language

## 🔧 Customization Guide

### Update WhatsApp Number
Replace `212600000000` with your actual WhatsApp number in:
- Hero section CTA buttons
- Floating WhatsApp chat links

### Update Form Submission
The form currently logs to console. To connect to your backend:
1. Replace the form submission handler in the JavaScript
2. Add your server endpoint
3. Configure email notifications

### Add Real Testimonials
Replace placeholder testimonials with real client feedback:
- Update names and cities
- Add real photos (optional)
- Include actual results

### Customize Colors
Modify CSS variables in the `:root` section:
```css
:root {
    --primary-green: #22c55e;
    --secondary-yellow: #fbbf24;
    --dark-green: #16a34a;
    /* ... other colors */
}
```

### Add Analytics
Add Google Analytics or Facebook Pixel:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚀 Deployment

### Option 1: GitHub Pages
1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify
1. Drag and drop the `index.html` file to Netlify
2. Get instant deployment with custom domain option

### Option 3: Vercel
1. Connect your GitHub repository to Vercel
2. Automatic deployments on every push

## 📊 Performance Optimization

- **Optimized Images** - Use WebP format for better loading
- **Minified CSS** - Consider minifying for production
- **CDN Fonts** - Google Fonts already optimized
- **Lazy Loading** - Add for images if needed

## 🔒 Security Considerations

- **HTTPS** - Always use HTTPS in production
- **Form Validation** - Client-side validation implemented
- **XSS Protection** - Sanitize form inputs on server

## 📈 Conversion Optimization Tips

1. **A/B Test Headlines** - Test different value propositions
2. **Optimize CTA Buttons** - Test colors, text, and placement
3. **Add Urgency** - Limited time offers or scarcity
4. **Social Proof** - Add more testimonials and case studies
5. **Mobile Optimization** - Ensure perfect mobile experience

## 🛠 Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks needed
- **Google Fonts** - Cairo (Arabic) and Inter (French)
- **Font Awesome** - Icons

## 📞 Support

For customization help or questions, contact your developer or refer to the inline comments in the code.

---

**Built for Strategix Media** - Helping Moroccan real estate agents double their sales with targeted Meta Ads.