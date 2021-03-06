---
layout: page
title: Session 4
subheading: Scavenger Hunt, Modeling OOP, Assessment Expectations
---

<div class="goals-agenda">
  <div>
    <h3>Goals</h3>
    <strong>By the end of this session, you will be able to:</strong>
    <ul>
      <li>Define Object Oriented Programming</li>
      <li>Understand how to utilize error messages from git</li>
      <li>model real-world objects and apps by breaking down their attributes and behaviors</li>
      <li>understand assessment expecations</li>
    </ul>
  </div>
  <div>
    <h3>Agenda</h3>
    <ul>
      <li><strong>10 min: </strong>Follow-Ups and Goals</li>
      <li><strong>35 min: </strong><a href="#scavengerhunt">Scavenger Hunt</a></li>
      <li><strong>5 min: </strong>Break</li>
      <li><strong>45 min: </strong><a href="#oop">Object Oriented Programming</a></li>
      <li><strong>15 min: </strong><a href="#assessmentprev">Assessment Expectations</a></li>
    </ul>
  </div>
  <div>
    <h3>Materials</h3>
    <ul>
      <li>Notebook</li>
      <li>Writing instrument</li>
      <li>Laptop</li>
      <li>Headphones & mic</li>
    </ul>
  </div>
</div>

## Housekeeping and Goals
### Wins

- Good survey scores regarding git and github.

### Follow-Ups

- Leaving feedback directly on homework gists. Make sure you're checking them. We'll reach out in slack if we have major concerns.
- Remember to be aware of where you are in your directory structure of the terminal before you clone anything down or start running git commands. Always run ls after cloning
- Capstone is due next Tuesday. Ideally, you're at least on day 4. If not, you're behind.

### Other Notes

- Good commit message format:

```
Add list of mod 0 resources
Remove reference to old blog post
Change data type of age field
Fix spelling mistake
```

- Not good commit message format:

```
Rachel is adding her list of mod 0 resources
old blog post
changed data type for age field
Oops, I need to fix my spelling mistake
```

## Intros, Review, and Icebreaker

<div class="try-it">
  <h3>Intros, Review, and Icebreaker</h3>
  <p>Person with the shortest first name goes first.</p>
  <p>1. Introduce yourself: name, pronouns</p>
  <p>2. What music are you listening to currently, and is there any music that you've found to be helpful when you're studying/programming? </p>
  <p>3. Accountability review: what tangible progress have you made toward the focus skills you identified at the beginning of Mod 0?</p>
  <p>Have extra time? Share what extra things you're doing to get ready to start school at Turing.</p>
</div>

<a name="scavengerhunt"></a>
## Scavenger Hunt

This portion of class was added because mod 1 instructors have noticed some behaviors in struggling students:
* Missing or not understanding directions
  * What strategies can you use to avoid this?
* Not reading error messages/using them to progress on a problem
  * What strategies can you use to avoid this?

In programming, we often need to follow tutorials in order to learn new things. *If you miss even one step,* **you'll get a different end result**.
Your challenge here is to **follow each step very diligently**. There are going to be things that you've already done, and things that you will need help from your old pal google to figure out on your own (I mean, tutorials can't tell you how to do everything right?).

The end goal here is to create a pull request. Something you just did as homework for session 3. Can't be that bad right?? Good luck!

We won't be available for help during this scavenger hunt, however write down the questions and issues you run into. We'll debrief as a group and answer any questions afterwards.

**Note:** The one exception to that rule is if you're asking for clarification on a given step. If you're unsure about what the directions are asking, please reach out in the slack thread.

<div class="try-it">
  <h3>Try It: Don't fork it up!</h3>
  <p>At this point, we'll split into breakout rooms. Everyone should do a fist to five to show their comfort with git. Whoever is the least comfortable with git will share their screen. Whoever is sharing their screen will be called the <span class="vocab">driver</span>. Every other person in the room will be a <span class="vocab">navigator</span>.</p>

  <p>If you are already comfortable with git, your challenge during the breakout is somewhat more difficult: your goal is to focus on your explanations, communication, and ability to gauge whether or not another person understands you.</p>
  <ol>
    <li>Clone down this repo: https://github.com/damwhit/best-foods (do not fork it first)</li>
    <li>Create a new file within the repo called dumplings.txt</li>
    <li>Add pot stickers in snake case to the first line of the file</li>
    <li>Add and commit your changes (what should your message be?)</li>
    <li>List the origin for your repo from the command line</li>
    <li>Do you have access rights to push? why or why not?</li>
    <li>Create a new repo in GitHub called very-best-foods</li>
    <li>Change the origin of your local clone of best-foods to match the new very-best-foods repo you just created in GitHub</li>
    <li>How can you confirm that you changed the origin successfully?</li>
    <li>Push your changes from your local repo to your very-best-foods repo</li>
    <li>Is your local repo in sync with the very-best-foods repo in GitHub? How can you tell?</li>
    <li>In GitHub, change the first line of the readme to say very best foods in PascalCase (save and commit in GitHub)</li>
    <li>In your local clone, add a file called noodles.txt</li>
    <li>In that file, add fettucine alfredo in camel case to the first line</li>
    <li>Save, commit, and push your changes to your very-best-foods remote repo</li>
    <li>Can't push? Why not? ... follow the error message</li>
    <li>Once you've pushed, create another file locally called best.txt</li>
    <li>Add ramen to the 5th line of the file</li>
    <li>Save, commit, and push your changes</li>
    <li>Create a pull request to this directory: https://github.com/damwhit/very-best-foods</li>
    <li>If you followed all of the directions above correctly, you should see no difference between the two repos in the pull request</li>
  </ol>
  <p><strong>Done?</strong> Switch drivers and try the process again!</p>
</div>

### Q and A time

<hr>
## BREAK

Turn off your mics and videos and walk away from the computer. Stand up, stretch, drink water. Do a few sit-ups, squats, push-ups, jumping jacks, arm circles, stress ball squeezes, or whatever else moves your body.
<hr>

<a href="" name="oop"></a>
## Object Oriented Programming

<span class="vocab">Object oriented programming</span>, or OOP for short, is an approach to programming (or a [programmming paradigm](https://en.wikipedia.org/wiki/Comparison_of_programming_paradigms)) where programs are organized as a series of objects.

OOP is very similar to how the world actually works. <span class="vocab">Objects</span> are created from templates that we call <span class="vocab">classes</span>.

A class defines attributes (or properties) and methods (or actions). An object is a very specific instance of a class. For example, if the class were Car, two objects might be David's 2007 Blue Nissan Versa and Grandma's 2014 Silver Nissan Juke. *There is only one of each of them*

<span class="vocab">Attributes</span> contain **data** about a specific object. The information format should be one of the basic data types from Session 1 (string, integer, float, boolean, array, hash).

The names of attributes are generally nouns.

A good question to ask when you're determining what should be classified as an attribute is:

* "Is there any other data that underlies this piece of data?" (you want the answer to be no)

CAUTION: Sometimes, methods will *feel* like they should be attributes. For example: `percent_full` or `volume`.

<div class="try-it">
  <h3>Try It Together: Bottle Class Attributes</h3>
  <p>Follow along as we walk through defining a bottle class with three different bottle objects.</p>
  <b>NOTE</b>: For consistency in this lesson, we're going to stick to the naming convention of <code>camelCase</code>. This will look very Javascript-esque. However, in Ruby land, you'll see <code>snake_case</code>.
</div>

```
Class: Bottle

Attributes:
color (string)
lidType (string)
totalCapacity (integer)
stickers (array)
currentCapacity (integer)
recyclable (boolean)
insulated (boolean)
```

<span class="vocab">Methods</span> define the **behavior** of an object, **actions** that can be performed on that object, or **calculations** that use the object's attributes. Methods are generally verbs (action words or short action phrases).

Methods generally answer the question "What can this thing do?" or "What can be done to this thing?"

A <span class="vocab">return value</span> is the result of a method that performs a calculation.
For instance, a `calculatePercentFull` method could divide the value of a `currentCapacity` attribute from the value of `totalCapacity` attribute. The result of that calculation would be the **return value** for `calculatePercentFull` method.

#### Key Points

* A method performs some kind of work and will almost always **use** or **modify** an attribute
* Anything that does work (calculations) should be a method, not an attribute
  * the result of that work is called the **return value**
* Attributes are generally nouns (99.9% of time)
* Methods are generally verbs (90% of time -- can also be questions OR nouns that are the result of calculations)
  * ie. `percent_full` or `volume` since they require calculation

<a href="" name="notateclasses"></a>
<div class="try-it">
  <h3>Try It Together: Bottle Class Methods</h3>
  <p>Follow along as we walk through defining some methods for our Bottle class.</p>
  <p> What kind of methods can we add? What would their return value be?</p>
</div>

```
Class: Bottle

Attributes:
color (string)
lidType (string)
totalCapacity (integer)
stickers (array)
currentCapacity (integer)
recyclable (boolean)

Methods:
calculatePercentFull (divides currentCapacity by totalCapacity)
refill (subtracts currentCapacity from totalCapacity and then refills that amount)
addSticker (append a sticker item into the stickers array)
changeColor (changes the color attribute)
```

<a href="" name="notateobjects"></a>
<div class="try-it">
  <h3>Try It Together: Defining Bottle Class Instances</h3>
  <p>Follow along as we walk through defining a couple instances</p>
  <p>Make sure that your syntax is correct for each data type: if it's a string, the value below should be wrapped in quotes. If it's an array, each item in the collection should be valid data as well, etc.</p>
</div>

```
Object: Nalgene

Attributes:
color: "Pink"
lidType: "Twist top"
...


Methods:
calculatePercentFull: 800 / 1000 = .8
changeColor: color = "Blue"
...
```

<div class="try-it">
  <h3>Try It (Big Breakout Rooms) (~15 minutes)</h3>
  <p>Person whose first name starts closest to Q will share their screen and choose one of the following classes:</p>
  <ul>
    <li>Vehicle</li>
    <li>Book</li>
    <li>Playlist</li>
    <li>GroceryStore</li>
  </ul>
  <p>Everyone should create a .txt file to work off of following the conventions we used above for defining classes and instances</p>
  <p>As a team, brainstorm at least five attributes (and data types) and five methods (and descriptions) for your chosen class. Each person should be keeping their own copy up to date to use as a reference.</p>
  <p>Person whose first name starts closest to the letter A will suggest an object that is an instance of the class. This is Object #1.</p>
  <p>Brainstorm the values for each attribute of that object.</p>
  <p>Brainstorm the results of each method called on that object.</p>
  <p>Person whose first name starts closest to the letter E will suggest a second object that is an instance of the class. This is Object #2.</p>
  <p>Repeat the brainstorm process for attributes and methods for object #2. </p>
</div>

### Can You Spot the Problem?

What would be wrong with...

* a class called `Turing`
* an attribute called `current_time`
* having attributes for a `Review` class called `one_star`, `two_stars`, `three_stars`, etc.
* a `Senator` class having an array attribute called `senator_names`
* a class called `California`
* having attributes on a `ShoppingCart` class called `item_one`, `item_two`, `item_three`, etc.
* a method on `GroceryStore` called `clean_aisle_seven`
* a `Bottle` class having an attribute called `water`
* a `Chair` class having an attribute called `number_of_chairs`
* a `MenuItem` class with a method called `CustomerSurvey`

<a name="assessmentprev"></a>
## Mod 0 Technical Assessment

This is our final Mod 0 technical session. Your assignment between now and Session 5 is to find 80 minutes  to complete the [Mod 0 Technical Assessment](https://fierce-beyond-34376.herokuapp.com).

<div class="instructions assessmentpreview">
  <h1>SAMPLE INSTRUCTIONS</h1>

  <p>The work portion of the assessment should take you approximately 70 minutes, but we recommend taking an additional 10 minutes to throughly read over the expectations outlined in this document. The timed nature is meant to get you used to working under pressure.</p>

  <p class="important"><strong>First,</strong> fork the assessment checklist. You will use this checklist to ensure that you have met the Mod 0 Technical Assessment expectations.</p>

  <h4>Part I: Creating Directories and Files; Initializing Git and Pushing to GitHub (10 min)</h4>

  <ol>
    <li>Use your terminal to create a directory called <code>...</code></li>
    <li>Inside of that directory, make an empty text file called <code>...</code></li>
    <li>Initialize your directory as a git repository.</li>
    <li>Add your file and commit using the message "Initial commit"</li>
    <li>Create a public repo on Github with the same name.</li>
    <li>Add the remote and push your local repository to Github.</li>
  </ol>

  <h4>Part II: Classes, Objects, Attributes, and Methods (35 min)</h4>

  <ol>
    <li>Inside of <code>...</code>, create a new directory called <code>...</code></li>
    <li>Inside of <code>...</code>, create four files: <code>...</code>, <code>...</code>, <code>...</code>, and <code>...</code><em>(If you're comfortable trying markdown at this point, feel free to use .md instead of .txt).</em> </li>
    <li>Open up <code>...</code> in your text editor.</li>
    <li>Brainstorm one class that might exist in a <code>...</code> and put this at the top of the file.</li>
    <li>List at least four attributes for that class. In parentheses, list the data type for that attribute (string, boolean, integer, float, hash/object, datetime).</li>
    <li>List at least four methods for that class. In parentheses, explain what the method does, including the names of the attributes that it uses or modifies.</li>
    <li>Save your file.</li>
    <li>Add and commit your changes for this class.</li>
    <li>Open up <code>...</code> in your text editor.</li>
    <li>At the top, type the name of an object that is an instance of your class.</li>
    <li>List the values for each attribute.</li>
    <li>List the results of the method being called for this specific object.</li>
    <li>Save your file.</li>
    <li>Add and commit your changes for this class.</li>
    <li>Repeat steps 3-8 with <code>...</code></li>
    <li>Repeat steps 9-14 with <code>...</code></li>
    <li>Push your changes to GitHub.</li>
  </ol>

  <h4>Part III: Program Specific Challenge (25 min)</h4>

  <ol>
    <li>Open up your <code>...</code> file in your text editor.</li>
    <li>You'll be given directions for some exercises that are program specific. Looking for something to study? Check out session 1 on data types and variable assignment. The capstone is also a good resource.</li>
    <li>If you are really solid with data types and variable assignment, it shouldn't be too bad</li>
    <li>Save your file.</li>
    <li>Add and commit your changes.</li>
    <li>Push your changes to Github.</li>
  </ol>

  <h4 class="important">Done?</h4>
  <p>There is a link to a google form where you'll submit your mod 0 assessment repo at the end of your checklist</p>
</div>

### Other faq's:
* Can I update my work after I've committed a file?
  * Yes, please do. Update and commit away!
* I messed up my commit message. Should I fix it?
  * No, mistakes happen. We don't want you wasting time on that. Just be more diligent on the next commit

Be sure to fill out the survey from your project board!

Also, capstone is due next Tuesday. Ideally, you're at least on day 4. If not, you're behind.
