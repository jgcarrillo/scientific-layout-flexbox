# Types of scientific paper

The aim of this project is to practice with the Flexbox layout inspired by the image uploaded by [xkce](https://xkcd.com/2456/).

There are twelve types of layouts based on the image followed in the above link, that you can see below:

<p align="center" width="435">
    <img align="center" width="435" src="https://github.com/jgcarrillo/scientific-layout-flexbox/blob/main/assets/types_of_scientific_paper.png" />
</p>

## Basic explanation of CSS Flexbox

In order to understand the whole concept of CSS Flexbox, there is a sample image representing the structure of all the papers in this project.

<p align="center" width="399">
    <img align="center" src="https://github.com/jgcarrillo/scientific-layout-flexbox/blob/main/assets/info_layout.jpg" />
</p>

Every single project have been divided into different parts to achieve the image of a newspaper or a scientific paper and obviously to practice the concepts of Flexbox.

- **body**. Is the general container of the project and emulates a paper. In order to get the item align horizontally and vertically aligned, the body need to have a *flex* display. In Flexbox, the **parent container need to be flex if we want the children to apply the flex properties**. Once we have set the display to flex in the parent, the children can set the flex properties by their own.
- **paper**. Once the parent have the flex display, this class only applies styles such as background, borders and size. The flex properties have been set up in the parent (alignment).
- **title**. The title has it's own flex display so we can play with the alignment and other properties such as flex-direction: column.
- **info**. In this case, we don't need to set the flex display because the **p** tag have a block display and the configuration of the paper doesn't need an special layout.
- **content**. This is the main content of the paper and have a flex display, so we can situated the children with flex properties. This container only defines the display and the childrens will set the width and other styles.
- **content_left** and **content_right**. This is the content situated at the left of the paper with a 50% of width.
- **number_page**. This acts like a **footer**. The display is also flex because we need to situated the p tags one in the left and the other in the right. The appropriate property is **space-between**, so we need to set flex to this container.

So that's all. Flexbox is easy to use but with a lot of possibilities. The most important thing to know is to establish the **flex display** in the parent so the children will acts with a flex layout.

## Resources

The resources that I have used in order to guide myself are the following:

- [Css tricks - A guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [MDN - Basic concepts of flexbox](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
- [Platzi - Simpsons newsletter](https://platzi.com/blog/periodico-simpsons-css/)
