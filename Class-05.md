# Read05

## Images

![images tag](https://www.mediacollege.com/internet/html/images/image-tag1.gif)

**Adding Images**

*(img src="" alt=" " title=" " /)*

**Height & Width of Images**

*You will also often see an (img)element use two other attributes that specify its size: (Height & Width)*

**Where to Place Images in Your Code**

1. before a paragraph
2. inside the start of a paragraph
3. in the middle of a paragraph

**Three Rules for Creating Images**

- Save images in the right format
- Save images at the right size
- Use the correct resolution

**Tools to Edit & Save Images**

*There are several tools you can use to edit and save images to ensure that they are the right size, format, and resolution*

**Image Resolution**

*Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file*

**HTML5: Figure and Figure Caption**

*((figure)(img src="" alt="")(br /)(figcaption).(/figcaption) (/figure))*

![](https://www.codegrepper.com/codeimages/how-to-use-figure-and-caption-in-html.png)

## Color With CSS

**Foreground Color**

***The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:***

1. **rgb values** :*These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)*
2. **hex codes** : *These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80*
3. **color names** : *There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan*

**Background Color**

***CSS treats each HTML element 
as if it appears in a box, and the 
background-color property 
sets the color of the background 
for that box.***

**The Color picker** 

![Color picker](https://i1.wp.com/www.cssscript.com/wp-content/uploads/2016/10/iro.js.png?fit=471%2C352&ssl=1.png)

**Contract** 

***When picking foreground and background 
colors, it is important to ensure that there is 
enough contrast for the text to be legible.*** : *(High,Medium,low) Contract*

**CSS3: Opacity (opacity, rgba)**

***CSS3 introduces the opacity
property which allows you to 
specify the opacity of an element 
and any of its child elements. 
The value is a number between 
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15% 
opacity).***

**CSS3: HSL Colors**

***CSS3 introduces an entirely new and intuitive 
way to specify colors using hue, saturation, 
and lightness values.***
- **Hue** : *Hue is the colloquial idea of 
color. In HSL colors, hue is often 
represented as a color circle 
where the angle represents the 
color, although it may also be 
shown as a slider with values 
from 0 to 360.*
- **saturation** : *Saturation is the amount of 
gray in a color. Saturation is 
represented as a percentage. 
100% is full saturation and 0% 
is a shade of gray*
- **lightness** : *Lightness is the amount of 
white (lightness) or black 
(darkness) in a color. Lightness 
is represented as a percentage. 
0% lightness is black, 100% 
lightness is white, and 50% 
lightness is normal. Lightness 
is sometimes referred to as 
luminosity.*

**CSS3:(HSL & HSLA)**

***The hsl color property has 
been introduced in CSS3 as an 
alternative way to specify colors. 
The value of the property starts 
with the letters hsl, followed 
by individual values inside 
parentheses for:(HUE,Saturation,Lightness,Alpha)***

## TEXT 
**Specifying Typefaces (font-family)**

![](https://slideplayer.com/slide/14463197/90/images/12/SPECIFYING+TYPEFACES+font-family.jpg)

*The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.The value of this property is the name of the typeface you want to use. The people who are visiting your site need the typeface you have specified installed on their computer in order for it to be displayed.*

**Size Of Type (font-size)**

![](https://w3-lab.com/wp-content/uploads/2019/11/2908271385_9fe4cde592_o-1.jpg)

*The font-size property enables you to specify a size for the font. There are several ways to specify the size of a font. The most common are (pixels,percentages,ems)*

**Type Scales**

*You may have noticed that programs such as Word, Photoshop and InDesign offer the same sizes of text.*

**Bold (font-Weight)**

![](https://docs.microsoft.com/en-us/uwp/api/windows.ui.text/images/font-weights.png?view=winrt-19041.png)

*The font-weight property allows you to create bold text. There are two values that this property commonly takes: (normal,bold)*

**Italic (font-style)**

*If you want to create italic text, you can use the font-styleproperty. There are three values this property can take: (normal,italic,oblique)*

**Underline & Strike (Text-decoration)**

![](https://www.codegrepper.com/codeimages/text-decoration-line-through-on-element.png)

*The text-decoration property allows you to specify the following values: (none,underline,overline,line-through,blink)*

**Leading(line-height)**

*Leading (pronounced ledding) is a term typographers use for the vertical space between lines of text. In a typeface, the part of a letter that drops beneath the baseline is called a descender, while the highest point of a letter is called the ascender. Leading is measured from the bottom of the descender on one line to the top of the ascender on the next.*

**Alignment(text-align)**

*The text-align property allows you to control the alignment of text. The property can take one of four values: (left,right,center,justify)*

**Vertical Alignment(vertical-align)**

*The vertical-align property is a common source of confusion. It is not intended to allow you to vertically align text in the middle of block level elements such as (p) and (div), although it does have this effect when used with table cells (the (td) and (th) elements).*

**CSS3: Drop Shadow (text-shadow)**

*The text-shadow property has become commonly used despite lacking support in all browsers. It is used to create a drop shadow, which is a dark version of the word just behind it and slightly offset. It can also be used to create an embossed effect by adding a shadow that is slightly lighter than the text.*

**First Letter or Line (:first-letter, :first-line)**

![](https://i.ytimg.com/vi/6uB-_pT8Rao/maxresdefault.jpg)

*You can specify different values for the first letter or first line of text inside an element using:first-letter and :first-line. Technically these are not properties. They are known as pseudo-elements.You specify the pseudo-element at the end of the selector, and then specify the declarations as you would normally for any other element.*

**Styling Links (:link , :visited)**

*Browsers tend to show links in blue with an underline by default, and they will change the color of links that have been visited to help users know which pages they have been to.In CSS, there are two pseudoclasses that allow you to set different styles for links that have and have not yet been visited.*

**Responding to Users (:hover, :active, :focus)**

![](https://miro.medium.com/max/5004/1*bQvhdLvbMqMtijZ5t11f1w.jpeg)

*There are three pseudo-classes that allow you to change the appearance of elements when a user is interacting with them.*

![](https://i.stack.imgur.com/tSAXe.png)