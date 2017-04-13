# Front End Developers JavaScript Exercises

All exercices must be placed in to dedicated GitHub repository under separate folders.

## Simple exercices

1. Create JS function to invert string (example: "exercise" => experted output: "esicrexe")
2. Write JS function that generates all combinations of a string (example: "cat" => expected output: c, ca, cat, a, at, t)
3. Create JS function to find first unique charater in string (example: "asdasfafghj" => expected output: "d")
4. Write JS program to output time every second (expected output: "11:50:51", "11:50:52", "11:50:53", ...)
5. Write JS program to compute the sum of an array of integers (example: [1,2,3,4,5,6,7] => expected output: 28)

## Advanced exercices

1. Create JS program with function chaining (example: name("John").go("Shop").buy("Food") => expected output: "John goes to shop to buy food");
2. Create JS function that converts array of objects like that: 
 example: 
 [
	{id: 1, name: "dog", parentId: null}
	{id: 2, name: "Buddy", parentId: 1}
	{id: 3, name: "Daisy", parentId: 1}
	{id: 4, name: "cat", parentId: null}
	{id: 5, name: "Smokey", parentId: 4}
	{id: 6, name: "Oscar", parentId: 4}
 ]
 expected output:
 {
	dog: [
		{name: "Buddy"},
		{name: "Daisy"}
	],
	cat: [
		{name: "Smokey"},
		{name: "Oscar"}
	]
 }
3. Create HTML5 Canvas and using JS draw Rectangle (this must be in HTML file or HTML + JS files) Add button "Create Rectangle" and bind it to the function that creates random width and height rectangle inside of canvas (all rectangles cannot collide with each other or be placed outside canvas)