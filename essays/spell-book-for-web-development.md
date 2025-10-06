---
layout: essay
type: essay
title: "Spell Book for Web Development"
# All dates must be YYYY-MM-DD format!
date: 2025-10-05
published: true
labels:
  - HTML
  - CSS
  - Bootstrap
  - Learning
  - Reflection
---

When I first learn about HTML and CSS, I can envision how the code would look like. I thought out long and complex codes, with different sections that need to involve CSS to add styles into a website’s interface. One of my weaknesses is keeping track of each component when trying to change small details, such as margin, padding, and styles. It means that I have to go back and forth between HTML and CSS files to trace and find the problem. After learning and practicing Bootstrap with exercises along with their solution videos, I realized that I have no idea how big the Bootstrap library is. To me, it is like a spell book, where nothing makes sense at first.

## Benefits

Through E26, where I had to recreate a website using Bootstrap with HTML while trying my best to not apply styles with CSS, I noticed that Bootstrap and its built-in components are very helpful. A component that is useful and common for websites as a built-in feature is Navbar. In my HTML code for the website, I am able to combine several styles/adjustments for how I want my navigation bar to look:

```ts
<ul class="navbar-nav d-flex flex-row">
  <li class="nav-item px-4"><a class="nav-link" href="#">UPCOMING EVENTS</a></li>
  <li class="nav-item px-4"><a class="nav-link" href="#">FAQ</a></li>
  <li class="nav-item px-4"><a class="nav-link" href="#">KITCHEN</a></li>
  <li class="nav-item px-4"><a class="nav-link" href="#">CONTACT</a></li>
  <li class="nav-item px-4"><a class="nav-link" href="#">PRIVATE EVENTS</a></li>
</ul>
```

```ts
navbar-nav d-flex flex-row
```
- navbar-nav: provides proper spacing and layout for components for each item in the list.
- d-flex: turns items into flex containers. (can also be written as display: flex; in CSS)
- flex-row: adjusts the items in the list to be laid out horizontally next to each other. (can also be written as flex-direction: row;  in CSS)

There are many other sub-components to Navbar, such as .navbar-brand (for your company, product, or project name), that developers can choose from the [library](https://getbootstrap.com/). For me, to visibly see what styles the navigation bar will have when it is created/declared in the same HTML file really helps save time when debugging, providing consistency and clearance throughout the program.

## Issue(for me)

<div class="text-center p-4">
  <img width="200px" src="../img/book-magic-spells-witchcraft_105738-781.jpg" class="img-thumbnail" >
</div>

When I first attempt E34: BrowserHistory with Bootstrap 5 and looked at the solution video, I felt really lost because it seems like all the shorthand utility classes for spacing such as pt-5 or mb-3 are just commands that are made up on the spot to be used. After attempting and closely inspecting the website from Live Preview mode, I recognized their usage and wonder if there are other different variants of these “shortcuts” that can get used to more. [Bootstrap Library](https://getbootstrap.com/) provides all the utilities that users can choose from. The amount of built-in shortcuts was overwhelming. Due to the large amount of resources Bootstrap offers, software developers first need to know and understand what features are offered and how to use them, and I believe that is why the learning curve for UI Frameworks can be compared to a new coding language.

## Conclusion

While UI Frameworks such as Bootstrap can feel complicated and frustrating when starting to learn, they provide convenience, consistency, and maintainability for programs. For a professional developer, taking time and effort to be familiar with the resources from these frameworks is worth it, since the knowledge enables them to build more robust and creative websites that are visually appealing to users. Even though using raw HTML and CSS can offer developers more control, tools like Bootstrap offer great creativity and speed for modern web development. Just like reading and learning a spell book, even though the contents make no sense at first, taking time to learn and understand can create magical results in the long run.
