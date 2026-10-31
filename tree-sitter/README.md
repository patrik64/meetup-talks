# Incremental parsing with Tree-sitter

28.10.2026 - ViennaJS  
https://www.meetup.com/viennajs/events/316696137

slides are in the above [talk.html](https://github.com/patrik64/meetup-talks/blob/main/tree-sitter/talk.html) file, simply open it in your browser.

Demo apps:

https://github.com/patrik64/tree-sitter-showcase  
https://github.com/patrik64/tree-sitter-json  
https://github.com/patrik64/code-analyzer  

Links:

https://tree-sitter.github.io  
https://github.com/tree-sitter/tree-sitter  

https://github.com/hydro-project/rust-sitter


Usually, just before I start my talk, I let Claude create an app while I am doing the talk.  
To recreate the application from this talk ([code-analyzer](https://github.com/patrik64/code-analyzer)) follow these steps:

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

<img width="2918" height="1452" alt="image" src="https://github.com/user-attachments/assets/3937fb8f-275c-4cf3-a77f-9ccb901981a0" />
<img width="2910" height="1496" alt="image" src="https://github.com/user-attachments/assets/86b8f173-c0c7-48b6-9280-934f81881daf" />
<img width="2908" height="1396" alt="image" src="https://github.com/user-attachments/assets/a8ae303d-14ec-444e-b9b9-26140738c355" />
