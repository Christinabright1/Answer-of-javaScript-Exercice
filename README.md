# Answer-of-javaScript-Exercice
Answers of algorithm JavaScript exercice

//Array with 3 elements

var names=['jonh','james','smith'];
var years= new Array(1990,2015,2018);
console.log(name[0]);
//mutate value in the Array
/*Change the value of some index in the Array*/
names[2]= 'Ben';
console.log(names);

//Add data to the array
/*Add a position that is not in the array*/
names[5]= 'Mary';
names[names.length]= 'Mary';
console.log(names);

//Different data Type
var jonh=['jonh','Smith',1990,'teacher',false];

//Method in JS
jonh.push('blue');
console.log(jonh);
//indexOf
console.log(jonh.indexOf('blue'));
var isDesigner= jonh.indexOf('Designer') === -1 ? 'jonh is NOT a designer': 'jonh is a designer';
console.log(isDesigner);
