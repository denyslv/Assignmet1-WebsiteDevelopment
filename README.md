# Website Design Report

This project outlines the design choices for a website that adapts to both light and dark modes. It details the layout, colour scheme, font styles, and responsive design techniques used to create a consistent and user-friendly experience. The website consists of four main pages: Home, Education, Hobbies, and Contact, and it is optimised for readability across different screen sizes.

## Layout

- The website consists of *4 pages*: Home, Education, Hobbies, and Contact.  
- Each page shares a similar *header*, navigation menu, main section, and no footer.  
- The navigation bar is *centred* and uses a *flexbox layout* to evenly space out the menu items.  
- Content is *centre-aligned* for better readability.  
- *Tables* are used in the Education page to display structured information about past studies.  
- *Images and icons* are placed in relevant sections to aid the content.  
- Contact links are presented in a *flexbox grid*, making them responsive.  

---

## Colour Scheme

- The default theme is dark mode, with a <span style="color:#121212">dark background</span> (#121212) and white text.  
- The *header background* is <span style="color:#3a1daa">purple</span> (#3a1daa), creating great contrast.  
- Table has a lighter <span style="color:#181818">grey background</span> (#181818) to better separate it from background.  
- A *light mode* alternative is available when the user’s system preference is set to light mode:  
  - The background changes to <span style="color:#aaaaaa">light grey</span> (#dddddd), and text switches to *black*.  
  - Tables and headers have lighter shades for better visibility.  
  - The *SETU logo* dynamically switches between light and dark versions depending on the theme.  

---

## Font Styles and Sizes

- The website uses a *sans-serif font* to ensure good readability.  
- :arrow-down-big-small-regular: *Text sizes* are based on viewport height (vh), to ensure good scalability across different screen sizes.  
- :text-regular: The *main content text* uses a size of *1.8vh*.  
- :ellipsis-solid: *Navigation menu items* are larger *2.3vh* to ensure they stand out.  
- :table-cells-large-regular: *Table text* is set to *2vh*.  
- :address-card-solid: *Contact icon* figcaptions are smaller (*1.5vh*) to fit well with the icons.  

---

## Responsive Design Choices

- The website adjusts based on screen size using *media queries*:  
  - If the screen width is *less than 720px*, images and icons reduce in size to improve readability.  
  - The navigation menu remains flexible and has wrap enabled to fit smaller screens.  
  - The table maintains its structure on different screen sizes.  

---

## Interactive Elements

- *Hover Effects*: Contact icons slightly *enlarge* when hovered over.  
- *Dynamic Logo Switching*: CSS applies an invert filter to the SETU logo to make it visible on both light and dark backgrounds.
