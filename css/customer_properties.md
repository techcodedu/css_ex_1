## Custom CSS Properties:

1. **body**:
    - **background-image**: This property sets two layered backgrounds. The first layer is a gradient, creating a dark overlay, while the second layer is the image.
    - **background-size: cover**: Makes the background image cover the entire container.
    - **background-repeat: no-repeat**: Ensures the background image does not repeat.
    - **background-attachment: fixed**: Makes the background image fixed with respect to the viewport.

2. **.navbar**:
    - **background-color: rgba(0, 0, 0, 0.7)**: Sets a dark background with 70% opacity. `rgba` allows us to set an opacity level.
    - **backdrop-filter: blur(10px)**: This gives the navbar a frosted glass effect.
    - **border: none** and **box-shadow: none**: These remove borders and shadows.

3. **.opacity-overlay::before**:
    - This is a pseudo-element which acts like an extra layer, creating an opacity overlay.
    - **background-color: rgba(0, 0, 0, 0.3)**: The overlay has a 30% opacity black background.

4. **.opacity-reduced**: 
    - **opacity: 0.93**: Reduces the opacity of any element this class is applied to, making it slightly transparent.

5. **.border-applied**: 
    - **border: 5px solid #fff**: Adds a white border around the element. 

## Bootstrap classes and their purpose:

1. **navbar**: Represents a navigation bar. 
   
2. **navbar-expand-lg**: This means the navbar items will be collapsed into a button (hamburger menu) on screens smaller than `lg` (large).

3. **navbar-light** and **bg-light**: These set the default theme and background of the navbar to light. However, it's overridden by the custom CSS for `.navbar`.

4. **container**: Sets a fixed-width (responsive) centered container for the content inside it.

5. **navbar-toggler**: Represents the button that shows up in smaller screens when the navbar collapses.

6. **collapse navbar-collapse**: Represents the content that gets toggled (shown/hidden) on small screens when you click the navbar-toggler.

7. **navbar-nav** and **nav-item**: Styling and behavior of the navigation items.

8. **navbar-brand**: Represents the brand logo or name on the navbar.

9. **mt-5** and **py-5**: Bootstrap utility classes for margins and padding. `mt-5` gives a top margin, and `py-5` gives padding to the top and bottom.

10. **row** and **col-lg-6**: These are part of Bootstrap's grid system. `row` defines a horizontal row, and `col-lg-6` means the column takes up half the available width on large screens.

11. **display-4** and **lead**: Typographic utility classes. `display-4` is for large headings and `lead` makes a paragraph stand out.

12. **btn** and **btn-primary btn-lg**: These style the button. `btn-primary` gives it a primary theme color, and `btn-lg` makes it larger than the default.

## Conceptual Understanding:

The custom CSS primarily serves to establish a specific design and aesthetic. The background image with the overlay gives depth and a rich feel to the website. The frosted glass effect on the navbar is a modern design trend.

Bootstrap, on the other hand, is a powerful and popular framework that helps build responsive designs easily. It provides a grid system, components like navbars, buttons, and utility classes for spacing, typography, etc., so you don’t have to write these from scratch. It ensures consistency and can considerably speed up the web development process.

By combining custom CSS with Bootstrap, you get the best of both worlds: the rapid development advantages of a framework and the uniqueness of custom styling.
