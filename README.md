# Github readme.md Syntax highlighting syntax code block 
Github readme.md Syntax highlighting syntax code block 

Fenced code blocks
You can create fenced code blocks by placing triple backticks ``` ``` ```
before and after the code block.
We recommend placing a blank line before and after code blocks to make the raw formatting easier to read.

"```javaScript  End Line Add ``` "

"```javascript
function Hello() {
  console.log("Hi Iam Hello Function");
}
```"

```
function Hello() {
  console.log("Hi Iam Hello Function");
}
```
# Syntax highlighting You can add an optional language identifier to enable syntax highlighting in your fenced code block.

For example, to syntax highlight javascript code: use First line ``````javascript .  Type Midle Your Code and last line type `````` 
![image](https://user-images.githubusercontent.com/45946252/168409372-b44bb15d-b9b0-43f7-8aa2-02fc3054e082.png)

javascript :

```javascript
<script>
    alert( 'Hello, world!' );
  </script>
```
C :

```C
#include <stdio.h>

int main() {
printf("Hello World");
return 0;
}
```
C#
```C#
namespace HelloWorld
{
	class Hello {		
		static void Main(string[] args)
		{
			System.Console.WriteLine("Hello World");
		}
	}
}
```
python

```python
print("Hello World")
```

Java

```java

import java.io.*;

class GFG {
	public static void main (String[] args) {
	System.out.println("Hello World");
	}
}

```

#add File

How to use
In markdown, write code block as follows:

```python:[test.py](https://github.com/coolsasindu/Github-readme.md-Syntax-highlighting-syntax-code-block-/blob/main/test.py)

```

And, you can refer specific lines as
```python:[tests/src/sample.py](https://github.com/coolsasindu/Github-readme.md-Syntax-highlighting-syntax-code-block-/blob/main/test.py) [4-5]
 
```
Then, this action referes to [test.py](https://github.com/coolsasindu/Github-readme.md-Syntax-highlighting-syntax-code-block-/blob/main/test.py) and modifies markdown as (if something code is written, they are overridden):

from math import sqrt


def sample(x):
    return sqrt(x)
And, specific lines is refered as

def sample(x):
    return sqrt(x)
 
