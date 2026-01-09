# Adding Your Own Images to the Gallery

## Quick Start

1. **Add your images** to the `static/images/` folder
   - Example: `static/images/project1.jpg`

2. **Update gallery.md** front matter with your image paths:

```yaml
---
title: "Gallery"
layout: gallery
gallery_items:
  - title: "My Project"
    description: "Brief description"
    image: "/images/project1.jpg"
  - title: "Another Project"
    description: "More details"
    image: "/images/project2.jpg"
---
```

## Image Recommendations

- **Format**: JPG or PNG
- **Size**: Around 800-1200px wide works well
- **Aspect ratio**: 4:3 or 16:9 for consistent grid
- **File size**: Optimize to under 500KB for fast loading

## Using External Images

You can also use full URLs:
```yaml
image: "https://example.com/image.jpg"
```

## Gallery Layout Features

- ✅ Responsive grid (adapts to screen size)
- ✅ Hover effects with title/description overlay
- ✅ Click to view full image
- ✅ Mobile-friendly single column on small screens
- ✅ Smooth animations

## Next Steps

The gallery layout is in `layouts/gallery.html` - customize the CSS there to match your style preferences!
