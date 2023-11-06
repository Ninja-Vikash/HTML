# CHAPTER 1

### INTRODUCTION OF HTML

![Banner](https://github.com/Ninja-Vikash/Assets/blob/main/HTML%20Assets/HTML%20introduction.png)
<b>HTML</b> : Hypertext Markup Language<br>

<p>HTML is the code used to structure a web page and its content. And the components used to design the structure of websites are called HTML tags. It is often assisted by technologies such as Cascading Style Sheets and Scripting languages such as Javascript.</p>
<hr>

<ol>
<li>How to create an HTML document.</li>
 syntax-
<pre>
&lt!DOCTYPE html&gt
&lthtml lang="en"&gt
  &lthead&gt
    &ltmeta charset="UTF-8" /&gt
    &ltmeta name="viewport" content="width=device-width, initial-scale=1.0" /&gt
    &lttitle&gtDocument&lt/title&gt
  &lt/head&gt
  &ltbody&gt
      ------Your code will be here!------
  &lt/body&gt
&lt/html&gt
</pre>
<p>The above code is called the <b>Boiler Plate</b>. <br>
:bulb: <b>Tip:</b>  We can write it with the help of emmet abbreviation <b>!</b> + <b>enter</b> | <b>html5</b> + <b>enter</b> <br>
Both methods are useful for deploying boilerplate.</p>
<br>
<li>All the elements within angular brackets <> called as <b>Tags</b></li>
<p>Most of the element are closed with two tags like &ltopening tag&gt context &lt/closing tag&gt <br>
Also, there are a few tags that are self-closed tag.</p>
<p>Example: &ltbr&gt , &lthr&gt , &ltimg&gt and so on..</p>
<li>Overview of Boilerplate-</li>
<pre>
&lt!DOCTYPE html&gt
</pre>
<p>&lt!DOCTYPE html&gt tells the browser this document is an HTML document.</p>

<pre>
&lthtml&gt
  -------Everything inside the html tag is the part of HTML--------
&lt/html&gt  
</pre>
<p>&ltHTML&gt is the parent container.</p>
<pre>
&lthead&gt
  -------Contains the metadata, title, link, and other useful tags which are not rendered on the browser's screen--------
&lt/head&gt

&ltbody&gt
-------Contains the main data and reflects on the browser's screen--------
&lt/body&gt

</pre>
<p>&lthead&gt and &ltbody&gt are children tags of HTML tag.</p>
<pre>
&ltmeta  -------useful data------  &gt
</pre>
<p>&ltmeta&gt is a self-closed tag that stores useful data like characters used in documents, content width, and initial scale for different size screens.<br>
&ltmeta&gt contains special information about the webpage. These are generally for browsers to use.</p>
<pre>
&lttitle&gt-----Name of the Webpage-----&lt/title&gt
</pre>
<p>&lttitle&gt is used to give the name to the Webpage When we search the Internet. It is shown on the browser's tab bar.</p>
<pre>
&ltbody&gt
  --------All the data is reflected on the browser's screen---------
&lt/body&gt
</pre>
<p>&ltbody&gt is also a container used to add data which is reflected on the browser's main screen. </p>
4. Comments are written as
<pre>
&lt!-- Your comment is here --&gt
</pre>
</ol>