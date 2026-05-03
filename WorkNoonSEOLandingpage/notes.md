# WordPress Project Setup Notes

## Page Builder Used
Divi Builder was used to design and structure the landing page.

## Layout Import
To recreate the page:
1. Install WordPress
2. Install and activate the Divi Theme
3. Create a new Page (will serve as landing page)
4. Set the landing page template as "blank" then publish
5. Edit the landing page using Divi and import the file WorknoonSEOLandingPage.json

## Plugins Used
- Forminator (for contact form)
- Site Kit by Google (for analytics)
- WP-Optimize (for optimization)

## Custom Styling
Additional styling was added using custom CSS to enhance layout and UI elements such as:
- Glassmorphism (blur effect)
- Button styling
- Sections
- Preloader
- Mobile Menu

## Custom CSS Setup
Custom styling was added to enhance the design.

To apply:
1. Go to Divi → Theme Options
2. Scroll to the "Custom CSS" section
3. Paste the contents of `custom.css`

## Integration (HTML / Scripts)
Any additional scripts (if used, e.g. preloader or tracking):

To apply:
1. Go to Divi → Theme Options → Integration
2. Paste the code inside:
   - "Add code to the <head> of your blog" OR
   - "Add code to the <body>"

## Notes
- The layout JSON file contains all modules, sections, and structure used in the page
- Custom CSS and integration scripts are separated for clarity and easy reuse.