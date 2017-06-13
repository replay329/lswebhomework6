# Homework #6

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.



	* Functions 
    
are reusable blocks of code instructions with a name that acts as a shortcut, which then does specific tasks or procedures, and returns (or gives you back) a value. You give the function further information in order to specify what you want the function to do. 

You can use prewritten libraries of functions to save time, or you can write your own function to help you to create your program, just like you can write your own set of instructions to another person on how to do something and what is needed in order to do it. 

EXAMPLE: declare a function called ALLOWANCE. Whether a kid GETS an allowance - and how much they get - depends on a variety of different circumstances and conditions. 


	* Parameters 

set out the characteristics or guidelines for what matters in the function - like a set of placeholders.

This could actually be as simple as the colour or size of something onscreen, or which font and fontsize to use, or how much space to make for another part of the program to use. 

But it could also be a set of complex values which are being sent back and forth through other coding routines so that you can re-use the function in different ways over and over again. 

EXAMPLE: the ALLOWANCE function requires parameters like CASH AMOUNT and FREQUENCY and WHICHPARENTWILLGIVE, these can be subject to change depending on other behaviour parameters like GOOD GRADES, CLEAN BEDROOM, POLITENESS, HOME ON TIME etc. 


	* Arguments 
    
are often very similar to a parameter, but they're a value or set of more specific named details which can interact with the parameters to allow the function to make decisions and operate.  

The argument can only be sent in one direction through the computer program so the argument's values can't be changed, unlike a parameter which can be sent back and forth and change its values. 

EXAMPLE: our ALLOWANCE function could say there are 2 parents called DAN AND JO (parameters) who have a kid called SAM (argument) who has been good, studies hard, gets home before curfew and is polite to people. (All arguments). They also have a kid called BOBBY (argument) who is terrible on all of these things (argument). And SAM and BOBBY would like an ALLOWANCE - please and thank you very much!


	* `if` statements 
    
tell the computer which conditions or circumstances need to exist or take place in order to "then" do a specific action or "else" do something different.   

So it's like saying when things are exactly like ABC, do XYZ, but should things NOT be exactly like ABC, instead do PQR.

EXAMPLE: 

IF SAM does get GOOD GRADES, THEN ALLOWANCE will be increased by X amount. 
IF BOBBY doesn't CLEAN BEDROOM THEN ALLOWANCE will be reduced by Y amount. 

or even 

IF all BOBBY behaviour parameters have arguments that are FALSE (all bad behaviour arguments) THEN ALLOWANCE = £BIGFATZERO

ELSE 

IF all SAM behaviour parameters have arguments that are TRUE 

THEN MYALLOWANCE = £KACHINNGGGG!!

you could even recognise that IF JO is broke THEN ALLOWANCE will be paid by DAN at the weekend!






2. Install Node and NPM.  NPM comes packaged with Node. https://nodejs.org/en/download/

DONE

3. Download (clone) this project folder from GitHub.

DONE

4. Navigate into the downloaded folder using Terminal(Mac) or Command Prompt(Windows).  `ls`(Mac), `dir`(Windows) and `cd <directory_name>` are the commands you need to navigate around.

DONE

5. Once you are in the folder type the command `npm install`.  This will fetch all of the needed requirements for the project.

DONE

6. Run `npm test` to run the automated tests.  At first all of the tests will be broken.  You will fill out the functions in `exercises.js` to make the tests pass.

DONE DONE DONE DONE DO-DONE DONE DO-DONE  (IMPERIAL MARCH, BABY!)



#### Congratulations on finishing Homework #1!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com
