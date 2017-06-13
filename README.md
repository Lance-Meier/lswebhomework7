# Homework #7

## Instructions
---
1. Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old.  Doing this will help you quickly discover any holes in your understanding.  Ask your questions on Slack.
		
	* Array - An array is essentially a list of different values, designated by brackets ex. [1, 2, 3]. Each value in the array has its own index number as well so can be called in a function or var by calling out the array and its array index number (0 indexed) to pull the specific value. You can also make arrays of arrays! Whoa!
    
	* Object - An object in general, is an entity, that has properties that make up the object. For example a Shoe in js might be defined as an object with this structure:
    
    var Shoe = {type: sneaker,
                size: 10,
                color: red,
                price: 20};
                
     The information in this object can be accessed using either . or bracket notation and critera can be removed or added using the delete function or by using the general assigner = to update or add a new value is the object criteria isn't there yet.
     example:
     
     shoe.material: leather;
     
     this will add the shoe material criteria to the object.
     
     
	* Method - A method is a function of an object . It's just like a normal function, but the function is the PROPERTY of an object.
        Ex lanceObject = {
            function 1 (parameters),
            function 2 (parameters),
            function 3 (parameters)
        }
        This object is made up of 3 methods


3. Fork and clone this repo.  When you need to commit use the following commands.
		
	* git status
	* git add --all
	* git status
	* git commit -m "your commit message"
	* git push origin master


4. Move into the `lswebhomework7` folder in your terminal and run `npm install` 


4. Make the tests pass! (Use `npm test`)




#### Congratulations on finishing Homework #7!
Apply to our full-time or part-time immersive program to learn cutting edge technologies that are used by top technology companies around the world.

Our part-time and full-time courses are 13 intense weeks of focused study on the most relevant technologies.  

Class sizes are small to ensure that each student gets individual attention from our world class instructors to help them succeed.  We also provide career support both during and after the course to help you succeed.  We are committed to your success.

For more information visit: https://www.lambdaschool.com
