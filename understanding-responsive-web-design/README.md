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
# Understanding HTML Fragments