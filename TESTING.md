# Testing

## Manual Testing

### Navigation

| Feature         | Action        | Expected Result                   | Status |
| --------------- | ------------- | --------------------------------- | ------ |
| Navigation menu | Click Home    | User is taken to the home page    | Pass   |
| Navigation menu | Click Explore | User is taken to the explore page | Pass   |
| Navigation menu | Click Contact | User is taken to the contact page | Pass   |

---

### Home Page

| Feature           | Action                | Expected Result                               | Status |
| ----------------- | --------------------- | --------------------------------------------- | ------ |
| Hero section      | Open homepage         | Hero image and welcome text display correctly | Pass   |
| Responsive layout | Resize browser window | Content adapts correctly on smaller screens   | Pass   |

---

### Explore Page

| Feature           | Action                | Expected Result                            | Status |
| ----------------- | --------------------- | ------------------------------------------ | ------ |
| Desert section    | Open explore page     | Desert images and text display correctly   | Pass   |
| Souk section      | Scroll down page      | Souk images and text display correctly     | Pass   |
| Cuisine section   | Scroll down page      | Cuisine images and text display correctly  | Pass   |
| Hover effects     | Hover over images     | Images slightly zoom on hover              | Pass   |
| Responsive layout | Open on mobile/tablet | Images stack vertically on smaller screens | Pass   |

---

### Contact Page

| Feature           | Action                       | Expected Result                              | Status |
| ----------------- | ---------------------------- | -------------------------------------------- | ------ |
| Contact form      | Enter information and submit | Success message appears                      | Pass   |
| Form reset        | Submit form                  | Form clears after submission                 | Pass   |
| Responsive layout | Open on mobile/tablet        | Layout adjusts correctly for smaller screens | Pass   |

---

## Validator Testing

### HTML

All HTML pages were tested using the official W3C HTML Validator.

- No major errors were found.
- Minor warnings were related to semantic structure and were reviewed.

### CSS

The CSS stylesheet was tested using the official W3C CSS Validator.

- No errors were found in the final CSS code.

---

## Lighthouse Testing

Lighthouse testing was performed in Google Chrome DevTools.

The website achieved good results in:

- Performance
- Accessibility
- Best Practices
- SEO

Images were compressed to improve loading performance.

---

## Browser Compatibility

The website was tested and works correctly on:

- Google Chrome
- Microsoft Edge
- Samsung Internet Browser

The website was also tested on different screen sizes including:

- Mobile devices
- Tablets
- Desktop screens

---

## Bugs Found and Fixed

| Bug                                          | Fix                                        |
| -------------------------------------------- | ------------------------------------------ |
| Some images did not display on GitHub Pages  | Renamed image files to lowercase filenames |
| Mobile layout on contact page was broken     | Added responsive media queries             |
| Images were too large and slowed performance | Compressed image sizes                     |
| GitHub Pages returned 404 errors for images  | Corrected file paths and filename casing   |

---

## Deployment

The project was deployed using GitHub Pages.

### Steps for deployment

1. Open the GitHub repository.
2. Navigate to the **Settings** tab.
3. Select **Pages** from the left-hand menu.
4. Under **Branch**, select:
   - `main`
   - `/root`
5. Click **Save**.
6. The live website link is generated after deployment.

Live link:
https://monia07.github.io/Marrakech-travel-guide/

---

## Remaining Bugs

- No known bugs remaining.

---

## Credits

### Content

- Text content was written by the developer for educational purposes.

### Media

- Images were sourced from Unsplash and personal image edits.

### Technologies Used

- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages
- Visual Studio Code
- Google Fonts
