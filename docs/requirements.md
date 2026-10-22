# Next Stride — Landing Page Requirements

## 1. Project overview

Next Stride is a fictional running shoe store.

This educational project promotes a Black Friday campaign through
a responsive landing page built with HTML and CSS.

The page helps visitors discover three promotional products and
navigate between the offers, benefits, and contact sections.

## 2. Technologies and constraints

- HTML5 for semantic structure and content.
- CSS3 for styling, layout, and responsive behavior.
- Git and GitHub for version control.
- GitHub Pages for hosting.
- Page language: English.
- Currency: USD.
- No JavaScript, frameworks, backend, or database.

The page does not include a shopping cart, checkout, authentication,
functional contact form, product filtering, or dynamic countdown.

## 3. Header

The header must display:

- The store name: Next Stride.
- Navigation links: Offers, Benefits, and Contact.

The store name must link to `#home`.

Navigation destinations:

- Offers → `#offers`
- Benefits → `#benefits`
- Contact → `#contact`

The navigation must remain visible on mobile using wrapping or
a stacked layout. A collapsible menu is not required.

## 4. Hero section

Section ID: `home`

The hero must contain:

- Campaign label: Black Friday.
- Main heading: Step into Black Friday.
- Supporting text: Your next stride starts here. Save up to 50%
  on selected running shoes.
- A prominent link labeled "View offers", leading to `#offers`.

The page must have one main `h1`, used for the hero heading.

Any hero image must support the running theme and keep the text readable.

## 5. Offers section

Section ID: `offers`

Section heading: Find your next running shoes.

Display three fictional products.

### Stride Daily

- Description: A versatile running shoe for everyday training.
- Original price: $100.00.
- Discounted price: $70.00.
- Discount: 30%.
- Image: A product image representing Stride Daily.
- Image alternative: Describe the actual shoe shown in the image.

### Stride Tempo

- Description: A lightweight running shoe for faster training sessions.
- Original price: $140.00.
- Discounted price: $84.00.
- Discount: 40%.
- Image: A product image representing Stride Tempo.
- Image alternative: Describe the actual shoe shown in the image.

### Stride Distance

- Description: A cushioned running shoe for comfortable longer runs.
- Original price: $180.00.
- Discounted price: $90.00.
- Discount: 50%.
- Image: A product image representing Stride Distance.
- Image alternative: Describe the actual shoe shown in the image.

### Product presentation

Each product must display:

- Product image.
- Product name.
- Short description.
- Clearly labeled original and discounted prices.
- Discount percentage.

Product names must use `h3` headings beneath the section's `h2`.

Products are informational cards. They do not include purchase buttons
or links to unavailable product pages.

A visible notice must explain that the products and prices are fictional.

## 6. Benefits section

Section ID: `benefits`

Section heading: Why choose Next Stride?

Display three fictional store benefits:

1. Free delivery
   Free standard delivery on orders over $100.

2. Easy exchanges
   Exchanges within 30 days, subject to the fictional store policy.

3. Flexible payments
   Multiple payment options for a convenient shopping experience.

These benefits are demonstration content. No delivery, exchange,
or payment functionality is implemented.

## 7. Footer and contact

Section ID: `contact`

The footer must include:

- The store name: Next Stride.
- A contact label and the fictional address:
  hello@nextstride.example.
- A clear indication that the address is for demonstration only.
- A "Back to top" link leading to `#home`.
- The notice:
  "Educational project. Next Stride, its products, prices, and
  promotional benefits are fictional. No purchases can be made."

Display the fictional email address as plain text.

Do not include social media links without real destinations.

## 8. Link behavior

All navigation and call-to-action links must have valid destinations:

| Link        | Destination |
| ----------- | ----------- |
| Next Stride | #home       |
| Offers      | #offers     |
| Benefits    | #benefits   |
| Contact     | #contact    |
| View offers | #offers     |
| Back to top | #home       |

Use HTML anchors for navigation.

Do not use empty links or `href="#"` placeholders.

## 9. Responsive layout

### Mobile

- Support viewport widths starting at 320px.
- Stack product cards and benefits vertically.
- Allow navigation links to wrap or stack.
- Keep text readable without zooming.
- Keep images within their containers.
- Avoid horizontal page scrolling.

### Desktop

- Display the three product cards in a three-column layout
  when sufficient space is available.
- Display benefits in a row when space permits.
- Use a centered content container with a maximum width.
- Maintain consistent spacing and image proportions.

### General

- Use CSS Flexbox or Grid for layout.
- Use media queries to adapt the layout.
- Choose breakpoints based on content fit.
- Include the viewport meta tag in the HTML.

## 10. Accessibility

- Set the document language to English using `lang="en"`.
- Use semantic elements such as `header`, `nav`, `main`,
  `section`, `article`, and `footer` where appropriate.
- Give the main navigation an accessible label.
- Use one `h1`, section `h2` headings, and product `h3` headings.
- Provide meaningful alternative text for product images.
- Use empty alternative text for purely decorative images.
- Keep essential text in HTML rather than embedding it in images.
- Maintain readable text contrast:
  at least 4.5:1 for normal text and 3:1 for large text.
- Ensure all links work with keyboard navigation.
- Provide a clearly visible keyboard focus indicator.
- Do not rely on color alone to communicate discounts or link states.
- Ensure content remains usable at 200% browser zoom.

## 11. Assets and paths

- Store images in the `images` folder.
- Use images that are permitted for use and record attribution
  in the README when required.
- Use relative paths for stylesheets and images.
- Match filename capitalization exactly.
- Avoid local computer paths.
- Compress images to limit unnecessary page weight.

## 12. Acceptance checklist

- [ ] All five planned sections are present.
- [ ] The page content is in English.
- [ ] All three products show the required information.
- [ ] Discount calculations match the displayed prices.
- [ ] Every navigation link reaches the correct section.
- [ ] The layout works at mobile and desktop widths.
- [ ] No horizontal scrolling occurs at 320px.
- [ ] Images load and have appropriate alternative text.
- [ ] Heading levels follow a logical hierarchy.
- [ ] Links are keyboard-accessible with visible focus.
- [ ] Text meets the defined contrast requirements.
- [ ] The page remains usable at 200% zoom.
- [ ] Fictional content and the educational purpose are disclosed.
- [ ] The page works using HTML and CSS only.
- [ ] Stylesheets and images load correctly on GitHub Pages.
