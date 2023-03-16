Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

## Getting To Know Array Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (2-3 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your words what this method does.
6. Does it mutate the original value or not (check https://doesitmutate.xyz)

Example:

1. `concat`

   - Parameter: n (any) number of values (number, string, boolean, array, null, undefined, object and function etc)
   - Return: a single Array consisting of by all the values passed as parameters in the same order.
   - Example:
     ```js
     let numbers = [1, 2, 3];
     numbers.concat(4); //[1,2,3,4]
     let sentanceArray = 'A quick brown fox jumped over a lazy'.split(' ');
     sentanceArray.concat('dog').join(' '); //"A quick brown fox jumped over a lazy dog"
     let colors = ['red', 'green', 'blue'];
     colors.concat('black', 'red', 21, true); // ['red','green','blue','black', 'red', 21, true]
     ```
   - `concat` accepts n number of values and returns one array with all the values in same order. It does not change the original array.
   - No it does not mutate the original array

2. `join`
    - Parameter: 
3. `flat`
    - Parameter: It accepts a depth value which specifies how deep the nested values should be flattened.
    (number data type.)
    - Return: it returns a new array 
    with all the sub arrays concatinated into one array.
    - Example: 
    ```js
    const arr1 = [1,2[3,4,5[6,7]]];
    console.log(arr1.flat(2))//[1,2,3,4,5,6,7]
    const arr2 = [1, 2, [3, 4, [5, 6]]];
    console.log(arr2.flat())//[1, 2, 3, 4, Array(2)]
    const arr3 = [1, 2, [3, 4, [5, 6, [7, 8, [9, 10]]]]];
    console.log(arr4.flat(Infinity));// [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
    ```
    - This method concatinates the nested arrays into a new array on the basis of depth value specified.
    -No, it does not mutate the original value.
4. `push`
    - Parameter: It accepts the element that has to be added to the end of the array. (string,number,object)
    - Return: it will return the array with the element entered by the user at the end of the array.
    - Example:
    ```js
    let arr = ['Apple','Banana'];
    console.log(arr.push['watermelon'])// ['Apple','Banana','watermelon']
    let color = ['orange','red','green'];
    console.log(color.push('white'))// ['orange','red','green','white']
    ```
    - This method puts the entered element to the end of the array.
    - Yes, it mutates the orignal value.

5. `indexOf`
    - Parameter: it accepts all data types which are present in the array, if the element is not present in the array it will return an index of -1
    - Return: index of the element specified by the user.
    ```js
    let number = [1,2,2,3]
    console.log(number.indexOf(2)) // 1

    let gender = ['male','female','bisexual']
    console.log(gender.indexOf('male')) // 0
    ```
    - It gives the index of the element entered by the user, from the start of the array if the given element is not present in the array it returns the index as -1
    - No it does not mutate the orignal array.
  
6. `lastIndexOf`
    - Parameter: it accepts all data types which are present in the array, if the element is not present in the array it will return an index of -1
    - Return: index of the element specified by the user.
    ```js
    let number = [1,2,2,3]
    console.log(number.lastIndexOf(2)) // 2

    let gender = ['male','female','bisexual']
    console.log(gender.indexOf('male')) // 0
    ```
    - It gives the index of the element entered by the user, from the end of the array if the given element is not present in the array it returns the index as -1
    - No it does not mutate the orignal array.

7. `includes`
8. `reverse`
9. `every`
10. `shift`
    - Parameter: it accepts a blank element,(no data type)
    - Result: it returns a the orignal value without the first element, as 'shift' removes the first value of the index.
    - Example:
    ```js
    let number = [1,2,2,3]
    console.log(number.shift()) // [2,2,3]

    let gender = ['male','female','bisexual']
    console.log(gender.shift()) // ['female','bisexual']
    ```
    - Shift method removes the first index of the object and lowers the index value of all other elements.
    -Yes, it mutates the orignal value.

11. `splice`
12. `find`
13. `unshift`
    - Parameter: it accepts an element which is to be added the start of the object. (string,number, etc)
    - Return: it returns the orignal array with the element added to the start of the original value and pushing the index of all other elements.
    - Example:
    ```js
    let number = [1,2,2,3]
    console.log(number.unshift(0)) // [0,1,2,2,3]

    let gender = ['male','female','bisexual']
    console.log(gender.unshift('transgender')) // [''transgender','male',female','bisexual']
    ```
    - it adds one or more elements to the start of the array and increases the index value accordingly.
    - Yes it mutates the orignal array.

14. `findIndex`
15. `filter`
16. `flat`
17. `forEach`
18. `map`
19. `pop`
20. `reduce`
21. `slice`
22. `some`
