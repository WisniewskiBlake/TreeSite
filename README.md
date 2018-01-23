# TreeSite-js-bootstrap-jquery
Large website I built to learn boostrap and enhance JS/JQuery skills. All fonts used were downloaded and accessed via css @font-face. All widget pictures come from Fontawesome.com and the main pictures comes from sitebuilderreport.com. Inspiration drawn from onepagelove.com, a site dedicated to displaying one page websites.

In the first section, a row is split into 12 columns(can't be more than 12 columns per row), with two divs; one holding 9 columns and one holding 3 columns. The main background image is inserted into a section with the id of cover. The background is not integrated using bootstrap so it does not get adjusted no matter what size the screen. The button in the first row is styled using special properties such as hover, focus, and active. The navbar is next to be coded. All the links are placed inside a list class. A searchbar is created inside of a form along with a button.

In the second section, a row is split into 12 columns with 4 divs each holding 3 columns. The 4 divs are integrated using bootstrap so they become responsive when the page is resized.

The third section is the Timeline section. The three fading textboxs are created using three lists. Inside these lists, various divs are created to store timeline info. One list takes a class name of time-line-inverted, this is because one of the lists needs to appear on the right, thus, it is styled differently than its siblings on the left. An important note to make here is that the lists appear one after the other on the left or right of a line, which is done by use of the :before and :after attributes in css. Absolute positioning is used here as it is a very powerful attribute when attempting to make certain elements resizeable.
The @media queries in css file of treesite resize the website to make it available on all platforms including any res on Windows, tablet, or mobile phone. The bootstrap is edited via bootstrap.min file where I take a default boostrap file and change values until the desired effect is produced in the browser.
