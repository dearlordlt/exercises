```json
let data = [
	{id="1", animal: "dog", color="black" },
	{id="2", name: "Buddy", age="7" }, 
	{id="3", name: "Daisy", friends: ["cat", "dog"] }, 
	{id="4", animal: "cat", hates="dog" },
	{id="5", name: "Smokey" }, 
    	{id="6", name: "Oscar", hobbyes=[{chess=2, football=4}] }
];

fn(data, {name: "Peter", height="200"})

/**

Write function, witch has two arguments:
1. Array of any objects
2. Single Object

Function should search in array (1) for object (2), 
if identical object or objects are found, it should return their id`s
Else if object (2) is not in array (1) object (2) should be pushed to the end of array and assigned unique id. This new object has to be returned by the function. 

This function should be tested with this example objects:
*/

example1 = { name: "Buddy", age="7" };
/* Should output:  
"2"
*/

example2 = { name: "Oscar", hobbyes=[{chess=2, football=4, racing="???"}] };
/* Should output:  
[
	{id="1", animal: "dog", color="black" },
	{id="2", name: "Buddy", age="7" }, 
	{id="3", name: "Daisy", friends: ["cat", "dog"] }, 
	{id="4", animal: "cat", hates="dog" },
	{id="5", name: "Smokey" }, 
    	{id="6", name: "Oscar", hobbys=[{chess=2, football=4}] },
    	{id="7", name: "Oscar", hobbyes=[{chess=2, football=4, racing="???"}] }
]
*/
example3 = { name: "Smokey", 0:[] };
/* Should output:  
[
	{id="1", animal: "dog", color="black" },
	{id="2", name: "Buddy", age="7" }, 
	{id="3", name: "Daisy", friends: ["cat", "dog"] }, 
	{id="4", animal: "cat", hates="dog" },
	{id="5", name: "Smokey" }, 
    	{id="6", name: "Oscar", hobbys=[{chess=2, football=4}] },
    	{id="7", name: "Oscar", hobbyes=[{chess=2, football=4, racing="???"}] },
    	{id="8" name: "Smokey", 0:[] }
]
*/
```
