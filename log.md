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



##<h1>Day 6: January 11, 2017</h1>

###**Today's Progress**
* Codeacademy Java - Conditions and Control Flow

###**Thoughts:**
"Practice Java" has been on my to-do list for days now, and I've put it off because I love web dev so much at the moment. I know it seems as though I jump around a lot, but that's how my diploma curriculum is. Granted, Javascript and .Net Core isn't part of my curriculum, learning new things and doing new things gives me the kicks. Should probably have some kind of system to make sure I don't completely abandon any technology.

###**Study Notes:**
**Java Boolean Operators**
* `&&` **"AND" operator**. Will return true if and only if **both sides** of the operator are **true**. Example of use: `(false && true)` //returns false; `(4 < 5 && 7 <= 7)` //returns true
* `||` **"OR operator"**. Will return true if **at least one** of the two sides of the operator is true. Example of use: `(2 > 1 || 3 > 4)` //returns true
* `!` **NOT operator**. Inverses the result. Example: `!(6 =< 6)`//returns false; `!(8 > 9)`//returns true.
* **Precedence:** `!` -> `&&` -> `||` 
```Java
System.out.println( !(false) || true && false);
// returns true
// 1. "!(false)" returns true, so the argument becomes "true || true && false"
// 2. "true && false" evaluates to false, so the argument becomes "true || false"
// 3. finally, "true || false" evaluates to "true".
``` 
* **If-Elseif-Else** 
```Java
		if (round > 12) {

			System.out.println("The match is over!");

		} else if (round > 0) {

			System.out.println("The match is underway!");

		}	else {

			System.out.println("The boxing match hasn't started yet.");

		}	
```
* **Ternary Conditions:** If/else shorthand. Syntax: `char result = (boolean expression) ? 'valueIfTrue' : 'valueIfFalse';`.
* **Switch case:** 
```Java
int restaurantRating = 3; 

switch (restaurantRating) {

    case 1: System.out.println("This restaurant is not my favorite.");
      break;

    case 2: System.out.println("This restaurant is good.");
      break;

    default: System.out.println("I've never dined at this restaurant.");
      break;
}
```


##<h1>Day 7: January 12, 2017</h1>

###**Today's Progress:**
* Codeacademy Java - Object Oriented Programming

###**Thoughts:**
Bless the lord, I know what methods do now!

###**Study Notes:**
* Methods are pre-defined sets of actions - they give a program its liveliness, it tells the program to _do stuff_



##<h1>Day 8: January 13, 2017</h1>

###**Today's Progress:**
* Codeacademy Java - Data Structure

###**Thoughts:**
Codeacademy is slacking a little here in this last module. Instead of taking time to explain For Each loops well enough for users to create For Each loops on their own, they give the entire snippet and basically asks users to copy and paste the code inside the editor. I've tried to make sense of it, and will include an explanation in the study notes section below.

###**Study Notes:**
* **For loops**, like most _loops_, _repeat_ a set of actions that are defined inside them. Here is an example:
```Java
for (int counter = 0; counter < 3; counter ++) {
	System.out.println("The counter value is " + counter); //display the sentence "The counter value is [the current value counter in that particular repetition]"
	
//1. For loop runs for the first time. Program prints "The counter value is 0". After counter ++, the value of counter is now 0+1=1. 1 is less than 3, so the loop repeats.
//2. For loop runs for the second time. Program prints "The counter value is 1". After counter ++, the value of counter is now 1+1=2. 2 is less than 3, so the loop repeats.
//3. For loop runs for the third time. Program prints "The counter value is 2". After counter ++, the value of counter is now 2+1=3. 3 is **not** less than 3, so the loop stops.
}
```
To split it up into easier to manage chunks, this is how it works: the program knows how many times the action (`System.out.println("The counter value is " + counter);`) from the following part of the code: `for(int counter = 0; counter < 3; counter++)`. `int counter` creates an integer variable named "counter" and assigns its starting value as '0'. This `counter < 3` bit says "repeat the action while the value of counter is less than 3". `counter++` tells the program to add 1 to "counter" every time the action in the code finishes one repetition. Each repetition runs in that order: check if counter is less than 3. If it is, then run the action inside the loop, finally add 1 to counter. If it is not, the loop stops.

* An `ArrayList` is essentially a data structure that stores a list of values. Here's how it looks like, and how to do some stuff with it:
```Java
ArrayList<Integer> quizGrades = new ArrayList<Integer>(); //create a new arraylist called "quizGrades" that stores Integers.

quizGrades.add(95); //add an integer value of "95" into the quizGrades array list 
quizGrades.add(87); //add an integer value of "87" into the quizGrades array list 
quizGrades.add(67); //add an integer value of "67" into the quizGrades array list 

System.out.println(quizGrades.get(0); //Print the value inside the 0th index of quizGrades array list. In this case, since arrays begin its numbering (indexing) from 0, 0 refers to the first entered value in the array list, the progarm will print out "95",.

quizGrades.add(0, 100); //add the value of "100" in the 0th position of the array. When you do this, "100" will be at the first (0) position in the array list. Everything else will get pushed down by one position, so "95" is now in index 1, the 2nd position.

System.out.println(quizGrades.get(0)); //after the adding, this line will print out "100" 

//To print out all the values in my ArrayList:
for (int i = 0; i < quizGrades.size(); i++) {

    System.out.println( quizGrades.get(i) ); //print out the value at the index numbered in the current value of "i". So if the value of i=2, the value printed out would be "87". Remember, we added "100" to the top of our array list, so the 3rd value(indexed at 2) becomes 87 instead of 67, since the positions are pushed downwards.

}
```

* For-Each loops:
```Java
for (Integer grade : quizGrades){ //for every integer (that we'll name "grade" temporarily) inside the quizGrades array list, -
    System.out.println(grade); //- do this.
}
```

* A `HashMap` is another data structure that can store a list of values, but with "keys" assigned to these values. It works and looks a little like the `ArrayList`. There are two parts of the setup. The first part of the setup determines the data type of the key, and the second part determines the data type of the values. So if I wanted to set up a list of my friends'ages, and I want to be able to access my friends' ages by "entering" their names, this is how my HashMap would be set up:
```Java
HashMap<String, Integer> myFriends = new HashMap<String, Integer>(); //set up a HashMap named "myFriends" that have String values as "keys", and Integer values as, well, the main values that I want to keep track of. This is for the "name" and "age" of my friends

myFriends.put("Mark", 24); //add a new record for a friend named Mark, who's 24.
myFriends.put("Cassandra", 25); //add a new record for a friend named Cassandra, who's 25.
myFriends.put("Zenas", 21); //add a new record for a friend named Zenas, who's 21.

System.out.println( myFriends.get("Zenas") ); //print out the age for my friend Zenas. Notice we use the first part, the string/name value of the setups, as our "indexes". In other words, I can access my friends' ages by inserting their names.


System.out.println( myFriends.size() ); //print out the number of records in my HashMap

//To print all of the available data I have in my HashMap:
for (String name: myFriends.keySet()) {

    System.out.println(name + " is age: " + myFriends.get(name)); 
}

```



##<h1>Day 9: January 14, 2017</h1>

###**Today's Progress:**
* Rails Tutorial - Chapter 1

###**Thoughts:**

###**Notes:**
Setting up a new file:
* Command: `$rails new appname`
Next steps:
* Change dependencies in Gemfile
* Build dependencies using `$bundle install`
Test run on server
* `$rails server` or `$rails server -b $IP -p $PORT` if on C9. use `$echo $IP` or `$echo $PORT` to get numbers
* If on local server: Paste URL (http://0.0.0.0:3000) in address bar. If on C9, window->share->application->open
MVC:
* Change code in controller` 
* Change routing in config/routes.rb -> syntax: `root 'controller_name#action_name'



##<h1>Day 10: January 15. 2017</h1>

###**Today's Progress:**
* More rails, plus creating a new site following [this tutorial](https://medium.com/@riklomas/how-to-create-a-simple-jobs-board-in-ruby-on-rails-even-if-youve-never-coded-before-9b296c4df483#.4jbrj8fh3)

###**Thoughts:**
So glad I've decided on a language to work with. Rails is so powerful, it's ridiculous. Hopefully by the end of the week, I'll be able to deploy a mvp of a project I have to do for college.

