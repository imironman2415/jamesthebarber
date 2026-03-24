# Image Alt Text Guide for SEO

## Why Alt Text Matters

Alt text serves three critical purposes:
1. **Accessibility** - Screen readers read alt text for visually impaired users
2. **SEO** - Search engines use alt text to understand and index images
3. **User Experience** - Appears if image fails to load

## Alt Text Best Practices

### ✅ DO's:
- Be descriptive and concise (under 125 characters)
- Include relevant keywords naturally
- Include service type and location when applicable
- Describe what's in the image, not "image of" or "picture"
- Use proper grammar and punctuation

### ❌ DON'Ts:
- Don't use generic text like "image," "pic," or "photo"
- Don't keyword stuff or repeat keywords
- Don't use the filename as alt text
- Don't leave alt text empty (use `alt=""` for decorative images only)
- Don't write in ALL CAPS

---

## Recommended Alt Text for Mobile Barber Website

### Hero & Main Images

```html
<!-- Homepage Hero -->
<img src="images/hero-barber.jpg" alt="Professional mobile barber providing skin fade haircut at client's home in Rocky Mount NC">

<!-- Service Images -->
<img src="images/skin_fade.png" alt="Precision skin fade haircut - Mobile Barber LLC Rocky Mount Greenville Wilson Tarboro NC">
<img src="images/precision_haircut.png" alt="Expert precision haircut styling for men in Eastern North Carolina">
<img src="images/kids_haircut.png" alt="Professional kids haircut service at home by mobile barber">
<img src="images/executive_package.png" alt="Executive grooming package - complete haircut and beard trim service">
<img src="images/haircut_beard_combo.png" alt="Haircut and beard trim combo service from mobile barber">
<img src="images/barber-img.png" alt="Mobile barber professional portrait in work apron with tools">
```

### Testimonial Images

```html
<!-- Example testimonials with customer names and service -->
<img src="images/testimonial-kyle.png" alt="Kyle testimonial photo - fresh haircut from Mobile Barber LLC">
<img src="images/testimonial-marcus.png" alt="Marcus testimonial - textured fade haircut service">
<img src="images/testimonial-andre-curly-hair.png" alt="Andre testimonial - curly hair styling service">
<img src="images/testimonial-brian-textured-fade.png" alt="Brian testimonial - textured fade haircut">
<img src="images/testimonial-chris-fade-haircut.png" alt="Chris testimonial - professional fade haircut">
<img src="images/testimonial-derek-neckline-taper.png" alt="Derek testimonial - neckline taper precision haircut">
<img src="images/testimonial-harold-senior-haircut.png" alt="Harold testimonial - senior men haircut service">
<img src="images/testimonial-rebecca-kids-haircut.png" alt="Rebecca testimonial - kids haircut mobile service">
<img src="images/testimonial-ryan-crew-cut.png" alt="Ryan testimonial - crew cut haircut style">
<img src="images/testimonial-tommy-beard-grooming.png" alt="Tommy testimonial - professional beard grooming service">
```

### Blog Images

```html
<!-- Blog Article Images -->
<img src="images/blog/mobile-barber-hero.jpg" alt="Mobile barber providing convenient at-home haircut service in Rocky Mount NC">
<img src="images/blog/low-taper-fade-hero.jpg" alt="Professional low taper fade haircut example on male client">
<img src="images/blog/beard-grooming-hero.jpg" alt="Complete beard grooming and maintenance guide from mobile barber">
<img src="images/blog/skin-fade-example.jpg" alt="High fade skin cut example with clippers on sides and back">
<img src="images/blog/barber-tools.jpg" alt="Professional barber tools including clippers trimmers and shears">
<img src="images/blog/beard-care-products.jpg" alt="Beard care product recommendations - oil balm and conditioner">
```

### Logo & Branding

```html
<!-- Logo Images -->
<img src="images/barber-logo.png" alt="Mobile Barber LLC logo">
<img src="images/logo.png" alt="Mobile Barber LLC business logo">
```

### Decorative Images

For purely decorative images (background patterns, dividers, etc.), use empty alt text:
```html
<img src="images/decorative-pattern.png" alt="">
```

---

## How to Add Alt Text to Your HTML

### Inline Images
```html
<img src="path/to/image.jpg" alt="Descriptive alt text including service and location">
```

### Responsive Images with srcset
```html
<img 
  srcset="image-500px.jpg 500w, image-1000px.jpg 1000w"
  src="image-1000px.jpg"
  alt="Descriptive alt text for all image sizes"
>
```

### Background Images (CSS Alternative)
For critical images used as backgrounds, add a corresponding `<img>` with alt text:
```html
<div style="background-image: url('image.jpg')">
  <img src="image.jpg" alt="Alt text" style="display: none; visibility: hidden;">
</div>
```

---

## SEO Impact of Alt Text

### Keyword Optimization Examples

**Before (Poor):**
```html
<img src="image123.jpg" alt="">
<img src="fade-cut.jpg" alt="haircut">
```

**After (Optimized):**
```html
<img src="image123.jpg" alt="Professional skin fade haircut service Mobile Barber Rocky Mount NC">
<img src="fade-cut.jpg" alt="Low taper fade haircut example with professional styling">
```

### Location Keywords
Always include service area names when relevant:
- ✅ "Professional haircut service in Rocky Mount NC"
- ✅ "Mobile barber Greenville Wilson Tarboro"
- ❌ "Haircut" (too generic)
- ❌ "Image of a haircut" (unnecessary words)

---

## Verification Checklist

Use these tools to verify alt text implementation:

### 1. **Manual Check**
- Right-click image → "Inspect"
- Look for `alt="[descriptive text]"`
- Ensure text is descriptive and includes keywords

### 2. **Google Rich Results Test**
- Go to: https://search.google.com/test/rich-results
- Paste your URL
- Check for image-related issues

### 3. **Browser Accessibility Check**
- Disable images in browser (or use browser extension)
- Verify all critical information is still clear via alt text

### 4. **Search Console**
- Check Google Search Console coverage
- Look for images indexed with your content
- Verify no image crawl errors

---

## Implementation Timeline

1. **Week 1**: Add alt text to top-performing pages (homepage, main services)
2. **Week 2**: Update all blog post images
3. **Week 3**: Add alt text to testimonial images
4. **Week 4**: Review and refine for keyword optimization
5. **Ongoing**: Add alt text to all new images going forward

---

## Examples by Service Type

### Skin Fade Service Images
```
"Professional skin fade haircut - high fade on sides and back with longer top styling"
"Expert skin fade technique at home barber service Rocky Mount NC"
"Clean skin fade haircut with precision line work and shaping"
```

### Beard Grooming Service Images
```
"Professional beard trim and shaping at home by mobile barber"
"Beard grooming maintenance and styling guide from expert barber"
"Clean beard shape with precise line work and maintenance care"
```

### General Haircut Images
```
"Professional men's haircut styling at home in Greenville NC"
"Expert precision haircut with modern style and clean finish"
"Professional barber providing quality haircut service"
```

### Testimonial Images
```
"[Customer Name] testimonial - [Service Type] from Mobile Barber LLC"
"[Customer Name] satisfied client showing results of [Service] haircut"
```

---

## Measuring Impact

Monitor these metrics after implementing alt text:

1. **Image Search Traffic** (Google Analytics)
   - New traffic from Google Images
   - Click-through rates

2. **Image Indexation** (Google Search Console)
   - Number of images indexed
   - Image-related impressions
   - Image-related clicks

3. **Keyword Rankings**
   - Local keyword rankings in Google Images
   - Image pack visibility

---

## Quick Reference Template

```html
<!-- Standard format for all images -->
<img 
  src="images/image-name.jpg" 
  alt="[service type] [result/style shown] [location reference] - Mobile Barber LLC"
>

<!-- Example -->
<img 
  src="images/skin_fade_example.jpg" 
  alt="Professional skin fade haircut with precision styling - Mobile Barber Rocky Mount NC"
>
```

---

## Notes

- Alt text should enhance SEO without appearing forced or unnatural
- Search engines can read images better each year but still rely on alt text
- Alt text helps users understand content when images fail to load
- Screen readers benefit greatly from descriptive alt text
- Update alt text when you change or replace images

**Last Updated**: March 24, 2026
