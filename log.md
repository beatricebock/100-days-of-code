# 100 Days Of Code - Log

## <h1> Day 0: January 5, 2017 </h1>

###**Today's Progress**: 
* JavaScript Arrays
* Javascript Functions
* Javascript Local and Global Scopes
 
###**Thoughts:** 
I've never taken time to learn JavaScript properly, but I've recently learned that JS is extremely important and versatile. So glad FCC teaches us about multidimensional arrays, which was only lightly touched on in my Diploma course. Also, it's really great how the challenge requires us to use GitHub, because now I'd have good, practical exercises to practice using GitHub.

###**Study Notes**:
####**Arays**
* `.push(//value)`: **add** a new value to the **end** of an array.
* `.pop()`: **remove** a value from the **end** of an array. Example of use: [1, 4, 6].pop()
* `.shift()`: **remove** the **first value** from an array. Example of use: removedFromMyArray = myArray.shift()
* `.unshift(//value)`: **add** a value to the **beginning** of an array. 

####**Functions**
* **A sample function**, and how it's called:
```javascript
//create new function
function reusableFunction() {
  console.log("Hi World");
}
//call function
reusableFunction();
```
* **Functions with parameters**: functions with initialized variables (parameters = variables). These variables will later be replaced with actual values when we call these functions. A sample:
```javascript
function testFun(param1, param2) {
  console.log(param1 + param2); //outputs the sum of param1 and param2
}
testFun(5, 6); //output is 11
```
* **Global Scope**: variables defined **outside** of any function, and variables defined **without** `var` are **global variables** with a **global scope**. this means they **can** be accessed from anywhere in the JS code.
* **Local Scope**: functions parameters and variables defined **inside** of any function with `var` have a **local scope**. This means they **cannot** be accessed from **outside** the function in which it was defined.
* **Local vs Global Scopes**: it's possible to have local and global variables with the same name. In this case, the local variable is prioritized. For example:
```javascript
var someVar = "Hat";
function myFun() {
  var someVar = "Head";
  return someVar;
}
//"Head" is the value returned because the local variable in myFun is prioritized. "Hat" is ignored.
```
* `return` can contain arguments. Example: `return x + 3;`


###**Links to work:** 
1. [Challenge: Shopping List](https://www.freecodecamp.com/challenges/shopping-list)



## <h1> Day 1: January 6, 2017 </h1>

###**Today's Progress**: 
* Completed the What is ASP.NET Core module
* Completed the HTML and CSS Basics module
* Followed along the tutorials with a local project and uploaded the notes and files to GitHub.
 
###**Thoughts:** 
There's a lot about learning technology that changes so much (so many resource versions since July 2016) that really teaches us to be versatile. Since quite a bit has changed with the extensions and resources used in the tutorials, I've had to dig around a little bit and train myself to avoid copying and pasting each line of code exactly in the tutorials. It's so important to do exercises on your own after watching tutorials; it really helps to strengthen and cement the concepts learned.

###**Link to Work**
[My Project Repo](https://github.com/trisssss/pluralsight-mvc-theWorld)



## <h1>Day 2: January 7, 2017</h1>

###**Today's Progress**:
* Completed the Javascript module

###**Thoughts:**
jQuery has alwyas been a mystery to me. It's still a mystery, and since the versions have changed since July 2016, there's quite a bit of syntax change that I've got to figure out myself. The AHA! moments are endless with this course.

###**Study Notes**
**jQuery**
* `$` is a selector. The selectors use the same syntax as CSS. For example, to select an element with an ID of "class", we write `$("#class")`. We can also select multiple classes or ids at one time. Example: `$(".class1, .class2")`
* Sample `.click` function:
```javascript
$("#button").click(
  function(){ 
   alert.("You clicked a button!");
  }
 )
```
* `.text` changes the text of the selected element
* `.toggleClass` adds and removes a class from the selected element.

###**Link to Work**
[My Project Repo](https://github.com/trisssss/pluralsight-mvc-theWorld)


## <h1>Day 3: January 8, 2017</h1>

###**Today's Progress:**
* Halfway through the MVC6 Module

###**Thoughts:** 
Holy crap this is frustrating. There's so much that's changed since the video was made, I spent 60% of the time figuring out workarounds/proper methods for the new versions. And bruh we need grunt to retrieve packages for jQuery Validate, and it's not even working??? Starting to realise that courses like these aren't exactly walkthroughs; they explain concepts, help you figure out what you need, then send you off to trudge through on your own.

###**Link to Work**
[My Project Repo](https://github.com/trisssss/pluralsight-mvc-theWorld)



## <h1>Day 4: January 9, 2017</h1>

###**Today's Progress:**
* JavaScript Queue
* JavaScript Boolean
* JavaScript if-else statements

###**Thoughts:**
I like coding. It relaxes me. It also relaxes me to learn things. No work done on the repo today, though.



##<h1>Day 5: January 10, 2017</h1>

###**Today's Progress:**
* Started to listen to coding podcasts (StartHere.fm) during commute. Listened to podcast [#30: How to Become an Advanced Beginner](https://soundcloud.com/starthere-webdev/30-advanced-beginner)
* Framework of personal portfolio

###**Thoughts:**
Found a way to listen to podcasts during commute. I really wish I'd done this sooner, because being stuck in 30 minute nightmare traffic isn't so bad when you're listening to people talking about how to learn code. I even commented on the post after being super inspired and comforted. Crazy thing is, Dain of StartHere.fm's (miraculously) reached out to _me_ and took the time to talk to me and helped me learn quite a few things. He even offered to be my mentor, which is _NUTS_. I've never had a mentor, I've always wanted one, and BAM. I would highly recommend anyone starting out to listen to Dain's podcasts, they're super informative and no-bullshittery. 

####**Key takeaways from this episode**
* **It's okay if you're slow. It'll take a couple years and lots and lots of tutorials before you can do anything substantial**
This little golden nugget was phenomenal for me because I've been coding for a couple of years now, bouncing around languages as per my diploma curriculum and getting positively terrified because I still don't know enough to do anything substantial. To have someone who's estalbished in the industry to tell me to "Slow down, take your time, you'll be ready when you're ready" lifted off tons off my shoulders.
* **Listen to videos about the technology even though you won't understand shit**
It never occured to be to spend time and be clueless enough to let my brain just get used to the jargon and technical phrases. This is something I'll start doing for sure. Just a couple days before, I lamented about how tutorials like PluralSight aren't meant to be walkthroughs, but instead tools to let us know what exactly we need to build certain things or to have a certain skill. Dain puts it this way: "Let yourself learn the context, and understand the context." Then, BAM, holy shit that's exactly what I needed at this point, because I feel so lost and I don't even know where to begin, but here's this dude who _gets it_.
* **Read tons of tutorials before beginning a walkthrough**
It makes sense, because we'd "let our brains find the patterns" between the tutorials. Once we see a pattern, we can understand the workflow of any given technology.
* **Just write**
After listening, I heeded his advice and just wrote code. I finally finished a framework of my portfolio which I've put off since the day I saw the challenge on FCC. Even though I was rusty, it was extremely therapeutic to just realise that I _can_ create something. There's lots left to learn, but once we get over that first hill _And just start coding_, we've taken leaps and bounds to make ourselves better learners.

> "I find too one piece of magic in life, that if you focus on helping other people, all your problems magically disappear" - Dain 

This is kind of philosophical, but it makes a ton of sense. For example, by helping someone else solve a problem, you solidify your knowledge. That's from a programmer standpoint anyway, I'll be using this little piece of wisow for loads of other things from here on out.

StartHere.fm changed my life, I think.

###**Link to Work:**
[Personal Portfolio](https://codepen.io/trisssss/pen/VmGmvj/?editors=1100)
