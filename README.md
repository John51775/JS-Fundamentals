 javascript is amazing because its dynamic and friendly to use
to display three texts on the console using javascript you can use three ways, 1 use array 
let languages = ["C is fun", "Python is cool", "JavaScript is amazing"]
console.log(languages[0]);
console.log(languages[1]);
console.log(languages[2]);

2

using for loop

const languages = ["C is fun", "Python is cool", "JavaScript is amazing"]
for (let i=0; i<languages.length; i++){
console.log(languages[i])

3

const languages = ["C is fun", "Python is cool", "JavaScript is amazing"]
languages.forEach(text => console.log(text));
