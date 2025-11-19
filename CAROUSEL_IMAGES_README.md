# Image Carousel Setup Instructions

## 📁 Folder Structure for Carousel Images

Place your carousel images in the following folder:
```
assets/images/
```

## 🖼️ Automatic Image Loading System

The carousel now **automatically detects and loads all images** from your `assets/images/` folder (excluding your profile photo). You can add any images you want, and they'll automatically appear in the carousel!

### 🚫 **Excluded from Carousel:**
- **`Vencedor-1756719927366.jpg`** - Your profile photo (stays in student profile section only)

### ✅ **Automatically Included in Carousel:**
The system will automatically create carousel slides for these images if they exist:

1. **`project-showcase.jpg`** - Innovation Projects & Enterprise Systems
2. **`achievements.jpg`** - Recognition, Awards & Academic Honors  
3. **`campus-life.jpg`** - University of Lusaka Campus Life
4. **`technology.jpg`** - Technology Focus & Information Systems
5. **`academic-work.jpg`** - Academic Excellence & Research
6. **`team-projects.jpg`** - Collaborative Work & Leadership
7. **`presentations.jpg`** - Academic Presentations & Conferences
8. **`graduation.jpg`** - Graduation Journey & Milestones

### 🆕 **Add Your Own Images:**
You can add **any images** with any names to the `assets/images/` folder, and they'll automatically be included in the carousel! The system will:
- Automatically detect new images
- Create appropriate titles and descriptions
- Add navigation dots
- Include them in the auto-rotation

## 📐 Image Specifications

### Recommended Image Properties:
- **Format**: JPG, PNG, or WebP
- **Dimensions**: 1200x800 pixels (3:2 aspect ratio)
- **File Size**: Under 2MB per image for optimal loading
- **Quality**: High resolution for crisp display

### Image Optimization Tips:
- Use image compression tools to reduce file size
- Ensure good lighting and clear focus
- Consider using professional photography or high-quality stock photos
- Maintain consistent style across all images

## 🎯 How to Add Your Images

### **Simple Method (Recommended):**
1. **Prepare your images** according to the specifications above
2. **Place them in the folder**: `assets/images/`
3. **That's it!** The carousel automatically detects and includes them

### **Specific Image Names (Optional):**
If you want specific titles and descriptions, use these names:
- `project-showcase.jpg` - Innovation Projects & Enterprise Systems
- `achievements.jpg` - Recognition, Awards & Academic Honors
- `campus-life.jpg` - University of Lusaka Campus Life
- `technology.jpg` - Technology Focus & Information Systems
- `academic-work.jpg` - Academic Excellence & Research
- `team-projects.jpg` - Collaborative Work & Leadership
- `presentations.jpg` - Academic Presentations & Conferences
- `graduation.jpg` - Graduation Journey & Milestones

### **Custom Images:**
- **Any image name** will work automatically
- The system will create appropriate titles and descriptions
- Images are automatically added to the carousel rotation
- No need to edit any code or HTML files

## 🔄 Carousel Features

### Automatic Features:
- **Auto-rotation**: Images change every 5 seconds
- **Smooth transitions**: 500ms fade between images
- **Infinite loop**: Cycles through all images continuously

### Manual Controls:
- **Navigation arrows**: Click left/right arrows to navigate
- **Dot indicators**: Click dots to jump to specific images
- **Keyboard navigation**: Use arrow keys to navigate
- **Hover pause**: Auto-rotation pauses when hovering over carousel

### Responsive Design:
- **Mobile-friendly**: Adapts to different screen sizes
- **Touch support**: Works on mobile devices
- **Accessibility**: Keyboard navigation and screen reader friendly

## 🛠️ Customization Options

If you want to modify the carousel:

### Change Auto-rotation Speed:
Edit the `autoPlayDelay` value in the JavaScript (currently 5000ms = 5 seconds)

### Add More Images:
1. Add new image slides to the HTML
2. Update the `totalSlides` count in JavaScript
3. Add corresponding dot indicators

### Modify Image Dimensions:
Change the `h-80` class in the image containers to adjust height

## 📱 Testing Your Carousel

1. Open `pages/academic_profile_hub.html` in your browser
2. Navigate to the "Portfolio Gallery" section
3. Verify that:
   - Images load correctly
   - Auto-rotation works
   - Navigation controls function
   - Images display properly on mobile

## 🆘 Troubleshooting

### Images Not Loading:
- Check file names match exactly (case-sensitive)
- Verify images are in `assets/images/` folder
- Check file permissions
- Ensure image files are not corrupted

### Carousel Not Working:
- Check browser console for JavaScript errors
- Verify all HTML elements have correct IDs
- Ensure JavaScript is enabled in browser

### Performance Issues:
- Optimize image file sizes
- Use WebP format for better compression
- Consider lazy loading for large images

---

**Note**: The carousel will work with placeholder images from Pexels if your custom images are not found, so you can test the functionality immediately!
