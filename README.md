# Description

This is an assignment to build a responsive ecommerce web page. Nav and product container div will use flexbox. Sidebar/aside is a module that changes layout and location based on window size. Submitting the mailing list signup form results in user feedback on the page. Clicking a product's “add to cart” or “remove from cart” button updates cart count at top.

Students may use the provided mockups to guide their design to whatever extent they like. Matching the mockups is not required.

## Provided Materials

  - basic HTML and CSS
  - JSON list of products in script.js file
  - reset.css
  - images for all products
  - suggested design mockups

## Assignments

Lesson 03:

  - Make design decisions about how you'd like your site to look. You can use the provided mockups to guide your design to whatever extent you'd like- feel free to implement them exactly or make up your own design completely.
  - Code basic CSS for page. `reset.css` file should remain as it is. `main.css` file can be added to, changed, or completely redone.
  - `nav ul` and `.item-container` elements should be styled as flexbox containers. Implement a responsive grid system of your own design, or use a library, or don't use a grid at all. Be sure all important size values are proportional (em, rem, %).
  - We'll continue working on the CSS for this project throughout the course, in particular making it more responsive. The styling does not have to be perfect after this assignment. It's fine to change or add to the HTML as necessary for your styling.

Lesson 05:

  - Write a JS form handler function to be triggered on form submit. It should print to the console a friendly message that includes the value of the form element with name "email". Something like "Thanks for signing up for our mailing list, bobross@example.com!"

Lesson 06:

  - Serve appropriately sized images. Use GIMP or another photo-editing program to resize all images to more reasonable, consistent dimensions. This includes product images, the logo, and any background or other images you've included.

Lesson 07:

  - Write Javascript function that toggles the inclusion of a product in the "cart".
  - Add/edit HTML as necessary to trigger the function on click of a button for each product.

Lesson 08:

  - Write CSS that uses media queries to change layouts/style based on device size. There shoud be at least one obvious layout change in addition to elements fluidly changing width.
  - Finish styling the page.

Lesson 09:

  - Write Javascript that causes the total number of items in the cart to display next to the cart icon when that total changes.
  - Write Javascript that displays the friendly message on form submit in the page, not in the console.
  - Update the HTML and CSS as necessary to accomodate these changes.
  - Update the Testing section of this README with your own information.

*Extra Challenge*: Incorporate unit tests with [Qunit](https://qunitjs.com/).

*Extra Challenge*: Code a popup that toggles between hidden and displayed when user clicks on cart icon. It should show information about items in the cart (maybe list of their names, but up to you).

*Extra Challenge*: Serve appropriately sized images for user's device. Create multiple sizes of each image, and serve the appropriate one using the `srcset` and `sizes` attributes on the `img` tags. This will require naming all of the images consistently, e.g. "ombre-infinity400.jpg", "ombre-infinity200.jpg". [More](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) about [srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

*Extra Challenge*: Use browser storage to save details about a user's cart so when they revisit the page, it's in the same state as when they left it. [More about browser storage](https://www.w3schools.com/html/html5_webstorage.asp)

*Extra Challenge*: Dynamically generate the HTML for product listings from the JSON objects in script.js.

## Requirements

  - Site layout looks good on all sizes of devices. At a minimum, elements are proportionally styled and aside element changes location and layout at different screen sizes. This should be tested using a variety of devices and at least one online browser compatiblity testing tool.
  - Nav and product container elements are styled using flexbox.
  - Appropriately sized images are served.
  - User can add and remove items from their cart, which changes cart count number at top of page.
  - This README is updated to include information about the testing steps taken to ensure site quality.
  - Site is live on GH Pages hosting.

## Grading
Each weekly assignment will be graded independently. There will not be a final grade for the entire project.

## Testing Part I
[update this section with information about the testing steps you took to ensure site quality]

-Used both Responsive WEB Design Checker and Web Page Test to test site both on various devices and on various web browsers in various locations around the world. 

-I tested on 15 devices total, these varied both in size and operating systems. I tested on sizes that  mirrorred the breakpoints of the webiste after using the dev tools in Chrome. 

Laptops/Desktops

24" Desktop 1920x1200 - 1st row and 2nr row lose margin formating, all modules next to each other
19" Deskstop 1600x900 - 2nd row, all modules together 
15" Notebook 1366x768 - Right side modules extend beyond border
13" Notebook 1024x800 -Module spacing incosistent
10" Notebook 1024x600 - No issues

Tablets

Apple ipad mini 768x1024 Last line in last module, the rating,  gets cut off
Apple ipad retina 768x1024 Last line in last module, the rating,  gets cut off
Amazon Kindle Fire 768x1024 Last line in last module, the rating,  gets cut off
Amazon Kindle Fire HD 768x1024 Last line in last module, the rating,  gets cut off
Nexus 9 1024x768 - Second line products have no spaces between them
Samsung Galaxy Tab 10 800x1280 - Items in rows too close together.

Smartphones/Cellphones
IOS Operating Systems
Apple iphone 3/4/4s 320x480 - Last item, cut off (rating)
Apple iphone 5/5s 320x568 - Last item, cut off (rating)
Apple iphone 6/6s/7 375x667 - Last item, cut off (rating)
Apple iphone 6s Plus /7 Plus 414x736 - Last item, cut off (rating) and submit form not centered properly on bottom line.

Android Operating Systems
Samsung Galaxy S5/S6/S7 360x640  - Last item, cut off (rating)
Sony Xperia Z2/Z3 360x640  - Last item, cut off (rating)
Google Pixel 411x731  - Last item, cut off (rating) and submit form not centered.
Nexus 4 384x640 Last item, cut off (rating) and submit form not centered.
Nexus 5 411x731 Last item, cut off (rating) and submit form not centered.
Nexus 6 411x731  Last item, cut off (rating) and submit form not centered.

## Testing Part II
 Second part of the testing was completed using Web Page Test. 
 The site received all A's: First Byte Time, Keep alive enabled,
 Compress Transfer, Compress Images, Effective Use of CDN. The site received on F in Cache Static content.
 
 I tested in 8 different locations using somewhat different browsers. I was hoping to be able to test the site using a slower speed but I think even in small cities around the world one has pretty decent internet speed. 
 
 I tested in (1)Sydney (Australia), (2)Tokyo, Japan (Asia), (3)Rose Hill, Mauritus (Africa), (4)Instabul, Turkey (Middle East), (5)Sao Paolo, Brazil (South America), (6) Prague Czech Republic (Europe), (7) Manchester UK (Europe), (8) Toronto, Canada (North America)and last (9) Clifton, NJ (North America).

1 Doc complete 2.38s Fully Loaded 2.417s
2.              2.195s              2.25
3.              2.978s              3.105
4               2.334s              2.422s
5.              2.297s              2.469s
6.              2.191s              2.248
7.              1.37s               1.623s
8.              2.286               2.374s
9.              2.9122s             2.247s

Overall, I did not expect huge discrepancies but expected some cities to have faster loading times. I was surprised that Tokyo (2) was not faster than Manchester (7). 

In reading the rest of the performance results I noticed that first it loaded text and then the images. Or at least some images loaded faster than others. 

In completing my testing, I have decided to redo the affected parts over and maybe redesign those and rewrite the code to get better control of some components like the nav, the submit form and look at the margins and spacing a little better. 
I also need to look at all the images and make sure they are rendering and are responsive when the website is browsed through a smaller device.
A lot of informaiton was given in the results when using the webpagetest site and I would like to know more about what it all means.

## UserDemographics
*Gender: All
Age: Varies, from early 20’s to …..
Location: Worldwide
Income: Wide range
Education level:  Varied
Marital or family status: Varied
Occupation: Varied
Ethnic background: Varied

Usage trends
Location: Worldwide
Time spent online : varies
Loyalty/Incentive/Reason: discount for certain purchases or buying more than one product. 


Values and attitudes
Media: Active role in social media 
Activities: Varies
Needs: interested in clothes, being well dressed, 
Desires: wants to look well dressed
Personality: varies but fun, one who enjoys mixing it up
Attitudes: Positive
Values: values a good price or bargain and valued well made products and materials. 
Interests/hobbies: varied
Lifestyle: active 


Product Knowledge and tasks
Product knowledge: buyers aware of current trends and costs and materials
Competitive awareness: Internet
Order method: easy, fast, find easier ways to make purchasing easier on the go.

Devices Used to Access Website
*Smartphone/Tablet/Desktop Computer/Laptop Cumputer

*OS
*IOS
*Android
*Other

Goals of Website
Short term: Advertise online via social  media
Long term: continually add products and change layout often and keep updating products
Motivation: 
Success outcomes : $$$$ more products, add new types of product.

