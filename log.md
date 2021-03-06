# 100 Days Of Code - Log

### Day 0: Jan 19th, 2020

**Today's Progress**: Built a basic quote generator which displays Stoic quotes.

**Thoughts:** I had to remind myself how to set up CSS from scratch well, as I'd been relying on Bootstrap containers. I'm not used to vanilla JS as I'd been doing a lot of React but it was good - and surprisingly simple. I learnt something new to launch functions on page load i.e. `<body onload="codeAddress();">.`I used https://femmebot.github.io/google-type/ for font inspiration which was incredibly useful.

**Link to work:**: https://marcusaureliusquotes.netlify.com/

### Day 1: Jan 20th, 2020

**Today's Progress**:  I've been working through the callbacks and higher order function challenges on @willsentance's great Javascript: The Hard Parts course (on @FrontendMasters). Revisited foreach, map, reduce etc. now knowing exactly how they work.

**Thoughts:**: Reminded myself on foreach, map, reduce etc. Can see benefits of higher order functions and generalising functions in large code bases. Realising functions are first-class objects makes understanding simpler i.e. that you can pass them as arguments, return them from functions etc.

**Link to work:**: https://gist.github.com/edgwatson1/c77c107ca91c046c052c13e395094071

### Day 2: Jan 21th, 2020

**Today's Progress**: Spent time trying to work through an authentication flow. I've created an Express/JWT/Passport/MySQL backend & separate frontend. But haven't got it working yet. Gonna resort to a tutorial on this - feel like in practice, it's simpler than I'm making it.

**Thoughts:**: Authentication flow isn't obvious at first but backend is relatively new to me so I suspect t'll get easier with practice. Need to follow a tutorial on this one first I think. 

**Link to work:**: https://gist.github.com/edgwatson1/c77c107ca91c046c052c13e395094071

### Day 3: Jan 22nd, 2020

**Today's Progress**: I wanted to test out Material-UI for React. So I started building the structure for a Twitter clone frontend. To be styled and populated with faker.js at another time... https://github.com/marak/Faker.js/

**Thoughts:**: Not sure to extent I can customise Material-UI components - they might end up being restrictive more than they are useful but for putting something together quickly they seem really good.

Need more practice mapping over objects/arrays to render, and need to work out how to create infinite scroll effect and keeping pulling data from API as the user scrolls.

**Link to work:**: https://gist.github.com/edgwatson1/c77c107ca91c046c052c13e395094071

### Day 4: Jan 23rd, 2020
 MySQL with Express practice, using on delete req to propogate with ON DELETE CASCADE. 

**Thoughts:**: Need more practice building dbs with many tables using foreign keys. Referential Actions important to understand when designing dbs. In mySQL there is ON DELETE CASCADE, ON UPDATE CASCADE, SET NULL, NO ACTION, SET DEFAULT. Documentation here: https://dev.mysql.com/doc/refman/8.0/en/create-table-foreign-keys.html

### Day 5: Jan 24th, 2020

Good day today: in my bootcamp project I'm making an interactive quiz in React and implemented some effective conditional rendering. 

**Thoughts:**: I'm doing a lot of prop drilling & want to explore Context API.

### Day 6: Jan 25th, 2020

No coding today, hectic with friends visiting Lisbon!

### Day 7: Jan 26th, 2020

Working through Tony Alicea: JS Understanding The Weird Parts. Learning and revisiting crucial concepts e.g. execution contents, this keyword, never to set variables to value undefined as it causes debugging problems etc. May make a This keyword minisite for my portfolio (Wes Bos's suggestion).

**Thoughts:**: Useful stuff but I need to try these things out in pratice. Need some related challenges as kthe nowledge will probably not bed in well just watching, despite it being interesting.
Ref: https://www.youtube.com/watch?v=Bv_5Zv5c-Ts&feature=youtu.be

### Day 8: Jan 27th 2020

Checking out and playing with Type Coercion in JS i.e. if you use an operator to perform an operation with variables of types JS does not expect, is tries to convert the types. 

Here's what coerces to what:https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong

**Thoughts** Important to understand to avoid errors. Can see use of Typescript (maybe I should learn how to use...)
