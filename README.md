# React Pokemon Search

Howdy! Your assignment today is to recreate the functionality
of our [Pokemon Search Engine](pokemon-app). Feel free to play
around with the app and see how it works. Here are some
thinking points you want to do when trying to recreate an app:

1. _What are the pieces of functionality I am working on? Are there buckets I can put work into to describe that functionality?_

2. _What components do I need to make the functionality work? Is there information that is shared between components? Who should own that information?_

3. _Which functionality has to come first? What is the basic version of this functionality working? How can I can get to proving that the simple version works?_

We like to call this the **planning phase**. If you improve on
that step, you will finish your code faster! You'll have
thought through how the app is. The process is so much more
important to uncover than it is just writing the code.

## Getting Started

First things first, make sure you fork and clone down the repository! From there,
you want to be sure to `npm install` or `npm i`. You always have to install packages
from an application. Then you can `npm start` to see what the setup we've given you.
(Which is practically nothing but an empty canvas).


## Deliverables

Below we will describe user stories, you will want to think
about how does this translate to code? What part of functionality do I need to
make it happen? **PRIORITIZE** the ones you understand how to do versus just
going down the list. We want you to be able to translate a list of requirements
of our app to functionality and it doesn't have to be step by step in that way.

You can find our list of Pokemon within the file `src/pokemon.js`. All you have
to do is make sure to import the data into the correct file. **We have said none
of the components that are necessary**. You get to decide how it flows. Using the
example app, try drawing out the website and thinking about what parts have to be
components.

### User Stories

- As a user, I want to be able to see an entire list of Pokemon from my `pokemon-data.js` file if my form has nothing in it.

- As a user, when I type into my form, I want it to only show  the Pokemon whose names include
the string I put into my search box. i.e. If I put in `b` or `B`, I want it to bring
up all Pokemon's names that **include** the character whether or not it is capital.

- When I click on a Pokemon's image, I want it to turn the Pokemon around and show
the opposite. If it is showing the front sprite and I click, I want it to show
the back sprite. If it is the back sprite, I want it to show the front sprite.


### BONUS

Only if you get through the first set of user stories. Try your hand to putting more
functionality inside of the application.
- Potentially multiple ways of filtering
- Ways of showing favorites
- Whatever you want!

#### Design

If you care about recreating the entire experience:
- We included a `pokemon.png` within the public folder for the Pokemon title.
  - All you have to do is import the image and use the src of `./pokemon.png`
- If you care about the entire imagery, try going back to the app and getting the
`style.css` file and seeing what classes they are using for each piece of functionality.


[pokemon-app]: https://learn-co-curriculum.github.io/js-pokemon-search-practice-assignment/
