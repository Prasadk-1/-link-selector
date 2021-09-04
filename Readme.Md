CSS :link selector
The :link selector is a pseudo-class that targets all unvisited anchor (<a>) elements on a page.

Need:
The :link selector is a pseudo-class that allows you to target a link that has not been visited
To know whether the link is visited or not We Use :link Selector.

Syntax:
The syntax for the :active CSS selector is:
a:link { style_properties }
Parameters or Arguments

style_properties:
The CSS styles that can be applied to a link that has not been visited yet.
Browser Compatibility
The CSS :link selector has basic support with the following browsers:
Chrome
Firefox (Gecko)
Internet Explorer (IE)
Opera
Safari (WebKit)

Example
We will discuss the :link selector below, exploring examples of how to use this selector in CSS to apply styling to an <a> tag that has not been visited.
With <a> tag
Let's look at a CSS :link example where we apply the :link selector to the <a> tag.
The CSS would look like this:
a:link { background: grey; color: white; }
The HTML would look like this:
<div>
  <p>Example written by: <a href="https://www.techonthenet.com/index.php">TechOnTheNet.com</a></p>
</div>
When the <a> tag has not been visited, the :link selector would style the <a> tag as follows:

In this :link example, the link "TechOnTheNet.com" will have a grey background with white text only when the link has not been visited.
Then once the <a> tag has been visited, the :link selector would no longer style the <a> tag and the link would appear as follows:

