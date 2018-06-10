# 100 Days Of Code - Log


### Day 1: April 16, 2018

**Today's Progress**: I've created a GitHub repo for a JS library which perform "synchronized" events on a webpage

**Thoughts:** I'm slowly settling down. Two new things I'll explore : first JS library I'm creating / contributing to + first use of ES2015 only. I will start mixing both ES5 and ES2015 and refactoring while I'm getting confortable with ES2015.

**Link to work:** https://github.com/antoinelouis/timeline-events-trigger


### Day 2: April 17, 2018

**Today's Progress**: I've quickly enable NPM on the library

**Thoughts:** Following this eggshead tutorial (https://egghead.io/lessons/javascript-creating-the-library-and-adding-dependencies) I've added support to NPM. Less than one hour of code but as tomorrow I'm off I'll be able to balance today's lacks.

**Link to work:** same repo than Day 1


### Day 3: April 18, 2018

**Today's Progress**: I've built the architecture for the project

**Thoughts:** I kinda dropped off the eggshead tutorial in order to spend more time building actual code. I did an OOP structure which went quite smooth.

**Link to work:** same repo than Day 1


### Day 4: April 19, 2018

**Today's Progress**: Managed to trigger events at the desired timing

**Thoughts:** Worked for the click event and used smoothscroll to simulate scroll.

**Link to work:** same repo than Day 1


### Day 5: April 20, 2018

**Today's Progress**: Code the hover event

**Thoughts:** Faced some serious difficulties, because of the `isTrusted` property on the events that is not possible to hack:
https://developer.mozilla.org/en-US/docs/Web/API/Event/isTrusted
Found as a fallback the possibility to get the CSS `:hover` properties and apply them directly on the element.

**Link to work:** same repo than Day 1


### Day 6: April 21, 2018

**Today's Progress**: factorize the hover event

**Thoughts:** I start to doubdt about the architeture I set up for the key construction. I eventually managed to simulate all the style of the hover effect.

**Link to work:** same repo than Day 1


### Day 7: April 22, 2018

**Today's Progress**: Manage the after hover event

**Thoughts:** Just a dumb style reset. I really need to add a cursor.

**Link to work:** same repo than Day 1


### Day 8: April 23, 2018

**Today's Progress**: Added a moving cursor

**Thoughts:** Although I can't move it to the right position. I might need some sleep.

**Link to work:** same repo than Day 1


### Day 9: April 24, 2018

**Today's Progress**: Refactorize event trigger

**Thoughts:** I mainly cleaned up what I did so far. There is still much to clean up. I separated the events trigger and the timeline execution.
I'm thinking about declaring events with no incidence on chronology.
I'm also procrastinating on turning my demo into a real JS library.

**Link to work:** same repo than Day 1


### Day 10: April 25, 2018

**Today's Progress**: Add possibility to declare events relatively or not on the timeline

**Thoughts:** I feel like taking a break from this project. I should focus on learning better ES2015 AND library crafting (npm) because I feel stuck.

**Link to work:** same repo than Day 1


### Day 11: April 27, 2018

**Today's Progress**: Reset mouse position to a default position

**Thoughts:** I have not commited yesterday, I think I got a lit late on my progress—I'll try to do better this weekend!

**Link to work:** same repo than Day 1


### Day 12: April 28, 2018

**Today's Progress**: Get hoverable elements, store their positions so it trigger the hover pseudo class when mousemove occurs

**Thoughts:** Complexity starts to grow. I think it's rather clean. I should dive more into ES2015 and react now.

**Link to work:** same repo than Day 1


### Day 13: April 29, 2018

**Today's Progress**: Worked on the hover mechanical : now the mouse movement trigger dynamically the hover styles.

**Thoughts:** I did some tutorials on ES2015 beside.

**Link to work:** same repo than Day 1


### Day 14: April 30, 2018

**Today's Progress**: Managed the state when the mouse leave the hoverable element (reset style).

**Thoughts:** I have not worked one hour. Not event 30 minutes. More like 15 😓. My work is now accessible online on netlify.

**Link to work:** same repo than Day 1


### Day 15: May 1, 2018

**Today's Progress**: I passed the constructor to ES6 Classes

**Thoughts:** I spent some time learning features of ES6 like classes. I'm stuck right now : I don't know how I bind a instance of one class (key) to the instance of another class (timeline). I passed 'this' as a parameter to retrieve the scope between classes but it just don't work that way.
I learned a lot today!

**Link to work:** same repo than Day 1


### Day 16: May 2, 2018

**Today's Progress**: I changes the library into a ES6 module

**Thoughts:** This was a bit tricky — I though it would be quicker. But I used the ES2015 modules which are great!

**Link to work:** same repo than Day 1


### Day 17: May 3, 2018

**Today's Progress**: I did something new today. I worked on a codepen, trying hard to draw the original eurovision opening logo.

**Thoughts:** I need to understand better css vars and masking / cliping.

**Link to work:** https://codepen.io/antoinelouis/pen/vjJLNY


### Day 18: May 4, 2018

**Today's Progress**: I did some refactor on the library.

**Thoughts:** I finish the ES2015 class. Still fresh, there are many concepts I've not assimilated well enough. I need practice to fully get it in mind.
I'll switch to ReactJS.

**Link to work:** same repo than Day 1


### Day 19: May 8, 2018

**Today's Progress**: Went back on codepen

**Thoughts:** I took a break to start learning React.js + watched a few videos by Ana Tudor to get inspired on the use of math in CSS.

**Link to work:** https://codepen.io/antoinelouis/pen/WJdKam?editors=1100


### Day 20: May 9, 2018

**Today's Progress**: Codepen done!

**Thoughts:** My trigonometry and algebra knowledge were a bit dusty, but I'm happy I succeed at that codepen. Hopefully I'll do many others and it will get easier.

**Link to work:** https://codepen.io/antoinelouis/pen/WJdKam?editors=1100


### Day 21: May 14, 2018

**Today's Progress**: New Codepen : React mastermind

**Thoughts:** I skipped a few days but hey! I'm back on track! I really want to start React and I'm scared AF. Hopefully it will click soon!

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 22: May 15, 2018

**Today's Progress**: Progress on React

**Thoughts:** I built my first component with React! I'm still painfully gathering around all the knowledge I need to run the mastermind game I'm working on but I have the feeling it's going on the right direction!

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 23: May 16, 2018

**Today's Progress**: I continue my progress on @reactjs : I used state / props to update my UI! 
Another step done, soon my first mini project will be ready!

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 24: May 17, 2018

**Today's Progress**: Progress on React

**Thoughts:** I spent some time studying and observing examples of React apps on the React official documentation. I have a better understanding on how to structure component and pass data through them.

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 25: May 18, 2018

**Today's Progress**: Progress on React

**Thoughts:** Almost done with my first #reactjs app!

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 26: May 20, 2018

**Today's Progress**: I'm done with my very first React.js App!

**Thoughts:** I've had troubles managing history, I think here is where libs like Redux would help (In any case I have to figure out what it makes) and I'll do more detailed and complexe apps with React to get comfortable with it.

**Link to work:** https://codepen.io/antoinelouis/pen/YLjEoK?editors=1010


### Day 27: June 11, 2018

**Today's Progress**: Back on the race

**Thoughts:** I've been seriously struggling to get back on track lately after a hackathon + heavy load of work.
I've started making my next portfolio.

**Link to work:** https://github.com/antoinelouis/portfolio-2019

