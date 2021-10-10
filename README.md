# top-choices

let wondering = prompt("What do you want to learn about my top choice?");
let otherProp = prompt("add some more property")

function MyChoice(wonder, property) {
  this.wonder = wonder;
  this.property = property;

  this.changeIntoObject = function () {
  
  return console.log(`My first choice is ${this.wonder} and from ${this.property}`);

  };
}

let firstObject = new MyChoice(wondering, otherProp)

firstObject.changeIntoObject()