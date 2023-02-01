Watch this video to understand what to do in this exercise block [link](https://www.youtube.com/watch?v=zGpplZj4zY0&feature=youtu.be)

#### Getting To Know String Methods

Go to this [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String) and look for the name of method to learn about it.

**Write in your own way of understanding (don't copy paste)**

Only if you are done with step 1 you should go ahead.

1. Practice it by yourself in console (4-5 times to understand)
2. Data types of parameters
3. Return value type
4. Write three examples
5. In your own words and one sentence explain what this method does.

Example:

1. `charAt`

   - Parameter: (index) defaults to 0 - (number data type)
   - Return: character at specific index in the string (string data type)
   - Example:
     ```js
     let name = 'Arya Stark';
     name.charAt(2); //"y"
     let sentance = 'A quick brown fox jumped over a lazy dog';
     sentance(4); // "i"
     let houseName = 'Starks';
     houseName.charAt(0); // "S"
     ```
   - `charAt` accepts a index (number data type) and return the character on that index in the string.

2. `toUpperCase`
  - Parameter: Accepts blank parameter
  - Return: (String data type) with the whole value converted to uppercase.
  -Example: 
  ```js
    let name = "I am learning javascript"
    name.toUpperCase();// 'I AM LEARNING JAVASCRPIT'

    let title = "are you ready?";
    title.toUpperCase();// 'ARE YOU READY'

    let brand = "Nike";
    let tagline = "just do it";
    brand.toUpperCase();// 'NIKE'
    tagline.toUpperCase();// 'JUST DO IT'
  ```

  - The toUpperCase() method returns the value of the string converted to uppercase.

3. `toLowerCase`
  - Parameter: Accepts blank paramter
  - Return: (String data type) with the whole value converted to lowercase.
  - Example:
  ```js
   let name = "I am learning javascript"
    name.toLowerCase();// 'i am learning javascript'

    let title = "Are you Ready?";
    title.toLowerCase();// 'are you ready'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.toLowerCase();// 'nike'
    tagline.toLowerCase();// 'just do it'
    ```
  - toLowerCase() method returns the value of the string converted to lower case.

4. `trim`
  - Paramter: Accepts blank paramater
  - Return: Whitespace is stripped off from the beginning & end of th string value.
  - Example: 
  ```js
    let name = "  I am learning javascript  "
    name.trim();// 'i am learning javascript'

    let title = "   Are you Ready?  ";
    title.trim();// 'are you ready'

    let brand = "  Nike";
    let tagline = "  Just Do It  ";
    brand.trim();// 'Nike'
    tagline.trim();// 'Just do it'
    ``` 
    trim() method removes whitespace from both ends of a string and returns a new string, without modifying the original string.
5. `trimEnd`
  - Parameter: Accepts blank parameter
  - Return:  (string data type) removes whitespace from the end of a string.
  - Example: 
  ```js
    let name = "  I am learning javascript  "
    name.trimEnd();// '  i am learning javascript'

    let title = "   Are you Ready?  ";
    title.trimEnd();// '  are you ready'

    let brand = "  Nike";
    let tagline = "  Just Do It  ";
    brand.trimEnd();// '  Nike'
    tagline.trimEnd();// '  Just do it'
    ``` 

6. `trimStart`
  - Parameter: Accepts blank parameter
  - Return:  (string data type) removes whitespace from the start of a string.
  - Example: 
  ```js
    let name = "  I am learning javascript  "
    name.trimStart();// 'i am learning javascript  '

    let title = "   Are you Ready?  ";
    title.trimStart();// 'are you ready  '

    let brand = "  Nike";
    let tagline = "  Just Do It  ";
    brand.trimStart();// 'Nike'
    tagline.trimStart();// 'Just do it  '
    ``` 
7. `concat`
  - Parameter: One or more strings to concatenate to string
  - Return: A new string combining the two text of the string provided.
  - Example:
  ```js
    let brand = "Nike";
    let tagline = "Just Do It";
    brand.concat(' ', tagline)// 'Nike Just Do It'
    tagline.concat(brand)// 'Just Do ItNike'
    brand.concat(', ', tagline, '!')//'Nike, Just Do It!'
  concat() method concatenates the string arguments to the calling string and returns a new string.


8. `endsWith`
  - Parameter: The characters to be searched for at the end of string value.
  - Return: true if the given characters are found at the end of the string, including when searchString is an empty string; otherwise, false. (boolean data type)
  - Example:
   ```js
   let name = "I am learning javascript"
    name.endsWith('pt');// true

    let title = "Are you Ready?";
    title.endsWith('Ready?');// true

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.endsWith('nike');// false
    tagline.endsWith('it');// false
    ```
  
9. `includes`
  - Parameter: A string to be searched for within str.
  - Return: true if the search string is found anywhere within the given string, including when searchString is an empty string; otherwise, false.
  - Example: 
  ```js
    let name = "I am learning javascript"
    name.includes('pt');// true

    let title = "Are you Ready?";
    title.includes('Ready?');// true

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.includes('nike');// false
    tagline.includes('it');// false
    ```
  includes() method performs a case-sensitive search to determine whether one string may be found within another string, returning true or false as appropriate.

10. `indexOf`
  - Paramter: 
11. `lastIndexOf`
12. `padEnd`
13. `padStart`
14. `repeat`
15. `replace`
16. `slice`
17. `split`
18. `substring`
