# All About Dinos

![devices](https://i.imgur.com/ZK3XJXr.png)

[All About Dinos](https://georgiegray.github.io/all-about-dinos/) is an educational website about dinosaur history, intended for children. It provides a jumping-off point for children to begin learning about dinosaurs.

The content is kept relatively concise and playful to keep it interesting for the target demographic. All About Dinos does not provide everything there is to know about dinosaurs, it's more intended as a starting point to pique the interests of future dinosaur enthusiasts.

The website consists of four main areas:
- The home page (or introduction)
- The dinosaur index
- The dinosaur profile page(s)
- The dino facts newsletter

There are 18 pages in total, including 15 dinosaur profiles.

The website is hosted using GitHub Pages, see it here:  
https://georgiegray.github.io/all-about-dinos/

## Table of Contents
- [Project Requirements](#project-requirements)
  - [User Experience](#user-experience)
  - [Development](#development)
  - [Deployment & Version Control](#deployment-version-control)
- [Target Demographic](#target-demographic)
- [User Stories](#user-stories)
- [Features](#features)
- [Technology](#technology)
- [Design](#design)
  - [Colour Pallette](#colour-pallette)
  - [Typography](#typography)
- [Local Development](#local-development)
- [Deployment](#deployment)
- [Testing](#testing)
  - [Issues](#issues)
  - [Third-Party](#third-party)
    - [W3C HTML Validator](#w3c-html-validator)
    - [W3C CSS Validator](#w3c-css-validator)
    - [Lighthouse](#lighthouse)
- [Content](#content)
  - [Editorial](#editorial)
  - [Media](#media)
- [Citations & Credits](#citations-credits)


## Project Requirements

### User Experience
- Main navigation menu & structured website layout
- Considerations for accessibility
- Sensible information hierarchy
- Consist content style & use of colour
- Must include a media element: audio or video

### Development
- At least three unique pages
- Passes the W3C HTML Validator
- Passes the W3C CSS Validator
- Suitable use of images: no pixelation or deformation
- External links should open in a seperate tab
- All internal links must work
- HTML element usage should be semantically correct
- No placeholder content allowed
- Intuitive website navigation

### Deployment & Version Control
- Should be deployed to a cloud hosting platform
- Use Git & GitHub as version control
- No commented out code in Git

### Maintainability
- Write a README.md
  - Project description
  - Screenshots
  - User value
  - Deployment
  - Provide references & give credit for anything not original
- Use an intuitive project structure for easy file discovery
- No inline CSS
- Good code readability & formatting, and naming consitency
- Locate asset files together (CSS, Images, etc)

## Target Demographic
- Children aged 7+
  - All About Dinos is a text heavy website with a handful of illustrations which provide additional context about the historical information.
  - Children must understand the concept of a paragraph, be able to understand context and use pictures as an aid to better understand words which are new to them. My research suggests most children have these skills developed starting at the age of 7.
- Any adult without basic dinosaur history knowledge
  - Although lacking the kinds of deep information adults will be accustomed to in their regular daily reading, any adult may find this website useful as a light introduction to the topic.
- Geographical location is unimportant, but the website is only provided in English so the demographic will be limited to English speakers.

## User Stories

- As a user, I want to learn the names of specific dinosaurs
- As a user, I want to learn about the history of specific dinosaurs
- As a user, I want to learn about the types/categories of dinosaurs
- As a user, I want to learn about the time periods when dinosaurs existed
- As a user, I want to learn about the geography of the earth during the time of dinosaurs
- As a user, I want to learn why dinosaurs no longer exist
- As a user, I want to learn about what dinosaurs ate
- As a user, I want to look at illustrations of dinosaurs
- As a user, I want to sign up to a dinosaur facts newletter
- As a user, I want to find the All About Dinos social media accounts

## Features
### Header/navigation bar
- Website logo which can be clicked to return to the home page
- Primary navigation links to the home page and the dinosaur index
- Mobile-friendly navigation menu, hidden behind hamburger icon

![header1](https://i.gyazo.com/8a9f06706a8ebed7bb137e45e49ea3b0.png)  
![header2](https://i.imgur.com/j7VvhjO.gif)

### Footer
- Provides links to social media accounts for All About Dinos
- Social media links are commonly put in this place on websites, so the user will intuitively know where to find them.

![footer](https://i.gyazo.com/95afd0ce6e44c673b73023c6a10c5ac4.png)

### Dinosaur Card
The dinosaur card is intended to prompt the user to want to learn more about a particular dinosaur based on their name or appearance.

The card includes:
- Dinosaur illustration
- Dinosaur name
- Link to the profile page for that dinosaur

The card zooms the image, and changes the learn more text decoration to imply to the user that the component is interactable.

![card](https://i.imgur.com/8MLNR8S.gif)  

### Dinosaur Mosaic
The dinosaur mosaic is a collection of dinosaur cards arranged in a masonry grid style, implemented using CSS grid. This component is the hero header for the home page. It showcases what I think are the most interesting dinosaurs, and is intended to capture the interest of those who land on the home page for the first time.  

As the viewport size shrinks, the mosaic arranges itself to make best use of the screen real-estate while still staying true to the intent of the feature. See second example below.  

#### Primary arrangement
![mosaic1](https://i.gyazo.com/8c11c9de6f740e2f6b95b27d13025049.jpg)  

#### Secondary arrangement
![mosaic2](https://i.gyazo.com/7323edee0c2b135a062a6fc5f4da2031.jpg)

### Types of Dinosaur
- Explains the types/categories of dinosaurs, and how they're differentiated  
![what](https://i.gyazo.com/b079750fbc876803120ac20ca660b188.png)

### Dinosaur Time Periods
- Provides high-level information about dinosaur time periods
- Explains that dinosaurs existed within the Mesozoic era
- The three periods are: Triassic, Jurassic and Cretaceous  
![when](https://i.gyazo.com/2897b4a66141861915efbb449792191c.png)

### Dinosaur Geography
- Information about where dinosaurs existed, and where they travelled.
- Includes an illustration of Pangea, a single super-continent where all dinosaurs coexisted before contentinental drift created todays earth.  
![where](https://i.gyazo.com/a1dca91d41031db4fe527d8761650494.png)
![pangea](https://i.gyazo.com/c40a89835081284eabb8ac6bda22e7ce.png)

### The End of the Dinosaurs
- An explanation of how the dinosaurs came to their demise
- Youtube video by popular education channel: Kurzgesagt
- The channel provides factual information but conveys it using a fun and playful art style, making it approachable for children.
![end](https://i.gyazo.com/888b36c738c597d338acfb668c9394f8.png)

### Dinosaur Index
- A non-exhaustive alphabetically ordered list of dinosaurs
- The familiar dinosaur card style from the home page makes an appearance here, but arranged in a different style with no "hero" card.
- This page is intended to behave as a list or "index" for the available dinosaur information available on the website.
- When clicked the cards link to each dinosaurs unique profile page including further historical information.

![dinos](https://i.gyazo.com/38c8a2e0156855dfe3fcf6db3f74ae4d.png)

### Dinosaur Profile Page(s)
- The name and an illustration of the dinosaur
- An introduction paragraph to set the scene
- Two or more additional sub-sections providing additional facts and information about the dinosaur. These include diet, appearance, temperament & nature, their height or weight, and some random trivia facts.
- There are 15 unique dinosaur profile pages

![profile](https://i.gyazo.com/5f4513155cf23076cb6e68bf30f7a3c1.png)

### Dinosaur Facts Newsletter

#### Sign-up form

#### Thank you page

## Technology

## Design

### Colour Pallette

### Typography

## Local Development

## Deployment

## Testing

### Issues

### Third-party

#### W3C HTML Valdiator

#### W3C CSS Validator

#### Lighthouse

## Content

### Editorial

### Media

## Citations & Credits