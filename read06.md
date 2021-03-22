#**Chapter-10 (Introducing CSS)**

Css: we use it to create rules that specify how the content of
an element should appear, like background, paragraph, headings.

##**Understanding CSS:**

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

##**Using External CSS**

 -*<link>:* The <link> element can be used in an HTML document to tell the browser where to find the CSS
          file used to style the page.
 
  -It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> element.
   It should use three attributes:
    
    -href: This specifies the path to the CSS file (which is often placed in a folder called css or styles).
    -type: This attribute specifies the type of document being linked to. The value should be text/css.
    -rel: This specifies the relationship between the HTML page and the file it is linked to. The value
          should be stylesheet when linking to a CSS file.

##**Usi ng Internal CSS**

 -*<style>:* You can also include CSS rules within an HTML page by placing them inside a <style> element,
           which usually sits inside the <head> element of the page.

-When building a site with more than one page, you should use an external CSS style sheet.

-If there are two or more rules that apply to the same element, it is important to understand
 which will take precedence.

-If you are just creating a single page, you might decide to put the rules in the same file to
 keep everything in one place.




#**Chapter-11 (Color)**

-Color can really bring your pages to life.

##**Foreground Color:**

 -The color property allowing us to specify the color of text inside an element. You can specify any
  color in CSS in one of three ways:
   
  -*rgb values:* These express colors in terms of how much red, green and blue are used to make it up. For
               example: rgb(100,100,90).
  -*hex codes:* These are six-digit codes that represent the amount of red, green and blue in a color,
              preceded by a pound or hash # sign. For example: #ee3e80 .
  -*color names:* There are 147 predefined color names that are recognized
                by browsers. For example: DarkCyan

##**Contrast:**When picking foreground and background colors, it is important to ensure that there is
         enough contrast for the text to be legible.


##**CSS 3:** Opacity opacity, rgba

 -CSS3 introduces the opacity property which allows you to specify the opacity of an element
  and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5
  is 50% opacity and 0.15 is 15% opacity).

##**CSS 3:** HSL Colors

 -CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation,
  and lightness values.
