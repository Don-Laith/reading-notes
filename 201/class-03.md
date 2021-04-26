## HTML Lists, Control Flow with JS, and the CSS Box Model
### Lists
#### There are lots of occasions when we need to use lists. HTML provides us with three different types:
- Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number.
- Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
- Definition lists are made up of a set of terms along with the definitions for each of those terms.
## summary
#### Lists X There are three types of HTML lists: ordered, unordered, and definition. X Ordered lists use numbers. X Unordered lists use bullets. X Definition lists are used to define terminology. X Lists can be nested inside one another.
## Boxes
### Controlling size of boxes Box model for borders, margin and padding Displaying and hiding boxes
#### At the beginning of this section on CSS, you saw how CSS treats each HTML element as if it lives in its own box. You can set several properties that affect the appearance of these boxes. In this chapter you will see how to:
- Control the dimensions of your boxes
- Create borders around boxes
- Set margins and padding for boxes
- Show and hide boxes
#### By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties. The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.
#### When you use percentages, the size of the box is relative to the size of the browser window or, if the box is encased within another box, it is a percentage of the size of the containing box.
#### When you use ems, the size of the box is based on the size of text within it. Designers have recently started to use percentages and ems more for measurements as they try to create designs that are flexible across devices which have different-sized screens. In the example on the right, you can see that a containing <div> element is used which is 300 pixels wide by 300 pixels high. Inside of this is a paragraph that is 75% of the width and height of the containing elemen This means that the size of the paragraph is 225 pixels wide by 225 pixels high.
## summAry
- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and paddingfor each box with CSS.
- It is possible to hide elements using the display andvisibility properties.
- Block-level boxes can be made into inline boxes, andinline boxes made into block-level boxes.
-boxes containing text and the leading.
- CSS3 has introduced the ability to create imageborders and rounded borders.