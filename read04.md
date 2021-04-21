# Grid Layout

* CSS Grid Layout is the most powerful layout system available in CSS. It is a 2-dimensional system, meaning it can handle both columns and rows.

* To get started you have to define a container element as a grid with display: grid, set the column and row sizes with grid-template-columns and grid-template-rows, and then place its child elements into the grid with grid-column and grid-row.

* Grid Container
The element on which display: grid is applied. It’s the direct parent of all the grid items. In this example container is the grid container.

    <div class="container">
      <div class="item item-1"> </div>
      <div class="item item-2"> </div>
      <div class="item item-3"> </div>
    </div>

* Grid Line
The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column. 

* Grid Cell
The space between two adjacent row and two adjacent column grid lines. 

* Grid Track
The space between two adjacent grid lines.


<br>

# Regex

* Short for regular expression, a regex is a string of text that allows you to create patterns that help match, locate, and manage text. 

* When first trying to understand regular expressions, it seems as if it's a different language. However, mastering regular expressions can save you thousands of hours if you work with text or need to parse large amounts of data.

* The basics of regular expressions 
            Character
            ^	Matches beginning of line	   ^abc	         abc, abcdef.., abc123

            $	Matches end of line	         abc$	           my:abc, 123abc, theabc

            .	Match any character         	a.c	              abc, asg, a2c

            |	OR operator	               abc|xyz	                 abc or xyz

            (...)	Capture anything matched  (a)b(c)         	Captures 'a' and 'c'

            (?:...)  Non-capturing group	(a)b(?:c) 	Captures 'a' but only groups 'c'

            [^...]	Matches anything not contained in brackets	[^abc]	xyz, 123, 1de

            [a-z]	Matches any characters between 'a' and 'z'	[b-z]	bc, mind, xyz

            {x}	The exact 'x' amount of times to match	(abc){2}	abcabc

            {x,}	Match 'x' amount of times or more	(abc){2,}	abcabc, abcabcabc

            {x,y}	Match between 'x' and 'y' times.	(a){2,4}	aa, aaa, aaaaa

            *	Greedy match that matches everything in place of the *	ab*c	abc, abbcc, abcdc

            +	Matches character before + one or more times	a+c	ac, aac, aaac,

            ?	Matches the character before the ? zero or one times. Also, used as a non-greedy match	ab?c	ac, abc
