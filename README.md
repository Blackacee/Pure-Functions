# Pure-Functions
 
let obj = { a: 0 }
const pure = (input) => {
 // Does not modify obj
 let output = input.a + 1;
 return output;
}
let b = pure(obj)
console.log(obj) // Logs { "a": 0 }
console.log(b) // Logs 1
