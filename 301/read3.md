# Reading :

1- map() function returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable

2- using map().






# The Spread Operator:




1- JavaScript, spread syntax refers to the use of an ellipsis of three dots (âĶ) to expand an iterable object into the list of arguments.




2- Copying an array , Concatenating or combining arrays, Using Math functions, Using an array as arguments





3- * const myArray = [`ðĪŠ`,`ðŧ`,`ð`]


* const yourArray = [`ð`,`ðĪ`,`ðĪĐ`]


* const ourArray = [...myArray,...yourArray]


 * console.log(...ourArray) // ðĪŠ ðŧ ð ð ðĪ ðĪĐ




 
 
 4- * const fewFruit = ['ð','ð','ð']

 * const fewMoreFruit = ['ð', 'ð', ...fewFruit]

* console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]







5- * const objectOne = {hello: "ðĪŠ"}
* const objectTwo = {world: "ðŧ"}

* const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}

* console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }

* const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}

* objectFour.laugh() // ððððð












## Things I want to know more about

i want to learn about map