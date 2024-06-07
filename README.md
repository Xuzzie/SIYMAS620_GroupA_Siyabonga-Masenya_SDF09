# [SDF09] Responsive Footer Design with Tailwind CSS

I created a responsive footer for a website using Tailwind CSS. 


## Structure

The footer is divided into several sections:
1. **Subscription Form**: Allows users to subscribe to a newsletter by entering their email address and clicking the "Subscribe" button. The `input` and `button` elements are styled using Tailwind CSS classes.
2. **Quick Links**: Provides links to important pages such as Home, About Us, and Philosophy. Each link is wrapped in an `a` tag and styled accordingly.
3. **Technologies**: Lists the technologies used in the website, including HTML, CSS, and JavaScript. Similar to the Quick Links section, each technology link is wrapped in an `a` tag and styled accordingly.
4. **Logo**: Displays the logo of the website. The logo is inserted using an `img` tag with the appropriate `src` attribute pointing to the image file.

## Customization

You can customize the appearance and content of the footer by modifying the HTML code and Tailwind CSS classes. Tailwind CSS offers a wide range of utility classes to easily customize the design.

## Class Functions

The following Tailwind CSS classes are used within the HTML code:

- `container`: Sets a max-width container with padding on the sides. It ensures that content doesn't spread too wide on larger screens.
- `grid`, `grid-cols-1`, `grid-cols-2`, `grid-cols-4`: Creates a responsive grid layout with one, two, or four columns depending on the screen size.
- `gap-6`, `gap-y-10`: Sets the gap between grid items, ensuring proper spacing.
- `col-span-2`: Spans the specified number of columns within the grid.
- `px-6`, `py-12`: Adds padding to the X and Y axes respectively.
- `mx-auto`: Centers the element horizontally.
- `text-xl`, `text-2xl`: Sets the text size to extra-large and double extra-large respectively.
- `text-[#313131]`, `dark:text-white`: Sets the text color to a specific shade of grey or white, depending on the theme (light or dark).
- `font-semibold`, `font-bold`, `font-light`: Sets the font weight to semi-bold, bold, or light respectively.
- `rounded-lg`, `rounded-md`: Rounds the corners of the element, creating a rounded appearance.
- `shadow-lg`: Adds a shadow effect to the element, giving it depth and dimension.
- `bg-[#659f8f]`, `bg-[#313131]`: Sets the background color to a specific shade of green or grey, depending on the theme (light or dark).
- `border`, `border-[#a75f48]`, `border-orange-600`: Adds a border around the element with the specified color.
- `w-auto`, `w-100`, `sm:w-auto`: Sets the width of the element to automatic, 100%, or automatic on small screens and full width on larger screens.
- `h-7`: Sets the height of the element to 7 pixels.

## Preview

For a live preview of the footer, you can view the HTML file in a web browser.

