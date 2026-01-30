# Commit planning
This document outlines a planned workflow for this exercise, with carefully-planned atomic commits to follow Git best practices as directed by The Odin Project: [Commit Messages](https://www.theodinproject.com/lessons/foundations-commit-messages) lesson.

## Commit Message Workflow Plan
**Commit 1:**
Add atomic commit workflow planning document

Create PLANNING.md to plan atomic commits and message format before starting work on this exercise.

**Commit 2:**
Add class and ID attributes to HTML elements

To support required CSS selectors for this exercise.

**Commit 3:**
Add background colours to elements

Apply background-color rules as specified in the exercise requirements.

**Commit 4:**
Set font style specified in exercise requirements

**Commit 5:**
Set font colours specified in exercise requirements

**Commit 6:**
Set font sizes specified in exercise requirements

**Commit 7:**
Set bold font specified in exercise requirements

    
# Class and ID Selectors
>Copied and reworked README to condense text into assignment constraints:

## Objective:
Match the outcome image: Add class and/or ID attributes in the HTML, and rules in the CSS file.

## Instructions:  
Analyze outcome image and determine which elements look:
    - similarly styled (classes), 
    - completely unique from the rest (ID),
    - slight variations from others (multiple classes).
   
>The objective is to to add the attributes and use the correct selector syntax to style elements, so which class or ID values are used is not important.
   
## Constraints:
Use non-keyword value for colours (RGB, HEX, or HSL). 
   
Add properties to each element:
* **All odd numbered elements**: 
    - light red/pink background
    - fonts: `Verdana`, `DejaVu Sans`, `sans-serif`
   
* **The second element**: 
    - blue font
    - font size 36px
   
* **The third element**:  
    - font size of 24px (in addition to font styles for all odd-numbered elements)
   
* **The fourth element**: 
    - light green background
    - font size 24px
    - bold style
   
> ### Note:
> Default fonts where none are applied may look different in the browser than in the provided desired-outcome image, this is okay.
   
## Desired Outcome
![desired outcome](./desired-outcome.png)
   
   
### Self Check
    - The odd numbered `p` elements share a class
    - The even numbered `div` elements have unique IDs
    - The Number 3 element have multiple classes