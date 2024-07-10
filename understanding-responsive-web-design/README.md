# Module Introduction
- **Responsive Design - What & Why**
- **Working with Media Queries**
- **Creating a Side Drawer**
# Project Overview
# Please Read: Optional Lectures [Day 20]
In the following four lectures ("Optional: ...") we create the project required for this responsive section from scratch.

The required HTML & CSS concepts were already taugt in the previous modules of this course, therefore you have two options now:

a) Follow along the "Optional" lectures to revise the already learned concepts and create another website

b) Skip the "Optional" lectures and directly continue with the lectures about responsive design ("What is Responsive Design?")

The choice is up to you, we recommend to also dive into the optional lectures as practicing is the best you can do on your way to become a web developer :)
# The Problem with Pixels
## Comparing Units (specifically for font-size)
- **px** Easy to understand & translatable
- **px** Limited user focus & not scalable (increasing the width of the device does not affect the pixels)
# Introducing "em" & "rem"
- **%** Relative to parent element size
- **%** Hard to manage due to cascading nature
- **em** Size is relative to font-size
- **em** Hard to manage due to cascading nature
- **rem** Size is relative to root element's font-size
- **rem** Preferred choice if applicable
# Applying "em" & "rem" for the Font Size
- **Note** Our overview is not the single truth. Unit choice is subject to personal preferences & individual project requirements.
# Deep Dive: "em" vs "rem" vs "%"
- **%** refers to parent elements
- **em** and **rem** are related to the font-size no matter which property the **em** and **rem** unit is actually apply to
# Understanding Media Queries
- **Desktop First** `max-width`
- **Mobile First** `min-width`
## Common Breakpoints for Media Queries
- **Portrait** `Smartphone 480px`
- **Portrait** `Tablet 768px`
- **Landscape** `Notebook 1024px`
- **Landscape** `Desktop Computer 1200px`
- **Landscape** `TV >1200px`
# Side Drawer & Hamburger Icon - Theory
- **Create clickable hamburger button in mobile view**
- **Open side drawer on first button click**
- **Close side drawer on second button click**
- **Internal links** Adds defined ID to URL `href="#id"`
- **The target selector** Activates CSS rules if defined ID is selected in URL `#id:target`
# Introducing the "z-index" Property
## Introducing the "z-index" Property [Day 24]
**The z-index - What & Why?**
We learned about the document flow and how to change the default positioning of HTML elements with the position property.

By changing the default element position, you might come across a situation were one element is overlapping the other one and where you want to control, which element is positioned above the other.

For such cases, the z-index is required.

How does it work

The z-index , a CSS property, defines the z-order of a positioned element (i.e. an element with the position property applied with a value different than static). The z-order refers to the z-axis, so it controls how elements are stacked above it each other if applicable.

The default value for HTML elements is set to auto, which is aquivalent to 0. Positioned elements with a higher z-index are positioned above elements with a lower value for the z-index.

Code example

HTML

```
<body>
    <div id="first">Element 1</div>
    <div id="second">Element 2</div>
</body>
```
CSS

```
div {
width: 200px;
height: 200px;
text-align: center;
color: white;
}

#first {
background-color: rgb(55, 117, 209);
}

#second {
background-color: rgb(233, 137, 59);
}
```
By default, both elements follow the document flow, element 1 is displayed first, element 2 is displayed second, one after another.

Now add the following code to #second:
```
    position: absolute;
    top: 0;
    left: 0;
```
Element 2 is taken out of the document flow and displayed on top of element 1.

Adding z-index: 1 to #first does not change the order of the elements along the z-axis, as the z-index only has an impact on positioned elements, excluding the default value position: static.

Adding position: relative to #first, will display element 1 above element 2 again.