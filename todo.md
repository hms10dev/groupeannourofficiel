# Todo List For Site:

## Images
### Hero Page slideshow:
- [X] Add 4 images to your images/ folder named:
  - hero-slide-1.jpg 
  - hero-slide-2.jpg 
  - hero-slide-3.jpg
  - hero-slide-4.jpg
- [x] Add images to the site

# INTER + LORA FONT IMPLEMENTATION

## Add this to the <head> section of EVERY HTML file:
(Place it after the viewport meta tag and before the stylesheet link)

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Lora:wght@400;600;700&display=swap" rel="stylesheet">
```

## Files to update:
1. index.html
2. programmes.html
3. admissions.html
4. direction.html
5. contact.html

## Example of where to place it:

```html
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- ADD GOOGLE FONTS HERE -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Lora:wght@400;600;700&display=swap" rel="stylesheet">
  <!-- END GOOGLE FONTS -->
  
  <meta name="description" content="...">
  <title>...</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

## What changed in styles.css:
- ✅ CSS has been updated automatically
- ✅ Headings now use Inter (clean, modern)
- ✅ Body text now uses Lora (readable, elegant serif)
- ✅ All UI elements (buttons, forms, nav) use Inter

## Font usage:
- **Inter**: All headings (h1-h6), navigation, buttons, forms, labels
- **Lora**: Body text, paragraphs, descriptions

This creates excellent visual hierarchy and readability