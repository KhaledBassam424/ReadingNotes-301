# Responsive Web design 

Responsive web design (RWD) is a web development approach that creates dynamic changes to the appearance of a website, depending on the screen size and orientation of the device being used to view it. RWD is one approach to the problem of designing for the multitude of devices available to customers, ranging from tiny phones to huge desktop monitors.

RWD uses so-called breakpoints to determine how the layout of a site will appear: one design is used above a breakpoint and another design is applied below that breakpoint. The breakpoints are commonly based on the width of the browser.

The same HTML is served to all devices, using CSS (which determines the layout of webpage) to change the appearance of the page. Rather than creating a separate site and corresponding codebase for wide-screen monitors, desktops, laptops, tablets and phones of all sizes, a single codebase can support users with differently sized viewports.

In responsive design, page elements reshuffle as the viewport grows or shrinks. A three-column desktop design may reshuffle to two columns for a tablet and a single column for a smartphone. Responsive design relies on proportion-based grids to rearrange content and design elements.

While responsive design emerged as a way to provide equal access to information regardless of device, it is also possible to hide certain items — such as background images, as in the Transport for London example above, secondary content or supplementary navigation — on smaller screens. Decisions about hiding content and functionality or altering appearance for different device types should be based on knowledge about your users and their needs.


# The float Property
The float property is used for positioning and formatting content e.g. let an image float left to the text in a container.

> The float property can have one of the following values:

1. left - The element floats to the left of its container
2. right - The element floats to the right of its container
3. none - The element does not float (will be displayed just where it occurs in the text). This is default
4. inherit - The element inherits the float value of its parent
In its simplest use, the float property can be used to wrap text around images.


> example on floating right and left

![Float right vs. Float left](https://tse4.mm.bing.net/th?id=OIP.1ghS6DwDs6L6Sec-XY0iaQAAAA&pid=Api&P=0&w=300&h=300)


# SMACSS

SMACSS (pronounced “smacks”) is more style guide than rigid framework. There is no library within here for you to download or install. There is no git repository for you to clone. SMACSS is a way to examine your design process and as a way to fit those rigid frameworks into a flexible thought process. It is an attempt to document a consistent approach to site development when using CSS. And really, who isn’t building a site with CSS these days?!


> Why we use SMACSS 

Every project needs some organization. Throwing every new style you create onto the end of a single file would make finding things more difficult and would be very confusing for anybody else working
on the project. 

Of course, you likely have some organization in place already. Hopefully, what you read among these pages will
highlight what works with your existing process and, if I’m lucky, you will see new ways in which you can improve your process.
How do you decide whether to use ID selectors, or class selectors, or any number of selectors that are at your disposal? How do you decide which elements should get the styling magic you wish to bestow
upon it? How do you make it easy to understand how your site and your styles are organized?
At the very core of SMACSS is categorization. By categorizing CSS rules, we begin to see patterns and can define better practices around each of these patterns.

There are five types of categories:
1. Base
2. Layout
3. Module
4. State
5. Theme


We often find ourselves mixing styles across each of these categories.
If we are more aware of what we are trying to style, we can
avoid the complexity that comes from intertwining these rules.

1. **Base style**

A Base rule is applied to an element using an element selector, a
descendent selector, or a child selector, along with any pseudoclasses.
It doesn’t include any class or ID selectors. It is defining the
default styling for how that element should look in all occurrences
on the page.


2. **Layout style**

CSS, by its very nature, is used to lay elements out on the page.
However, there is a distinction between layouts dictating the major
and minor components of a page. The minor components—such as
a callout, or login form, or a navigation item—sit within the scope
of major components such as a header or footer. I refer to the minor
components as Modules and will dive into those in the next section.
The major components are referred to as Layout styles.
Layout styles can also be divided into major and minor styles based
on reuse. Major layout styles such as header and footer are traditionally
styled using ID selectors but take the time to think about
the elements that are common across all components of the page
and use class selectors where appropriate.


3. **Module style**

a Module is a more
discrete component of the page. It is your navigation bars and your
carousels and your dialogs and your widgets and so on. This is the
meat of the page. Modules sit inside Layout components. Modules
can sometimes sit within other Modules, too. Each Module should
be designed to exist as a standalone component. In doing so, the
page will be more flexible. If done right, Modules can easily be
moved to different parts of the layout without breaking.
When defining the rule set for a module, avoid using IDs and element
selectors, sticking only to class names. A module will likely
contain a number of elements and there is likely to be a desire to
use descendent or child selectors to target those elements.

