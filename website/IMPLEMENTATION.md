# Kissan App Website Implementation Guide

This document explains which image files are used on the `index.html` page, where to place them, and the recommended sizes for best quality.

## Folder structure

Put all website files inside:

- `website/`

Images go inside:

- `website/assets/img/`

CSS file:

- `website/assets/css/style.css`

JavaScript file:

- `website/assets/js/main.js`

Main HTML page:

- `website/index.html`
- `website/calculators.html`
- `website/plant-health.html`
- `website/mandi-rates.html`
- `website/crop-planning.html`

## Image list

### 1. Logo

- File name: `logo.png`
- Location: `website/assets/img/logo.png`
- Recommended size: `320 x 120 px`
- Format: `PNG`
- Use: Header logo and footer logo
- Tip: Use a transparent background PNG for the cleanest look

### 2. Hero background image

- File name: `hero-bg.jpg`
- Location: `website/assets/img/hero-bg.jpg`
- Recommended size: `1920 x 1080 px`
- Format: `JPG`
- Use: Full hero section background behind the transparent header
- Tip: Use a wide field or farming landscape image similar to the reference

### 3. Tool cards image

- File name: `card.jpeg`
- Location: `website/assets/img/card.jpeg`
- Recommended size: `900 x 600 px`
- Format: `JPEG`
- Use: Used in all 3 cards inside the Precision Tools section
- Tip: You can keep one shared image or later replace each card with separate images if needed

### 4. Plant scan image

- File name: `plantcamera.jpg`
- Location: `website/assets/img/plantcamera.jpg`
- Recommended size: `1200 x 1400 px`
- Format: `JPG`
- Use: Left side image in the "Heal your crops with a single scan." section
- Tip: Use a close-up agricultural image with a phone or device in hand if possible

### 5. Mobile app mockup

- File name: `app-phone.png`
- Location: `website/assets/img/app-phone.png`
- Recommended size: `900 x 1400 px`
- Format: `PNG`
- Use: Right side phone image in the mobile app section
- Tip: Best if this image has transparent background

### 6. Modern farm section image

- File name: `feature-support.jpg`
- Location: `website/assets/img/feature-support.jpg`
- Recommended size: `1200 x 1400 px`
- Format: `JPG`
- Use: Left side image in the "Built for the modern farm." section
- Tip: Use an image showing a farm device, agricultural technology, or field monitoring

### 7. Footer background texture

- File name: `footer-texture.jpg`
- Location: `website/assets/img/footer-texture.jpg`
- Recommended size: `1600 x 600 px`
- Format: `JPG`
- Use: Background texture/image for the footer section
- Tip: Keep this dark and subtle so footer text remains easy to read

### 8. Field plot image

- File name: `field-plot.jpg`
- Location: `website/assets/img/field-plot.jpg`
- Recommended size: `1200 x 700 px`
- Format: `JPG`
- Use: Selected plot image on the `crop-planning.html` page
- Tip: Use an aerial farm field image with visible crop geometry or contour patterns

## How to replace placeholders

1. Open the folder `website/assets/img/`.
2. Replace the placeholder images with your real images.
3. Keep the exact same file names.
4. Refresh the browser after replacing the files.

## Mandi Rates page asset usage

The `mandi-rates.html` page reuses the same image system to keep things simple.

- `logo.png` is used in the header and footer.
- `card.jpeg` is used as the community post image placeholder.
- `footer-texture.jpg` is used in the footer background.

If you want a dedicated image just for the community post later, we can add a separate file such as `mandi-post.jpg` and wire it into the page.

## Crop Planning page asset usage

The `crop-planning.html` page uses:

- `logo.png` in the header and footer
- `card.jpeg` for crop variety cards
- `field-plot.jpg` for the selected plot preview
- `footer-texture.jpg` for the footer background

## Calculators page asset usage

The `calculators.html` page currently uses:

- `logo.png` in the header and footer
- `footer-texture.jpg` for the footer background

This page is intentionally built mostly with layout, typography, and UI cards, so it does not require additional images right now.

## Plant Health page asset usage

The `plant-health.html` page uses:

- `logo.png` in the header and footer
- `plantcamera.jpg` as the uploaded plant scan preview image
- `footer-texture.jpg` for the footer background

This page is designed to present an AI report workflow where Gemini AI analyzes an uploaded crop image and returns diagnosis and action guidance.

## If you want different images for each card

Right now the page uses the same file `card.jpeg` for all 3 cards.

If you want 3 separate card images later, we can change them to:

- `card-1.jpeg`
- `card-2.jpeg`
- `card-3.jpeg`

and update the HTML accordingly.
