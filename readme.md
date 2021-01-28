This is a recreation of the Google homepage, the first assignment by the Odin Project.

I have some experience in HTML and CSS but will need to refresh my positioning attributes and maybe even some of my form entry elements. I'm really hoping that this won't prove too difficult following my time on Learning Web Design.

---

This task was about as challenging as I expected it to be; I found myself Googling a lot of things I'd already covered in Learning Web Design, but it was to remind myself of the attributes and values rather than to understand a concept. It was handy remembering the trick to 'push' flex items to either side of a container, and in general I knew when to apply which positioning approach. I'm proud not to have needed to look at the original homepage in developer tools even once, but that may explain if my solutions aren't the most logical.

Although the page does generally look like the Google home page and the challenge was specifically *not* to spend too much time tweaking pixels, I noticed the following problems on which I could spend more time either to come up with a solution or improve the applied solution:

- Ideally the search bar should keep its current (approximate) width but *collapse* when the screen width is less than its current length. I don't know how much I should be practising responsive web design at this stage.

- The only way I could push the country ('Sweden') right was to add a margin which resulted in the borders not extending to the far left of the page; my solution to apply them to the footer itself and the lower link container was probably not the most elegant possible.

- I'm aware that there's a far more complicated method of underlining text than 'text-decoration: underline;' which breaks the line for letters extending below the baseline, but didn't go down the rabbit hole as I assume that this was meant to be a beginners' exercise.

- I just left out that little 3x3 grid in the top right on the assumption that it's some sort of .svg graphic.

- My knowledge of 'box-shadow' could be better: how do you distinguish between two shadows where one extends downwards and outwards from the sides (as if the light is pointed at a greater angle) and the other extends downwards and inwards? Probably the answer is to experiment with a bunch of examples.

- Jennifer Neiderst Robbins recommends grouping and labelling CSS declarations, but my initial semantic idea of separating styling and layout declarations went badly, resulting in repeated disparate declarations for the same items. Instead, I opted to deal with declarations grouped chronologically, which makes finding back declarations much easier, but I'm still not sure if there's a more logical way to group my declarations. For example, I generally tried to keep my links in the same place but there are link declarations within the language select block and the footer. I don't currently know how to avoid overlap.

- Generally I'm relatively certain that later I'll be more logical in my use of ids, classes and selectors. With so few elements on the page, it made more sense to just apply a rule to two objects in a list rather than to give them a class, but I may later learn that that's better practice. The footer styles in particular look like there are too many individual declarations but they all seem logical and necessary for the moment.

---

Having a look at the top rated solution for the project; it does look identical to the original but also the two files are much longer than mine. Considering that I don't think I'm expected to source and embed .svg graphics at this stage, my version seems acceptable. I do now realise, however, that I hadn't noticed the text in the buttons got slightly darker on hover.