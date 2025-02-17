# Dev-Test


# **Custom Section for Shopify Theme**
### **Live Demo:** [View Here](https://sanyakapoor05.github.io/Dev-Test/)

## **1. Approach**
I developed a custom Shopify section based on the Figma design provided. The section includes dynamic elements such as a circular path with numbering, custom typography, and image placements. The implementation was done using **HTML, CSS, and JavaScript** to ensure flexibility within Shopify’s theme editor.


### **Key Steps in Development:**
- **Understanding the Design**  
   - Extracted desktop and mobile layout details from the provided Figma file.  
   - Ensured a **mobile-first approach** for better adaptability.
- **Font Adjustments:** The font size from Figma was too large on the web version, so I manually adjusted sizes for better visual balance.
- **SVG Path for Circular Numbering:** Since I hadn’t created a curved path with numbering before, I researched SVG techniques and used `path` with `textPath` to achieve the effect.
- **Responsive Design:** Ensured the section adapts well to different screen sizes using CSS Flexbox and media queries.
- **Image Placement:** Initially attempted to create a water splash effect dynamically but faced challenges. Instead, using an exported image from Figma would be a more practical solution.

---

## **2. Challenges & Solutions**
### **1. Font Size Discrepancy**
**Challenge:** The fonts from Figma appeared larger on the live website.  
**Solution:** Reduced the font size `px` to ensure responsive scaling.

### **2. Creating a Circular Path with Numbering**
**Challenge:** Never created a circular path with numbers before.  
**Solution:** Researched SVG paths and used `textPath` with an `SVG <path>` to create a curved numbering effect.

### **3. Water Splash Effect**
**Challenge:** Couldn’t replicate the water splash outside the image dynamically.  
**Solution:** The best approach would be to use an exported image from Figma rather than attempting a complex CSS/JS animation.

### **4. Shopify Theme Compatibility**
**Challenge:** Ensuring the section works within Shopify’s Liquid template structure.  
**Solution:** Used Shopify’s `sections` structure to make the component editable in the Theme Editor.

