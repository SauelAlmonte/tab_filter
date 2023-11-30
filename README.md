# Tab Filter / Tech Conferences Website

This project is a simple website for exploring and filtering tech conferences based on their types. It includes HTML, CSS, and JavaScript to create an interactive and visually appealing experience.

## Table of Contents

- [Tab Filter / Tech Conferences Website](#tab-filter--tech-conferences-website)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Features](#features)
- [CSS Styles Explanation](#css-styles-explanation)
  - [Box Sizing and Reset](#box-sizing-and-reset)
  - [Visually Hidden Class](#visually-hidden-class)
  - [Layout and Grid](#layout-and-grid)
  - [Primary Header and Navigation](#primary-header-and-navigation)
  - [Breadcrumbs](#breadcrumbs)
  - [Conference List and Filters](#conference-list-and-filters)
  - [Sidebar](#sidebar)
- [JavaScript Code Explanation](#javascript-code-explanation)
  - [Event Transition Names](#event-transition-names)
  - [Filter Buttons](#filter-buttons)
    - [Update Active Button Function](#update-active-button-function)
    - [Filter Events Function](#filter-events-function)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)

## Description

The website provides information about upcoming tech conferences and allows users to filter conferences by type (Frontend, Backend, Fullstack). It includes a responsive design for a seamless experience on various devices.

## Features

- **Navigation:** The website has a clear navigation structure with a primary header and breadcrumb navigation for easy exploration.

- **Filtering:** Users can filter conferences by type using the interactive filter buttons.

- **Conference List:** A list of upcoming conferences is displayed, each with its date, category, and name.

- **Sidebar:** The sidebar provides additional information about different topics, enhancing user engagement.

- **Footer:** The footer includes copyright information.

# CSS Styles Explanation

## Box Sizing and Reset

- Ensures consistent box sizing for all elements (including padding and borders).
- Resets margins for all elements to zero.
- Sets the default font for the entire document as the system UI font.

## Visually Hidden Class

- Defines a class (`.visually-hidden`) to visually hide elements while maintaining accessibility for screen readers.

## Layout and Grid

- Utilizes CSS Grid for layout, creating a grid structure with specific column placements.
- Defines styles for full-width elements within the content grid.

## Primary Header and Navigation

- Styles the primary header and its layout with flex properties for spacing and alignment.
- Defines styles for the primary navigation, including list styling, spacing, and link styles.

## Breadcrumbs

- Styles breadcrumb navigation for a clean and visually appealing display.
- Defines styles for breadcrumb links, including hover and focus states.

## Conference List and Filters

- Styles the list of conferences and filter buttons.
- Uses flexbox for responsive design within the main content area.
- Defines button styles for the filter buttons, with a distinct appearance for the active filter.

## Sidebar

- Styles the sidebar with padding, border, and border-radius for a visually appealing appearance.
- Utilizes flex properties for alignment and spacing of sidebar content.

# JavaScript Code Explanation

## Event Transition Names

- Assigns unique transition names (`viewTransitionName`) to each conference element for enhanced view transitions.

## Filter Buttons

- Event listeners attached to each filter button within the "filter" container.
- Clicking a button triggers the following actions:

### Update Active Button Function

- Manages the active state of filter buttons.
- Ensures the currently active button is visually highlighted.

### Filter Events Function

- Filters and displays conferences based on the selected category.
- Iterates through conferences, retrieves their categories, and shows/hides them accordingly.

## Usage

1. Clone the repository.

   ```bash
   git clone https://github.com/your-username/tech-conferences.git
   ```

2. Open the `index.html` file in your preferred web browser.

3. Explore and filter conferences based on your interests.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes and commit them.

   ```bash
   git commit -m "Add your commit message"
   ```

4. Push to the branch.

   ```bash
   git push origin feature/your-feature
   ```

5. Open a pull request on GitHub.

## License

This project is licensed under the [MIT License](LICENSE).
