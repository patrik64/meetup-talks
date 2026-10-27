# Incremental parsing with Tree-sitter

28.10.2026 - ViennaJS  
https://www.meetup.com/viennajs/events/316696137

Demo apps:

https://github.com/patrik64/tree-sitter-showcase  
https://github.com/patrik64/tree-sitter-json  

Links:

https://tree-sitter.github.io  
https://github.com/tree-sitter/tree-sitter  

https://github.com/hydro-project/rust-sitter



To recreate the application from the beginning of the talk (code-analyzer) using Claude follow these steps:

1. create a folder called code-analyzer and open Claude Code in it
2. set the model to Sonnet 5.5
3. set the effort to low
4. use the following prompt:  

"Create a SvelteKit application using tree-sitter and chart.js libraries that accepts a folder of an existing project as input and does the following:  
	- parses all typescript and javascipt files using tree-sitter. 
	- provides detailed statistics about the code:  
		- number of js and ts files  
		- number of lines of code  
		- for each js or ts file - number of lines of code, number of functions, number of imports etc.  
		- create a graph view where vertices are js or ts files and connect them using import directives  

Add anything else you can think of that might help a user get a good grasp about the project."  
