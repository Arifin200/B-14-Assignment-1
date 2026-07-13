I have an existing responsive HTML/CSS landing page called "DEVCONF 2026". Do not redesign or remove my existing Header, Hero, Speakers, Pricing, or Footer. Only add the following sections matching the current navy, blue, white, and light-gray design.

1. Venue Section (#venue)
- Two-column responsive layout.
- Left: Label "VENUE", heading "Built for Big Ideas", description, and three info rows (Date, Location, Doors Open) using semantic HTML (dl, dt, dd).
- Right: Rounded navy visual card with subtle blue gradient, circular outline, and centered "DEVCONF 2026".

2. Why Attend DEVCONF (#why)
- Dark navy rounded container.
- Left: Label, heading "Experience. Learn. Connect." ("Connect." in blue), paragraph.
- Right: 6 benefit cards in a responsive grid:
  Expert Talks, Hands-on Labs, Networking, Career Growth, Fresh Ideas, New Skills.
- Below: "What Attendees Say" with 3 testimonial cards containing 5 stars, quote, and blue job title.

3. Latest Insights (#blog)
- White section.
- Centered label, heading, subtitle.
- Three responsive blog cards:
  Conference Guide, Engineering, Networking.
- Each card contains category, title, description, and "Read article →".

Interaction:
- Benefit, testimonial, and blog cards:
  - Hover: translateY(-8px), blue shadow, highlighted border, subtle blue gradient overlay.
  - Active: slight scale down and move down.
  - Focus: lift and slightly enlarge.
  - Smooth transitions.
  - Keyboard accessible (tabindex="0").

Responsive:
- Desktop: multi-column.
- Tablet: stacked layouts and adjusted grids.
- Mobile: single-column cards.
- Use clamp() for headings and prevent horizontal scrolling.

Technical:
- HTML5 semantic elements only.
- No Bootstrap, Tailwind, JavaScript, or frameworks.
- Keep HTML in index.html and CSS in style.css.
- Reuse existing .container and CSS variables.
- Use unique classes:
  .venue-section, .venue-layout, .venue-visual,
  .why-section, .benefit-grid, .benefit-card,
  .testimonial-grid, .testimonial-card,
  .blog-section, .blog-grid, .blog-card.
- Add section IDs for navigation.
- Return complete HTML for the new sections and separate CSS only.