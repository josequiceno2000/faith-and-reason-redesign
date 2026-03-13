# Faith and Reason Redesign

## The Objective:
To redesign the Faith & Reason landing page to improve mobile responsiveness and ADA compliance while sticking to the fell of Franciscan University.

## Performance Optimization:
- **Head Optimization**
    - *Doctype* -- added Doctype declaration to avoid "Quirks Mode".
    - *Viewport* -- changed scale="1" to initial-scale=1.0 to ensure correct sizing across mobile devices.
    - *Connection Priming* -- moved preconnect tags to top of file to reduce total blocking time. 
    - *Global Tracking Scripts* -- mark all google tag manager script tags with defer.
- **Images** -- converted all to WebP for faster loading
- **CSS** -- minimized for speed and quality factors
- **Bottom Internal Script** -- wrapped custom logic (setSeason, getQueryParam) in event listener so it fires after HTML is parsed.

## Accessibility Features
- **Keyboard Navigation** -- 
- **Color Contrast Ratios** --
- **ARIA Landmarks** -- 
- **Skip to Content Link** -- added a skip link to allow keyboard users to go jump from the menu straight into the main content.

## WordPress Readiness
The codebase is modeled off of WordPress standards, meaning it uses modular components which were tailor-designed for porting into a custom WordPress theme.