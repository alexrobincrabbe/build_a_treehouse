
[Build a Treehouse](https://alexrobincrabbe.github.io/build_a_treehouse/) is a site about
how to build a treehouse. 

## Table of Contents
1. <details open>
    <summary><a href="#ux">UX</a></summary>

    <ul>
    <li><details>
    <summary><a href="#goals">Goals</a></summary>

    - [Visitor Goals](#visitor-goals)
    - [Business Goals](#business-goals)
    - [User Stories](#user-stories)
    </details></li>

    <li><details>
    <summary><a href="#visual-design">Visual Design</a></summary>

    - [Wireframes](#wireframes)
    - [Fonts](#fonts)
    - [Icons](#icons)
    - [Colors](#colors)
    - [Images](#images)
    - [Styling](#styling)
    </details></li>
    </ul>
</details>

2. <details open>
    <summary><a href="#features">Features</a></summary>

    <ul>
    <li><details>
    <summary><a href="#page-elements">Page Elements</a></summary>

    - [All Pages](#all-pages)
    - [Index Page](#index-page)
    - [Gallery Page](#gallery-page)
    - [Contact Page](#contact-page)
    </details></li>

    <li><details>
    <summary><a href="#additional-features">Additional Features</a></summary>

    - [Image Loading Blur](#image-loading-blur)
    - [Email](#email)
    </details></li>

    <li><details>
    <summary><a href="#feature-ideas">Feature Ideas</a></summary>

    - [Basic](#basic)
    - [Content](#content)
    </details></li>
    </ul>
</details>

3. <details open>
    <summary><a href="#technologies-used">Technologies Used</a></summary>

    - [Languages](#languages)
    - [Frameworks](#frameworks)
    - [Libraries](#libraries)
    - [APIs](#apis)
    - [Platforms](#platforms)
    - [Other Tools](#other-tools)
</details>

4. <details open>
    <summary><a href="#testing">Testing</a></summary>

    <ul>
    <li><details>
    <summary><a href="#methods">Methods</a></summary>

    - [Validation](#validation)
    - [General Testing](#general-testing)
    - [Mobile Testing](#mobile-testing)
    - [Desktop Testing](#desktop-testing)
    </details></li>

    <li><details>
    <summary><a href="#bugs">Bugs</a></summary>

    - [Known Bugs](#known-bugs)
    - [Fixed Bugs](#fixed-bugs)
    </details></li>
    </ul>
</details>

5. <details open>
    <summary><a href="#deployment">Deployment</a></summary>

    <ul>
    <li><details>
    <summary><a href="#local-deployment">Local Deployment</a></summary>

    - [Local Preparation](#local-preparation)
    - [Local Instructions](#local-instructions)
    </details></li>

    <li><details>
    <summary><a href="#github-deployment">Github Deployment</a></summary>

    - [Github Preparation](#github-preparation)
    - [Github Instructions](#github-instructions)
    </details></li>
    </ul>
</details>

6. <details open>
    <summary><a href="#credit-and-contact">Credit and Contact</a></summary>

    - [Content](#content)
    - [Contact](#contact)
</details>

----

# UX
## Goals
### Visitor Goals
The target audience for Build a Treehouse are:
- People who want are interest in building their own treehouse.
- People who are interested in seeing beautiful picture of things built by other people.
- People who want to share things they have built and exchange ideas with the website owner.

User goals are:
- Be inspired to build a treehouse.
- Get an idea of the steps in involved in building a treehouse.
- Contact the website owner, to share projects or get tips.
- Follow the progress of the website owners treehouse.

Build a Treehouse fills these needs by:
- Providing a broad overview of the steps to build a treehouse on the home page.
- Providing external links to inspire and inform the visitor.
- Links in the text to the gallery, to show specific examples and show by example.
- Providing a contact page to write a message to the website owner.

### Business Goals
The Business Goals of Build a Treehouse are:
- Showcase the Treehouse built by the website owner.
- Gain subscribers through the newsletter.
- Make contact with people with similar interests, exhange ideas.

### User Stories
1. As a user interested in making a treehouse, I expect to see different kind of treehouses.
2. I expect to see different stages of treehouse construction.
3. I expect to find information to inform me how I should build a treehouse.

## Visual Design
### Wireframes

### Fonts
<div align="center">
</div>

### Icons
<div align="center">
  <img src="https://user-images.githubusercontent.com/44118951/92331590-1fe40380-f078-11ea-814b-d15b413f59aa.png" alt="Icons">
</div>

- Icons are taken from the [Fontawesome](https://fontawesome.com/) Icon library and are utilised as classes in the `<i>` tag.
- Icons are utilised in the footer for links to external sites.

### Colors
<div align="center">
  <img src="https://user-images.githubusercontent.com/44118951/92331821-a64d1500-f079-11ea-9ceb-a9b1b85872bd.png" alt="Color Pallette">
</div>

- The primary colour used for the site is green, which was chosen because of the treehouse theme. A darker shade was chosen for good contrast with the text.
- An off-white colour was chosen for the text, to contrast well with the background, while the hint of yellow/green compliments the green shades.
- a bright green was chosen for the in text links to make them clearly stand out, while not contrasting too much with the overall theme
- The only other colour used was a grey background for the introduction on the home page, which was chosen to be a light-grey to be subtle and not distracting, but give the introduction section a clear border.

### Images
<div align="center">
</div>

- All images used were my own, other than the mini-gallery on the home page. 

### Styling 

# Features
## Page Elements
### All Pages
#### Navbar

- The Navbar was based largely on the Love Running example. Other than the specific styling, a transition animation was added to the dropdown menu. 
- On larger screens the Navigation links are shown by default.
- The link to the current page is highlighted using combined text-shadow effects to create an aura effect.
- The Navbar is fixed and does not scroll with the rest of the content.

#### Footer

- The footer is styled similarly to the header
- However is not fixed, and is only visible when scrolling down.
- It contains links to external sites, with more information about treehouses for interested users.

### Index Page
#### Introduction
- The top section of the index page is an introduction, that gives and overview of the kinds of treehouses that can be built, any of which may apply to the intested user.
- The first image was chosen to be visually inviting, and immediately capture the interest of user visting the home page.
- The mini-gallery appears only on the screen for tablet screens or larger. It was added to add variety to the layour on larger screens, and utilize the screenspace. The border and shadow were added to make it stand out, as it is the only part of the site that uses images from external sources. Arrows were added to make it clear that this image is in a window that is scrollable. The scrollbars were removed for stylistic reasons.

#### Subsection links
- These only appear on the mobile version. They were added to allow users to quickly jump to sections without scrolling.
#### Floor, Stairs and Walls/Roof sections
- The images of the following sections show various stages of construction of a treehouse, and relate to the titles of each section. They were chosen to be both visually appealing, and informative.
- On larger screens the text for the following sections appears in front of the corresponding image for each subsection. This was done to make the page visually appealing on all screensizes, without leaving large sections of empty space.

#### Scroll to top button
- This only appears on the mobile view. It appears just above the footer at the end of the page. 
- It is overlaid on top of the content, to avoid blank space appearing between the content and the footer.

### Gallery Page
- The Gallery page contains images to specific parts of the treehouse.
- It is intended to be browsed, simply for people intested in seeing the images.
- It is also intended to be functional. Individual images are linked by words in the text on the main page. This allows users to see images that show more detail than is shown on the home page, if they are interested, without overcrowding the homepage with images.
- On larger screens the scroll direction was changed to horizontal. This was to allow several images to be shown screen at the same time, utilizing the whole screen and reducing the amount of scrolling. It also means that the the images can be scaled with a uniform height, and all fit entirely on the screen.
- On mobile view, the scroll to top button also appears.

### Contact Page


## Feature Ideas
### Basic
- A selection of countries to click on that brings you directly to the gallery.
- The ability to share photos directly to social media.
- Purchasing on the site
- More details about countries.

### Content 
- In order to keep the scope of the project manageable, the instructions on the site were kept very brief. In practice much more detail should be included on building a tree house. This would include more expansive and specific sections
- A cost caculator, with the floor area and type of treehouse(with/without roof). Would likely need Javascript to implement.
- An extra page, listing tools and materials that are needed

# Technologies Used
## Languages
- [HTML](w3.org/standards/webdesign/htmlcss)
    * Page markup.
- [CSS](w3.org/standards/webdesign/htmlcss)
    * Styling.

## Libraries
- [Google Fonts](https://fonts.google.com)
    * Font Styles.
- [Fontawesome](https://fontawesome.com/)
    * Used for icons

## Platforms
- [Github](https://github.com/)
    * Storing code remotely and deployment.
- [Gitpod](https://gitpod.io/)
    * IDE for project development.

## Other Tools
- [Balsamiq](https://balsamiq.com/)
    * To create wireframes.
- [Favicon Generator](https://www.favicon.cc/)
    * Favicons

----

# Testing
## Methods
### Validation
- HTML has been validated with [W3C HTML5 Validator](https://validator.w3.org/).
- CSS has been validated with [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) 

## Bugs

# Deployment