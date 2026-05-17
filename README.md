 # Little Chefs Academy 👨‍🍳

Little Chefs Academy is a front-end website for a children's cooking
school offering classes for kids aged 4–12. The site allows parents
to browse available classes, watch a preview video, and register
their child online.

## Table of Contents

- [User Stories](#user-stories)
- [Features](#features)
- [Design](#design)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

<img width="1047" height="452" alt="top of the page little chefA" src="https://github.com/user-attachments/assets/3fac2439-7052-44b9-abe3-2b6781244cf3" />

## User Stories

- As a parent, I want to see what cooking classes are available
  so I can choose one for my child.
- As a parent, I want to register my child for a class online
  so I don't have to call.
- As a visitor, I want to watch a video preview so I can see
  the environment before enrolling.
- As a mobile user, I want to navigate the site easily on my
  phone so I can browse on the go.


## Features

### Navigation Bar
- Sticky navigation visible at all times.
- Responsive hamburger menu on mobile devices.
- Links to all sections of the page.
<img width="1056" height="628" alt="class-cards-chef-academy" src="https://github.com/user-attachments/assets/c96a44ca-7b02-46f3-9fa1-610a1a272a3f" />
### Hero Section
- Clear headline and call-to-action button.
- Immediately communicates the site's purpose.

### About Section
- Brief introduction to the academy's mission and values.

### Class Cards
- Three class options displayed in a responsive grid.
- Each card includes an image, description, price, and schedule.

### Why Choose Us
- Four key selling points displayed in a feature grid.

### Video Section
- Embedded HTML5 video with full user controls.
- Responsive sizing across all devices.
<img width="953" height="657" alt="cooking video section " src="https://github.com/user-attachments/assets/3a53bca2-439a-42cb-b751-1477233f80c8" />

### Registration Form
- Allows parents to register their child for a specific class.
- Includes validation via required fields.
- Submits to Code Institute's formdump for testing.

### Testimonials
- Parent quotes that build trust and credibility.
<img width="1040" height="155" alt="registration section chefAcamy" src="https://github.com/user-attachments/assets/dcd4ffd3-e07b-404b-a327-6fdf91d6a735" />
### Footer
- Contact details, address, and social media links.
- All external links open in new tabs.
 
<img width="707" height="131" alt="footer littlechefacademy" src="https://github.com/user-attachments/assets/c7812778-d922-4652-a8e7-6e40df53d3d6" />

## Design

### Color Scheme
| Color           | Hex       | Usage                  |
|-----------------|-----------|------------------------|
| Dark Orange     | #FF8C00   | Accents, borders, CTAs |
| Gold            | #FFD700   | Headings, highlights   |
| Dark Blue-Grey  | #2C3E50   | Background             |
| White           | #FFFFFF   | Body text              |
| Lighter Grey    | #34495E   | Card backgrounds       |

### Typography
- **Verdana** (system font) — chosen for readability and
  accessibility, especially for younger audiences.

## Technologies Used

- **HTML5** — semantic structure
- **CSS3** — styling, Flexbox, Grid, media queries
- **Git** — version control
- **GitHub** — repository hosting
- **GitHub Pages** — deployment
- **W3C Validator** — HTML validation
- **Jigsaw Validator** — CSS validation
## Testing

### HTML Validation (W3C)
All pages pass with no errors or warnings.

![W3C validation result](assets/images/screenshots/w3c-validation.png)

### CSS Validation (Jigsaw)
Stylesheet passes with no errors.

![Jigsaw validation result](assets/images/screenshots/jigsaw-validation.png)

### Manual Testing

| Feature           | Test Performed           | Expected Result              | Actual Result    | Pass |
|-------------------|--------------------------|------------------------------|------------------|------|
| Nav links         | Click each nav link      | Scrolls to correct section   | Works correctly  | ✅   |
| Hamburger menu    | Tap icon on mobile       | Menu expands/collapses       | Works correctly  | ✅   |
| CTA button        | Click "View Our Classes" | Scrolls to classes section   | Works correctly  | ✅   |
| Video controls    | Click play/pause/volume  | Video responds to controls   | Works correctly  | ✅   |
| Form submission   | Fill form and submit     | Redirects to formdump        | Works correctly  | ✅   |
| Form reset        | Click reset button       | All fields clear             | Works correctly  | ✅   |
| Social links      | Click each footer link   | Opens in new tab             | Works correctly  | ✅   |
| Responsive layout | Resize browser/use phone | Layout adapts, no overflow   | Works correctly  | ✅   |

### Responsiveness Testing

| Device / Width      | Result                         |
|----------------------|--------------------------------|
| Desktop (1920px)     | Full layout, grid displays     |
| Tablet (768px)       | Hamburger menu activates       |
| Mobile (375px)       | Single column, all accessible  |

### Accessibility
- Lighthouse accessibility score: [insert score + screenshot]
- All images have descriptive alt text.
- Focus states visible on all interactive elements.
- Sufficient color contrast (WCAG AA compliant).

---

## Deployment

### GitHub Pages

This site was deployed using GitHub Pages. The steps are:

1. Log in to [GitHub](https://github.com/).
2. Navigate to the repository:
3. Click **Settings** in the repository menu.
4. In the left sidebar, click **Pages**.
5. Under **Source**, select **main** branch and **/ (root)** folder.
6. Click **Save**.
7. Wait 1–2 minutes. The live URL will appear at the top of the
   Pages section.

   ## Credits

### Content
- All text content was written by [Your Name].

### Media
- `cookies-deco-kids.jpg` —[https://unsplash.com/]
- `kids-making-pizza.jpg` — [https://unsplash.com/]
- `smoothies-for-kids.jpg` — [https://unsplash.com/]
- `kids-cooking.mp4` — [https://unsplash.com/]
### Code
- Form action URL: [Code Institute formdump service](https://formdump.codeinstitute.net/)
- CSS hamburger menu technique

### Acknowledgements
-github tutorials. 



