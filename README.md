# Horiseon
This is my first homework assignment from my coding certificate program. We were given demo files of an SEO company called "Horiseon" to work with. We worked on HTML semantics and cleaning up the CSS. 

## Changes I made in HTML.

1. Added rows between the &lt;div&gt; and other tags in the &lt;body&gt; to make it easier to read. 
2. Changed the title from “website” to “Horiseon Marketing."
3. Noted where the &lt;Header&gt;, &lt;Navbar&gt;, &lt;Body&gt;, &lt;Sidebar&gt;, and &lt;Footer&gt; are.
4. Added an aria-label to the &lt;hero&gt; image. 
```
    I wanted to add descriptive text for it and didn’t know how to till I watched a replay 
    of the office hours. In it, our teacher demo’d how that can add descriptive text where 
    you can’t add descriptive text. 
```
5. Turned the &lt;div&gt; header into a &lt;header&gt;. 
6. Added image descriptions for &lt;body&gt; images. 
7. Removed an unnecessary &lt;img&gt; tag from the &lt;Cost Management&gt; clip art. 
8. Updated the copyright to 2020.
9. Created a new &lt;div&gt; class and named it &lt;benefit-box&gt; to consolidate code in the &lt;Sidebar&gt;. 
10. Removed unnecessary &lt;div id&gt; tags from two of the boxes inside the &lt;content&gt; box.
11. Created a new &lt;div&gt; class and named it &lt;content-boxes&gt; to consolidate code in the &lt;Body&gt;.
12. Linked my Navbar to my h2 sections inside &lt;content-boxes&gt;.  


## Changes I made in CSS.

1. Added notes to style.css.
2. Removed list style type from “.header div ul”.
3. Rearranged “a” and “p” font styles to above the “.content” style to create better flow of information. 
4. Consolidated styles for &lt;Sidebar&gt; boxes to target the new &lt;div&gt; class I made for index.html. 
5. Rearranged style order so that the styles for boxes inside the “content” box follow the styles of the “content” box. Prior to this, the order was: 
    * .content
    * .benefits
    * boxes inside .benefits box
    * boxes inside .content box
6. Changed the blue background for boxes to one color of blue. 
7. Consolidated styles for &lt;Body&gt; boxes to target the new &lt;div class=content-boxes&gt; I made for index.html. 

## Screenshot of Working Website.

![Image](./assets/images/Homework-Screenshots.jpg)