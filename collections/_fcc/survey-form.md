---
title: "Survey Form"
excerpt: "A simple, single webpage demonstrating basic HTML and CSS skills. With forms and fields as a focal point."
header:
  teaser: "https://jalence.github.io/fcc-projects/responsive-web-design/02-survey-form/teaser.jpg"
sidebar:
  - image: https://jalence.github.io/fcc-projects/responsive-web-design/02-survey-form/teaser.jpg
    image_alt: "Preview of Project"
  - links:
    - title: "Links"
      children:
      - label: "Demo Page"
        icon: 
        url: https://jalence.github.io/fcc-projects/responsive-web-design/02-survey-form
      - label: "GitHub Repo"
        icon: fa-brands:github
        url: https://github.com/Jalence/fcc-projects/tree/master/responsive-web-design/02-survey-form
      - label: "FreeCodeCamp Page"
        icon: simple-icons:freecodecamp
        url: https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-survey-form
    - title: "Technologies Used"
      children:
      - label: "Materialize"
        url: https://materializecss.com
---

Goal is to create a survey form that demonstrates basic HTML and CSS skills. 

## User stories
<!-- User stories are short, simple descriptions of a feature/requirement told from the perspective of the user or client. 
For FreeCodeCamp, these are also used as tests to determine if the project satisfies the requirements of the assignment.
-->

| 01 | I can see a title with `id="title"` in H1 sized text.|
| 02 | I can see a short explanation with `id="description"` in P sized text.|
| 03 | I can see a form with `id="survey-form"`.|
| 04 | Inside the form element, I am required to enter my name in a field with `id="name"`.|
| 05 | Inside the form element, I am required to enter an email in a field with `id="email"`.|
| 06 | If I enter an email that is not formatted correctly, I will see an HTML5 validation error.|
| 07 | Inside the form, I can enter a number in a field with `id="number"`. |
| 08 | If I enter non-numbers in the number input, I will see an HTML5 validation error. |
| 09 | If I enter numbers outside the range of the number input, which are defined by the min and max attributes, I will see an HTML5 validation error. |
| 10 | For the name, email, and number input fields inside the form I can see corresponding labels that describe the purpose of each field with the following ids: `id="name-label"`, `id="email-label"`, and `id="number-label"`.|
| 11 | For the name, email, and number `input` fields, I can see placeholder text that gives me a description or instructions for each field.|
| 12 | Inside the form element, I can select an option from a dropdown that has a corresponding `id="dropdown"`.|
| 13 | Inside the form element, I can select a field from one or more groups of radio buttons. Each group should be grouped using the `name` attribute.|
| 14 | Inside the form element, I can select several fields from a series of checkboxes, each of which must have a `value` attribute.|
| 15 | Inside the form element, I am presented with a `textarea` at the end for additional comments.|
| 16 | Inside the form element, I am presented with a `button` with `id="submit"` to submit all my inputs.| 