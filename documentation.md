# GCTU IT Learning Hub - Website Documentation

## Project Overview
This project involves the development of a multi-page website for the "GCTU IT Learning Hub". The site serves as an educational resource for students, providing information about courses, admissions, and the department.

## File Structure
The project consists of the following files:
*   `index.html`: The homepage featuring a hero section and call-to-action.
*   `about.html`: Information about the mission and vision.
*   `courses.html`: A list of available modules presented in a table.
*   `admissions.html`: Requirements and application process.
*   `contact.html`: A contact form and address details.
*   `style.css`: The central stylesheet managing the visual presentation.

## Design & Development Features

### 1. Responsive Layout
*   **Viewport Meta Tag**: Added to all HTML files to ensure proper scaling on mobile devices.
*   **Media Queries**: Implemented in `style.css` (at `max-width: 768px`) to adjust the navigation bar from a horizontal row to a vertical stack and to make tables scrollable horizontally.

### 2. Navigation
*   **Consistent Bar**: A unified navigation bar across all pages.
*   **Active State**: The current page is highlighted in the navigation menu using the `.active` class, providing visual feedback to the user.

### 3. UI Enhancements
*   **Hero Sections**: A reusable `.hero` class was created for the homepage to display introductory content prominently.
*   **Tables**: The course list is styled with alternating row colors and a distinct header for better readability.
*   **Forms**: The contact form is styled as a card with improved input spacing and a "Send Message" button that changes color on hover.
*   **Cards**: Sections in the "About" page and lists in the "Admissions" page are styled as cards with shadow effects and accent borders.

## Development Process
1.  **HTML Skeleton**: Created the basic structure for all five pages.
2.  **CSS Reset & Base**: Applied basic reset rules and typography settings.
3.  **Navigation Logic**: Implemented the flexbox-based menu and added the active class logic.
4.  **Responsiveness**: Added media queries to handle mobile viewports.
5.  **Refinement**: Enhanced specific elements like tables, forms, and lists to improve the overall user experience (UX).

## Credits
Developed by Sylvester Anneh Yaw Otoo (ID: 1696582104).