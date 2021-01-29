# Brief

This is a recreation of the Google homepage, the first assignment by the Odin Project.

## Thoughts before beginning

I have some experience in HTML and CSS but will need to refresh my positioning attributes and maybe even some of my form entry elements. I'm really hoping that this won't prove too difficult following my time on Learning Web Design.

## Thoughts after completion

This task was about as challenging as I expected it to be; I found myself Googling a lot of things I'd already covered in Learning Web Design, but it was to remind myself of the attributes and values rather than to understand a concept. It was handy remembering the trick to 'push' flex items to either side of a container, and in general I knew when to apply which positioning approach. I'm proud only to have needed to check developer tools for breakpoints for my own responsive rules, but that may explain if my solutions aren't the most logical.

## Areas for improvement

Although the page does generally look like the Google home page and the challenge was specifically *not* to spend too much time tweaking pixels, I noticed the following problems on which I could spend more time either to come up with a solution or improve the applied solution:

- The only way I could push 'Sweden' in the footer right was to add `margin-left` which resulted in the borders not extending to the far left of the page; my solution to keep the rule and change the border to the footer itself and the lower link container was probably not the most elegant possible.

- I just left out that little 3x3 grid in the top right on the assumption that it's some sort of .svg graphic and I'm not ready to deep dive on that yet.

- Jennifer Neiderst Robbins recommends grouping and labelling CSS declarations, but my initial semantic idea of separating styling and layout declarations went badly, resulting in repeated disparate declarations for the same items. Instead, I opted to deal with declarations grouped chronologically, which makes finding back declarations much easier, but I'm still sure there's a more logical way to group my declarations. For example, I generally tried to keep my links in the same place but there are link declarations within the language select block and the footer. I don't currently know how to avoid overlap without making multiple declaration blocks per element at different points on the page, which creates extra code and would probably complicate debugging.

- Generally I'm relatively certain that later I'll be more logical in my use of ids, classes and selectors. With so few elements on the page, it made more sense to just apply a rule to multiple objects in a list or to use selectors rather than to give them a class, but I may later learn that that's better practice. The footer styles in particular look like there are too many individual declarations but they all seem logical and necessary for the moment.

- I'm not very confident with `box-shadow` and need to look at many more examples.

## Lessons learned

### **Mobile first!**

It makes perfect sense that the screen should be gradually modified to get larger as viewports can get infinitely larger but not infinitely smaller; however, having begun the exercise before intending to make the page responsive I made *way* too much work for myself with those media queries. Next time I'll start with the smallest version possible.

### Group CSS rules

I know I need to group them, but not yet sure how. Chronologically in the DOM seemed best for this project.

### Apply classes to elements sharing styles (make code 'reusable')

I'm not skilled enough to have known exactly which classes to share between elements, I'm sure I could cut some lines of CSS by adding some classes but it's time to move on to another project. It should become habit to apply a shared class to elements visibly similar in any way.

### Take the time to learn

At this stage, so many of the solutions involve acquainting myself with new rules and concepts (the adaptive searchbar solution of `calc()` was new information) that making the webpage is a fraction of the time compared to Googling around.

### I am a perfectionist

I knew this already, but I should have anticipated wanting to make the page adaptive from the start, and therefore started with the mobile version of the site.