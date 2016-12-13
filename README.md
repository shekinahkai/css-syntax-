# css-syntax-
CSS Syntax 
A CSS rule set consists of a selector and a declaration block: 
 
CSS selector 
 
The selector points to the HTML element you want to style. 
 
The declaration block contains one or more declarations separated by semicolons. 
 
Each declaration includes a property name and a value, separated by a colon. 
 
CSS Example 
A CSS declaration always ends with a semicolon, and declaration groups are surrounded by curly braces: 
 
p {color:red;text-align:center;} 
To make the CSS code more readable, you can put one declaration on each line, like this: 
 
Example 
 
p { 
    color: red; 
    text-align: center; 
} 
 
 
[demo] 
 
<!DOCTYPE html> 
<html> 
    <head> 
    <style> 
        p { 
            color: red; 
            text-align: center; 
        }  
    </style> 
    </head> 
    <body> 
 
        <p>Hello World!</p> 
        <p>This paragraph is styled with CSS.</p> 
 
    </body> 
</html> 
 
[/demo] 
 
 
 
CSS Comments 
Comments are used to explain your code, and may help you when you edit the source code at a later date. Comments are ignored by browsers. 
 
A CSS comment starts with /* and ends with */. Comments can also span multiple lines: 
 
Example 
 
p { 
    color: red; 
    /* This is a single-line comment */ 
    text-align: center; 
} 
 
/* This is 
a multi-line 
comment */ 
 
 
[demo] 
 
<!DOCTYPE html> 
<html> 
    <head> 
    <style> 
        p { 
            color: red; 
            /* This is a single-line comment */ 
            text-align: center; 
        }  
 
        /* This is 
        a multi-line 
        comment */ 
    </style> 
    </head> 
    <body> 
 
        <p>Hello World!</p> 
        <p>This paragraph is styled with CSS.</p> 
        <p>CSS comments are not shown in the output.</p> 
 
    </body> 
</html> 
 
[/demo] 
 
