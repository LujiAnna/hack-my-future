# Wiki

## Task: Clone duckduckgo website

- [x] Step 0 check-list: Find out
- [x] Communication: github & slack
- [x] Repo & Initial files set up 

### Repo

- [x] Created a new repository
- [x] Add collaborators
- [x] Add a license
- [2] Create a README : Assign myself - Monday
- [x] Turn on GitHub Pages : Communicate with updation and screenshot & website description
- [ ] Website clone: Desktop Vs Mobile Version Vs Tablet etc
- [ ] Website design: Browser rendering: Safari Vs Chrome Vs IE etc
- [1] Wireframe -- invisio: Assign myself. Draw this & pic of web -Monday
- [3] Write a development strategy: Communicate. Assign self - Monday
- [4] Translate the strategy into issues - Monday Night
- [6] Put each issue on a new project board - Monday Night
- [5] Issue/tasks assignments: Communicate - Monday Night
  

- [\] My Issues 1, 2, 3
- [\] PR, Review
1. Time to meet up & talk: tuesday?
2. CSS Stack to Use: Framework, Grid, Flex, Float, pure css?
- [ ] Website Browser : Screenshot
3.  Assets: pics, images, fonts
4.  Other: color, responsivity
5.  Flow: project board, issues, reviews, conflicts, etc

Requirement Set Name: Responsive Design Requirements

Description:

For optimal user experience, the PoetsBar layouts are designed to adapt and be responsive across a wide variety of devices.

Requirements

The layout adapts to accommodate breakpoint widths: 480, 600, 840, 960, 1280, 1440, and 1600dp.
The design is based on a 12-column grid layout.
i. Content is logically ordered in grid for display on mobile devices.
The content is suitable for use in a mobile context.
Pages are divided into usable size portions for mobile devices.
Scrolling is limited to one direction.
Background images are readable on mobile devices.

## User Story: Responsive Design Requirement

__Story: As a site user, I want to use the site to on a variety of devices so I can, have access on the go.__

Repo

-[ ] Create a branch called `media-query`

README.md
- [ ] Add mockup for tablet and phones


HTML

- [ ] Viewport: Add the meta tag and set viewport to adapt to variety of devices window sizes.

Site layout adapts to accommodate breakpoint widths: 480, 600, 840, dp.
The design is based on a 12-column grid layout.
Content is logically ordered in grid for display on mobile devices.
The content is suitable for use in a mobile context.
Pages are divided into usable size portions for mobile devices.
Scrolling is limited to one direction.
Background images are readable on mobile devices.

CSS 

- [ ] Media Query: Make the site layout adapts to accomodate breakpoint widths: for ..480, ..600, ..840
- [ ] Container: 
- [ ] Text / Font: Set text to ..
- [ ] Image:
- [ ] Icons: reduce or increase
- [ ] Search Input: shrinks
- [ ] Buttons: 
- [ ] Form:
- [ ] Color
- [ ] Shadow
- [ ] Grid

Dev Strategy.md
- [ ] Update dev strategy

/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {...} 

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {...} 

// DEFAULT already done by team
/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {...} 

=====
/* Responsive Design Requirement*/

/* Medium devices (landscape tablets, 840px and down) */
@media only screen and (max-width: 840px) {
    .search-field[type=text]  {
        width: 40em;
    }
    .search-field::placeholder {
        font-size: 13px;
    }
    #features h5 {
        font-size: 1.1em;
        font-weight:normal;
    }
} 

/* Extra small devices (phones, 540px and down) */
@media only screen and (max-width: 540px) {
    .search-field[type=text]  {
        width: 35em;
    }
    .search-field::placeholder {
        font-size: 11px;
    }
    #features h5 {
        font-size: 1em;
        font-weight:lighter;
    }
} 
====

- [ ] Update readme file
- [ ] Update development-strategy file

@media (max-height: 590px), (max-width: 700px)
.onboarding-ed__slide .onboarding-ed__content .onboarding-ed__subtitle {
    font-size: 17px;
    line-height: 20px;
}

p {
    line-height: 1.35;
    padding-top: .25em;
    padding-bottom: .25em;
}

## 3. User-Story: A flexible Website 

> Assigned to `Anna`

_As a user, I want to be able to consult the website from diferrent devices:_

- mobile
- tablets

### Repo

- [ ] Created a branch called `media-queries`
- [ ] Updated the development-strategy.md according to the changes made in html/css to meet the User-Story requirements.
- [ ] Add mockup for tablets in the README file

### HTML

- [ ] Create the meta tag and set viewport to adapt to variety of windows sizes

### CSS

- [ ] Make the site layout adapts to accomodate different breakpoint widths.
- [ ] Resize search button to accomodate breakpoints 850px, 620px, and 420px
- [ ] Resize font to acomodate breakpoints 590px, 180px


Tutorials Used:
Responsive design with media queries: https://www.youtube.com/watch?v=fA1NW-T1QXc 
Create Website Layouts Using CSS Grid: https://www.youtube.com/watch?v=HgwCeNVPlo0
CSS Grid Layout: https://www.youtube.com/watch?v=N5Lt1SLqBmQ