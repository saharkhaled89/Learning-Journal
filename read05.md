#**CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background
of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, 
italic, Times typefac**

## learned how to write a CSS

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. 
A CSS rule contains two parts: a selector and a declaration.

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.
cSS propertIeS affect how eLeMentS are dISpLayed
h1, h2, h3 {           font-family: Arial;  
                           color: yellow;}
                          ProPerty Value

### **uSIng externaL cSS**
                  
1.The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style
the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the <head> 
element. It should use three attributes

2.href This specifies the path to the CSS file (which is often placed in a folder called css or styles).

3.type This attribute specifies the type of document being linked to. The value should be text/css.

4.rel This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when 
linking to a CSS file
<!DOCTYPE html>
<html>
<head> 
<title>Using External CSS</title> 
<link href="css/styles.css" type="text/css"    
rel="stylesheet" /> 
</head>
<body> 
<h1>Potatoes</h1> 
<p>
</p>
</body>
</html> 

####** uSIng InternaL css **

**<style>**
You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page. 
The <style> element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.

**When building a website there are several advantages to placing your CSS rules in a separate style sheet:**
1.All of your web pages can share the same style sheet
2.e the user has downloaded the CSS stylesheet, the rest of the site will load faster. If you want to make a change to how your site
appears, you only need to edit the one CSS file and all of your pages will be updated. 

##### **understanding Color**

Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use 
a color picker.

. Color not only brings your site to life, but also helpsconvey the mood and evokes reactions.
. There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
. Color pickers can help you find the color you want. 
. It is important to ensure that there is enough contrast between any text and the background color
(otherwise people will not be able to read your content).
. CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
. CSS3 also allows you to specify colors as HSL values, with an optional opacity value.
   It is known as HSLA.






