## What is "legacy" code?

Note:
Ask the audience?
We intentionally haven't used the word legacy in the title of this bootcamp - because it is so loaded.

--

## A pejorative term?

+ Old
+ Dirty
+ Hard to work with

Note:
These are all common perceptions - and perhaps what the audience will have suggested.

--

## Where does it come from?

+ We write it
+ Anything that's existing
+ The code you wrote before lunch

Note:
Expect the audience to suggest it comes from elsewhere.
Emphasise our role in creating it.

--

> The existing code is quite good.

+ _No Developer Ever_

Note:
All pre-existing code is typically regarded as poor quality.

--

## There is a lot of existing code

+ Google is two billion LOC (lines of code)
+ Auto Trader has 42 MLOC (17 MLOC Java, website is 1.5 MLOC)
+ 111 billion lines of new code created every year ([2017 estimate](https://cybersecurityventures.com/application-security-report-2017/))
  + They are not all good lines of code
+ [Lines of code infographic](https://informationisbeautiful.net/visualizations/million-lines-of-code/)

--

> Which idiot wrote this?

+ `git blame Legacy.java`

Note:
Use of term idiot is intentional to indicate the strength of feeling around these issues.
Talk about appropriate language?
Mention `git blame` and the use of version control for auditing.

--

<img height="600" src="{{ site.github.url }}/images/your-country-wants-you.jpg"/>

Note:
The emphasis here is not to be so quick to judge - we are often the culprit.

--

## Reasons for __bad__ code

> The road to hell is paved with good intentions...

\- proverb

--

## Clever is a circular scale

<img src="{{ site.github.url }}/images/smart_dumb.png"/>

Note:
We do the wrong thing even with the best of intentions.

--

### The second system effect

> An architect's first work is apt to be spare and clean. He knows he doesn't know what he's doing, so he does it carefully and with great restraint.

> The general tendency is to over-design the second system, using all the ideas and frills that were cautiously sidetracked on the first one.

<div style="font-size: 0.25em">\- The Mythical Man-Month - Fred Brooks</div>

Notes:
YAGNI - Extreme Programming Installed, Ronald E. Jeffries,

--

### Excuses

+ Not enough time
+ Blame the tools
+ Blame the people
+ We didn't know what we wanted when we started

--

## Embrace the legacy

<img height="500" src="https://i.imgur.com/ov1XeHo.jpg"/>

Note:
We need to take ownership of legacy code and help ensure we don't leave behind a _Big Ball of Mud_ for those who follow.

---

## Exercise prep

* Go here:
 
 https://github.com/MCR-Digital/apprentice-boot-camp-improving-code
* Click the **Fork** button to make your own copy of the repository
* `git clone https://github.com/<YOUR_USERNAME>/apprentice-boot-camp-improving-code`

--

## Make sure the tests pass
  * Java folk
    * import the `exercises/java` directory using ‘Import project from external model’
    * Choose ‘Use default gradle wrapper (recommended)’
  * Other languages
    * ask your mentors how to go about it

--

## Reading code

+ Possibly your most important skill
+ Great source of learning (if you read good code)
+ Good developers spend ~10x as long reading
+ Developers who only write create debt

--

## Codebase

Refactoring codebase called ‘Trivia’

Notes: Used in ‘Legacy Code Retreat’ workshops

--

## Exercise: Read and try to understand the code (15 mins?)

+ Look at Game Runner and Game
+ Do not change the code
+ Do try to understand
+ Drawing things will help… flow chart?

--

## Recap - What have we discovered?

* What does the code represent?
* What concepts do we have?
* How does it work?
* What do we think of it?

--

## Here's one I made earlier... (15 mins?)

<backgroundimage>{{ site.github.url }}/images/Blue_peter_badge.jpg</backgroundimage>
<backgroundimageopacity>0.25</backgroundimageopacity>
<!-- .slide: data-background-repeat="repeat" -->
<!-- .slide: data-background-size="100px" -->

+ Groups of 4 or 5
+ Use your best cutting and sticking skills to make a physical copy of the game

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
    <img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" />
</a>
<div style="font-size:0.25em">
This work is licensed under a 
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</div>

--

## Review - what did we end up with?