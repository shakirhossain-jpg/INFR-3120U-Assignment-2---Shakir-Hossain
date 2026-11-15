Shakir Hossain - Personal Portfolio - Assignment 2

Shared Layout Partials (header and footer)

Header(header.ejs):
Responsive navigation bar featuring a portfolio brand title, and navigation links to other site pages
utilizing Font Awesome icons for Home, Projects, Contact Me, and About Me pages. 

Footer(footer.ejs): Fixed bottom footer, dark like the header. Displays links to my GitHub and LinkedIn pages
also utilizing Font Awesome icons to make links look neat and presentable, along with copyright label.

Both implemented as partials in all page views, using "<%- include('header') %>" and "<%- include('footer') %>"
Syled using Bootstrap classes and Font Awesome


Home Page(index.ejs)

A centered card displaying my name, a short introduction of myself and the website. Along with three
bold and well-sized buttons linking to view the Projects, About Me, and Contact Me pages

Created through (--views=ejs) through router "routes/index.js"
Built utilizing Bootstrap flexbox alignment (ex. justify-content-center), card/border utilities (ex. bg-white rounded)
, and Bootstrap button classes (ex. btn btn-dark)


About Me Page(about.ejs)
Centered About Me page heading, with content split by a left and right column.

The left column has an embedded HTML video tag (<video>) with playback controls and a custom preview poster
image with an image of me as a thumbnail, both video and image found in public/images folders.

The right column has a smaller " Who am I " title with text, providing an extended introduction of myself about my background,
what program I am enrolled in, my hobbies, and a list of career/academic goals in the near future.

Created and rendered via /about route in routes/index.js. Structured with Bootstrap container and spacing utilities (my-4. mt-5)
to provide margins for even spacing and centering. Utilized <video> and <source> tags to link the assets in the public folder.



Projects Page(projects.ejs)

Centered Projects page heading with four boxes showcasing four different projects I have done. Split in groups of two
displayed through left and right columns. Utilizing Font Awesome icons in the titles for each box.

Created and rendered via /projects route in routes/index.js using Bootstrap container layout and Font Awesome icons
to provide proper placement in center of page along with customized styling of columns in universal style.css file



Contact Me Page(contact.ejs)

Centered Contact Me heading with a prompt indicating the use of an interactive contact form with four simple fields.
Fields for First Name, Last Name, Email Address, and Message box. Included with reset and submit buttons

Created and rendered via /contact route in routes/index.js, built using Boostrap grid functions to center field elements
along with Bootstrap form controls to provide a suited style for the page. 


Global Styling with (style.css)

Applied across all pages by linking /stylesheeets/style.css in the <head> section to provide the 
left/right column customizations, the clear class customizations, box class styling (in projects page) and the 
universal beige background colour across all pages.


