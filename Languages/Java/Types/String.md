# String
## String literals
- `"string"`
- [Text blocks](https://openjdk.org/jeps/355) (Java 13)  
    ```java
        """
        first line\n"\"
        ← incidental white space →    
        last line"""
    ```
    ==
    `"first line\n\"\"\n← incidental white space →\nlast line"`

    [Programmer's Guide to Text Blocks](https://docs.oracle.com/en/java/javase/15/text-blocks/index.html)
- ~~[Raw string literals](https://openjdk.org/jeps/326)~~