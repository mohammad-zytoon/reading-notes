
# **Duckett HTML book:**

## *chapter-2-Text*

### Heading

-HTML has six "levels" of headings:<h1>, <h2>, <h3>, <h4>, <h5>, <h6>.

-<h1> is used for main headings <h2> is used for subheadings If there are further sections
under the subheadings then the <h3> element is used, and so on...

### Paragraph

-<p>: To create a paragraph, surround the words that make up the
      paragraph with an opening <p> tag and closing </p> tag.

### Bold & It alic

-<b>: By enclosing words in the tags <b> and </b> we can make characters appear bold.
-<i>: By enclosing words in the tags <i> and </i> we can make characters appear italic.

### Superscript & Subscript

-<sup>: The <sup> element is used to contain characters that should be superscript such
        as the suffixes of dates or mathematical concepts like raising a number to a power.

-<sub>: The <sub> element is used to contain characters that should be subscript. It is commonly
        used with foot notes or chemical formulas such as H20.

### White Space
-In order to make code easier to read, web page authors often
 add extra spaces or start some elements on new lines.

### Line Breaks & Horizontal Rules

-<br />: As you have already seen, the browser will automatically show each new paragraph or heading
         on a new line. But if you wanted to add a line break inside the middle of a paragraph you can 
         use the line break tag <br />.

-<hr />: To create a break between themes — such as a change of topic in a book or a new scene
         in a play — you can add a horizontal rule between sections using the <hr /> tag.

### Visual Editors &Their Code views

-Content management systems and HTML editors such as Dreamweaver usually have two views of the page you 
 are creating: a visual editor and a code view.

### Semantic Markup

-<strong>: The use of the <strong> element indicates that its content has strong importance.
           For example, the words contained in this element might be said with strong emphasis.

-<em>: The <em> element indicates emphasis that subtly changes the meaning of a sentence.

Quotations: <blockquote>, <q>.

### Abb reviations & Acronyms

-<abbr>: If you use an abbreviation or an acronym, then the <abbr> element can be used. A title
         attribute on the opening tag is used to specify the full term.

### Citations & Definitions

-<cite>: When you are referencing a piece of work such as a book,
         film or research paper, the <cite> element can be used to indicate where the citation is from.
-<dfn>: The first time you explain some new terminology (perhaps an
        academic concept or some jargon) in a document, it is known as the defining instance of it.

### Auth or Details

-<address>: The <address> element has quite a specific use: to contain contact details for the author of the page.

Changes to Content: <ins>, <del>, <s>.


## **Chapter-10 (Introducing CSS)**

**Css:** we use it to create rules that specify how the content of
an element should appear, like background, paragraph, headings.

Understanding CSS:

-The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.

-Block level elements: they start on a new line. Examples include the <h1>- <h6>, <p> and <div> elements.

-Inline elements flow within the text and do not start on a new line. Examples include <b>, <i>,
<img>, <em> and <span>.

-CSS allowing us to create rules that control the way that each individual box (and the contents
 of that box) is presented.

-CSS works by associating rules with HTML elements. These rules govern how the content of specified 
 elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

 -Selectors indicate which element the rule applies to.
 -Declarations indicate how the elements referred to in the selector should be styled.

-CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon.
 You can specify several properties in one declaration, each separated by a semi-colon.

Using External CSS

 -<link>: The <link> element can be used in an HTML document to tell the browser where to find the CSS
          file used to style the page.
 
  -It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element.
   It should use three attributes:
    
    -href: This specifies the path to the CSS file (which is often placed in a folder called css or styles).
    -type: This attribute specifies the type of document being linked to. The value should be text/css.
    -rel: This specifies the relationship between the HTML page and the file it is linked to. The value
          should be stylesheet when linking to a CSS file.

### **Usi ng Internal CSS**

 -<style>: You can also include CSS rules within an HTML page by placing them inside a <style> element,
           which usually sits inside the <head> element of the page.

-When building a site with more than one page, you should use an external CSS style sheet.

-If there are two or more rules that apply to the same element, it is important to understand
 which will take precedence.
 -If you are just creating a single page, you might decide to put the rules in the same file to
 keep everything in one place.




## **Chapter-10 (Color)**

-Color can really bring your pages to life.

### Foreground Color:

 -The color property allowing us to specify the color of text inside an element. You can specify any
  color in CSS in one of three ways:
   
  -rgb values: These express colors in terms of how much red, green and blue are used to make it up. For
               example: rgb(100,100,90).
  -hex codes: These are six-digit codes that represent the amount of red, green and blue in a color,
              preceded by a pound or hash # sign. For example: #ee3e80 .
  -color names: There are 147 predefined color names that are recognized
                by browsers. For example: DarkCyan

Contrast:When picking foreground and background colors, it is important to ensure that there is
         enough contrast for the text to be legible.


CSS 3: Opacity opacity, rgba

 -CSS3 introduces the opacity property which allows you to specify the opacity of an element
  and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5
  is 50% opacity and 0.15 is 15% opacity).

CSS 3: HSL Colors

 -CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation,
  and lightness values.


# **Duckett JS book:**

## **Chapter-2- Basic JavaScript Instructions**

-A script is made up of a series of statements. Each
 statement is like a step in a recipe.

-Scripts contain very precise instructions. For example,
 you might specify that a value must be remembered before creating a calculation using that value.

-Variables are used to temporarily store pieces of
 information used in the script.

-Arrays are special types of variables that store more than one piece of related information.

-JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).

-Expressions evaluate into a single value.

-Expressions rely on operators to calculate a value.



## **Chapter-4- Decisions and Loops up to the section on switch statements**

-There are situations when we want to run the code at different conditions, such as, if one
 condition applies run a particular code, if another condition applies another code is run.

-There are two components to a decision:
 1-An expression is evaluated, which returns a value.
 2-Acondtional statment says what to do in a given situation.

-**If statement:** if is used to check for a condition whether its true or not. Condition could be any expression
               that returns true or false. When condition satisfies then statements following if statement are executed.

-if(condition)
{
    statement1
    statement2
    ...
}

-if(condition)
    statement

-if(condition)
{
    statements
}
else
{
    statements
}

-if(condition)
{
    statements
}
else if(condition)
{
    statements
}
else
{
    statements
}

-**A note on comparison operators**

- === and !== — test if one value is identical to, or not identical to, another.
- < and > — test if one value is less than or greater than another.
- <= and >= — test if one value is less than or equal to, or greater than or equal to, another.

-Logical operators: AND, OR and NOT

- && — AND; allows you to chain together two or more expressions so that all of them have to individually evaluate to true for the whole expression to return true.
- || — OR; allows you to chain together two or more expressions so that one or more of them have to individually evaluate to true for the whole expression to return true.
