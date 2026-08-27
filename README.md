# Week 1 Task Report — Transforming Wireframes into Static Web Pages

## 1. Project Overview

The objective of this Week 1 task was to convert the supplied internship-task wireframe into a functional static webpage using HTML and CSS. The implementation recreates the two-column desktop layout, orange gradient header, task-information section, submission form, typography, spacing, borders, buttons, and responsive behavior shown in the reference design.

## 2. Design Analysis

The wireframe is divided into two main areas. The top section contains an orange gradient internship header with breadcrumb navigation, the internship title, start and end dates, and duration. Below the header is a rounded white content card divided into a task-details column and a submission column.

The left side presents the Week 1 task information using a numbered badge, headings, paragraphs, and unordered lists. The right side contains the work-submission form, including a file upload control, GitHub URL field, an informational notice, a report-description textarea, and a submit button.

## 3. HTML Structure

Semantic HTML elements were used to keep the document organized and accessible. The page uses `header` for the internship banner, `main` for the primary content, `section` elements for the task and submission areas, and a `form` for user inputs. Heading levels are used to establish a clear content hierarchy.

The HTML also includes labels associated with form controls and descriptive placeholders where appropriate.

## 4. CSS and Layout Strategy

CSS Grid is used for the main two-column desktop layout. This allows the task description and submission form to occupy equal-width columns while maintaining a clean vertical divider. Flexbox is used for smaller component layouts such as the breadcrumb, metadata row, task heading, and file input.

The design uses an orange gradient as the primary visual accent. Rounded corners, subtle borders, shadows, spacing, and typography were added to reproduce the visual hierarchy of the reference wireframe.

CSS custom properties were used for frequently repeated colors such as the orange accent, text colors, muted text, and borders. This makes the stylesheet easier to maintain.

## 5. Responsive Design

Responsive media queries were added at 760px and 480px breakpoints.

On smaller screens, the two-column card changes into a single-column layout. The vertical divider becomes a horizontal divider, metadata items stack vertically, heading sizes are reduced, and the file-upload control changes to a vertical arrangement. These changes prevent horizontal overflow and keep the form usable on mobile devices.

## 6. Challenges and Solutions

One challenge was maintaining the visual balance between the two desktop columns while keeping the page readable on smaller screens. CSS Grid was selected for the primary layout because it provides predictable column sizing.

Another challenge was recreating the compact form controls and notice box without relying on fixed page dimensions. Relative widths, padding, minimum heights, and responsive breakpoints were used instead of hard-coded positioning.

The orange header also contains subtle decorative elements. These were recreated using CSS gradients, radial patterns, pseudo-elements, and translucent circular shapes rather than using additional image assets.

## 7. Testing Approach

The page should be tested at desktop, tablet, and mobile widths. Important checks include:

- Header alignment and spacing
- Two-column desktop layout
- Single-column mobile layout
- Form control sizing
- Text wrapping
- Button visibility
- Absence of horizontal scrolling
- File input interaction
- Overall visual consistency with the supplied wireframe

## 8. Conclusion

The final implementation provides a clean, semantic, responsive static webpage based on the supplied wireframe. The project demonstrates fundamental frontend skills including semantic HTML, CSS Grid, Flexbox, responsive media queries, reusable CSS variables, form styling, and basic JavaScript interaction for the file-selection label.
