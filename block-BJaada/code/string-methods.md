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
    ```
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
  - Paramter: Substring to search for. (optional) the index position to start searching from
  - Return:the index of the first occurence of the subtring(number data type)
  - Example:
  ```js
    let name = "I am learning javascript"
    name.indexOf('pt');// 22

    let title = "Are you Ready?";
    title.indexOf('Ready?');// 8

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.indexOf('nike');// 0
    tagline.indexOf('it');// -1
    ```
  indexOf() method, given one argument: a substring to search for, searches the entire calling string, and returns the index of the first occurrence of the specified substring.
  
11. `lastIndexOf`
  - Parameter: Substring to search for. (optional) the index position to start searching from
  - Return: The index of the last occurrence of searchString found (number data Type)
  - Example: 
   ```js
    let name = "I am learning javascript"
    name.lastIndexOf('pt');// 22

    let title = "Are you Ready?";
    title.lastIndexOf('e');// 9

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.lastIndexOf('nike');// 0
    tagline.lastIndexOf('it');// -1
    ```
12. `padEnd`
  - Parameter: The length of the resulting string once the current str has been padded. A string with which it has to be padded(optional)
  - Return: A String of the specified targetLength with the padString applied at the end of the current str. (string data type)
  - Example:
  ```js
    let name = "I am learning javascript"
    name.padEnd('30', 't');// "I am learning javascripttttttt"

    let title = "Are you Ready?";
    title.padEnd(20, '?');// 'Are you Ready???????'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.padEnd(6, 'Nike');// 'NikeNi'
    tagline.padEnd(15, 'it');// 'Just Do Itititi'
    ```
  padEnd() method pads the current string with a given string (repeated, if needed) so that the resulting string reaches a given length. The padding is applied from the end of the current string.


13. `padStart`
  - Parameter: The length of the resulting string once the current str has been padded. A string with which it has to be padded(optional)
  - Return: A String of the specified targetLength with the padString applied at the start of the current str. (string data type)
  - Example:
  ```js
    let name = "I am learning javascript"
    name.padStart('30', 'helo ');// 'helo hi am learning javascrpit'

    let title = "Are you Ready?";
    title.padStart(20, 'people ');// 'PeopleAre you Ready?'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.padStart(6, 'Nike');// 'NikeNi'
    tagline.padStart(15, 'it');// 'Just Do Itititi'
    ```
  - padStart() method pads the current string with another string (multiple times, if needed) until the resulting string reaches the              given length. The padding is applied from the start of the current string

14. `repeat`
  - Parameter- An integer between 0 and +Infinity, indicating the number of times to repeat the string.
  - Return- A new string containing the specified number of copies of the given string. (string data type)
  - Example- 
  ```js
    let name = "I am learning javascript"
    name.repeat(2);// 'i am learning javascrpiti am learning javascrpit'

    let title = "Are you Ready?";
    title.repeat(3);// 'Are you Ready?Are you Ready?Are you Ready?'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.repeat(6);// 'NikeNikeNike'
    tagline.repeat(15);// 'Just Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do ItJust Do It'
    ```
     repeat() method constructs and returns a new string which contains the specified number of copies of the string on which it was called, concatenated together.

15. `replace`
  - Parameter: Can be a string or an object with a Symbol.replace method 
  - Return: A new string, with one, some, or all matches of the pattern replaced by the specified replacement. (string data type.)
  - Example: 
  ```js
    let name = "I am learning javascript"
    name.replace('javascript', 'python' );// 'i am learning python'

    let title = "Are you Ready?";
    title.replace('Are you Ready?', 'Ready, Steady, Go!'  );// 'Ready, Steady, Go!'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.replace('Nike', 'Volkswagon');// 'Volkswagon'
    tagline.replace('Just Do It', 'Das Auto');// 'Das Auto'
    ```
    The replace() method returns a new string with one, some, or all matches of a pattern replaced by a replacement

16. `slice`
  - Parameter: index start & Index End(optional) (Number data type)
  - Return: A new string between the start and end index values.
  - Example: 
  ```js
    let name = "I am learning javascript"
    name.slice(2);// 'am learning python'

    let title = "Are you Ready?";
    title.slice(7);// 'Ready?'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.slice(1,2);// 'i'
    tagline.slice(5);// 'Do It'
    ```
    The slice() method extracts a section of a string and returns it as a new string, without modifying the original string.

17. `split`
  - Parameter: Seperator (string data type) is needed which determines forom where the orignal string will split.
  - Return: An Array of strings, split at each point where the separator occurs in the given string.
  - Example: 
  ```js
  let name = "I am learning javascript"
    name.split(' ');// (4) ['i', 'am', 'learning', 'javascrpit']

    let title = "Are you Ready?";
    title.split('y');// (3) ['Are ', 'ou Read', '?']

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.split('i');// (2) ['N', 'ke']
    tagline.split('Do');// (2) ['Just ', ' It']
    ```
  The split() method takes a pattern and divides a String into an ordered list of substrings by searching for the pattern, puts these substrings into an array, and returns the array.

18. `substring`
- Parameter: Index start & Index End.
- Return: A new string containing the specified part of the given string.
- Example :
```js
    let name = "I am learning javascript"
    name.substring(2);// "am learning javascript"

    let title = "Are you Ready?";
    title.substring(5, 1);// 're y'

    let brand = "Nike";
    let tagline = "Just Do It";
    brand.substring(6);// ' '
    tagline.substring(5,10);// 'Do It'
    ```
substring() method returns the part of the string from the start index up to and excluding the end index, or to the end of the string if no end index is supplied

