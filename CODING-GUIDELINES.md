# Coding Guidelines

# Names:

Use descriptive names for all identifiers.
<br>
**Branch naming convention:**

* Use descriptive branch name with the issue number.
    * Example: Create-Coding-Guideline-document-#3

**Use PascalCasing for:**
<br>
* Class names
* Enums
<br>

**Use camelCasing for:**
<br>
* Functions
* Methods
* Property names
* local variables

# Comments:
Comments should have a space at the beginning and be complete sentences.
```js
// This is a comment. 
``` 
<br>

**Use JSDoc style comments for:** 
<br>
* Functions
* Enums
* Classes

```js
/**
* This is a comment.
*/
function myFunction() {
}
```

# Style:

* K&R style for curly brace placement
* One line if-statements require curly braces
* Include semi-colons at the end of statements
* Use let when declaring variables