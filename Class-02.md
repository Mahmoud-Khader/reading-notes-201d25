# Class-02 read

***TEXTs***

- *Headings : from (h1-h6)*
- *Paragraphs <p> : To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag*
- *Bold & Italic <b>$<i>*
- *Superscript & Subscript <sup>&<sub>*
- *White space : When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing*
- *Line breaks & Horizontal rules <br />&<hr />*
- *Strong & Emphasis <strong>&<em>*
- *Quotations <blockquote>&<q><q />*
- *Citations & Definitions <cite>&<dfn>*
- *Author Details <address><address />*
- *Changes to Content <ins>,<del> &<s>*

![text image](https://info201.github.io/img/markdown/markdown-blocks.png)

***CSS***

**CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.**

**CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.**

**Using External CSS**
*<link href="css/styles.css" type="text/css"
 rel="stylesheet" />*

 ![External CSS](https://www.homeandlearn.co.uk/WD/images/chapter4/external_styles_about_code.gif)

 **Using Internal CSS**
 *<style><style/>ou can also include CSS rules within an HTML page by placing them inside a <style> element,which usually sits inside the<head> element of the page*

 ![style CSS](https://fitbloggin.com/wp-content/uploads/2014/06/Fitbloggin-HTML-and-CSS-for-the-Non-Technical-Blogger-9.jpg)

 ***JavaScript basics***

 *JavaScript is a programming language that adds interactivity to your website. This happens in games, in the behavior of responses when buttons are pressed or with data entry on forms; with dynamic styling; with animation, etc. This article helps you get started with JavaScript and furthers your understanding of what is possible.*

 **STATEMENTS**
 *A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.*

 **COMMENTS**

 *You should write comments to explain what your code does.They help make your code easier to read and understand.This can help you and others who read your code.*

 **Variabels**

 *A script will have to temporarily store the bits of information it needs to do its job. It can store this  data in variables*

 **Data Types**

 *JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.*

 **Rules of naming variables**

 1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
 2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
 3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript. 
 4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 
 5. Use a name that describes the kind of information that the variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age. 
 6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash). 

 **Arrays**

 *An array is a special type of variable. It doesn't just store one value; it stores a list of values.*

 **Values in Arrays**

 *Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).*

**EXPRESSIONS**

*An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.*

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE 

**OPERATORS**

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Operators-1200x720.jpg)

![](https://i.stack.imgur.com/47OJp.jpg)

***Decision & Loops***

*Looking at a flowchart (for all but the most basic scripts),the code can take more than one path, which means the browser runs different code in different situations. In this chapter, you will learn how to create and control the flow of data in your scripts to handle different situations.* (EVALUATIONS,DECISIONS,LOOPS)

![](https://lessons2all.com/c%20images/output3%20(14).jpeg)

**If Statments**

*The if statement evaluates (or checks)a condition, if the condition evaluates to true, any statement in the subsequent code block are executed*

![](https://media.geeksforgeeks.org/wp-content/uploads/20191118171408/If-statement-GeeksforGeeks1.jpg)

**IF...Else Statements**

*The if...else statement checks a condition if it resolve to true the first code block is executed,if the condition resolves to false the second code block is run instead*

![](https://media.geeksforgeeks.org/wp-content/uploads/20191118180512/If-else-statement-GeeksforGeeks1.jpg)

**Switch Statements**

*A Switch statement starts with a variable called the Switch value , each case indicate a possible value for this variable and the code that should run if the variable matches that value.*

![](https://miro.medium.com/max/2184/1*SiM_5c6wtpq-p7O-DvkQ4A.png)