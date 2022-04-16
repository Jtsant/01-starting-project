# Styling-React-Components-New-Project  
## Day 21  
After taking as granted a new project i will be focusing now on how to set dynamic inline styles to my components. This method although is not advised but i will be testing it so that i get to know how it is done. In my new file CourseInput.js i will add styling on the label and input so that when i make an empty entry the background color of my text and label changes so that to give the user information that it is empty. My file then transforms like this ![Screenshot_1](https://user-images.githubusercontent.com/90603989/163435104-5a2215cc-c539-428d-a632-6b74e97c217c.png)  
Now in order to set css classes dynamically i will work on the CourseInput.js file. I can use a template literal by implementing backticks. This allows me to construct a string because whatever is typed between backticks is treated as a string. With this simple syntax i can dynamically add or remove classes. ' ` css class selector ${} `'. My file then transforms to this ![Screenshot_1](https://user-images.githubusercontent.com/90603989/163674721-52b7a950-3b6b-411c-86f3-f87140efa609.png)  
## Day 22  
The 1st approach in order to have styling in components seperately and not in css files is with the introduction of Styled Components. After downloading it and installing it with npm `npm install --save styled-components` i can now use the tagged template styled.'item' ` `` `; so as to conclude in each seperate element its desired style. I will work on the Button.js file and by using the tagged template i can now copy paste the css code of the Button.css file inside the backticks and style the button component with the style that i intend. My file then looks like this 

