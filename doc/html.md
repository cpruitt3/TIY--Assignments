### 1. `<div>` -- Document division element

* *type:* block-level
* *content:* flow content
* *support:* all browsers
* *example:*
```
<div>content</div> 
<div>separate content</div>
```
<div><p>Hello up here</p></div><br><div><p>Hello down here</p></div>

###  2. `<header>` --  Represents a group of introductory or navigational aids


* *type:* block-level
* *content:* flow content
* *support:* all browsers
* *example:* 
```
<header>Welcome to class</header>
```
<header>Welcome to class</header>

### 3. `<ol>` -- Ordered list

* *type:* block-level
* *content:* flow content, palpable content
* *support:* all browsers (basic support)
* *example:* 
```
<ol>
  <li>I'm number one!</li>
  <li>I'm number two!</li>
</ol>
```
<ol>
  <li>I'm number one!</li>
  <li>I'm number two!</li>
</ol>

### 4. `<address>` -- Used for contact information

* *type:* block-level
* *content:* flow content, palpable content
* *support:* all browsers
* *example:*
```
<address>Call me at 407-123-4567</address>
```
<address>Call me at 407-123-4567</address>

### 5. `<hr>` -- Horizontal rule (creates horizontal break in page)

* *type:* block-level
* *content:* flow content
* *support:* all browsers
* *example:*
```
<p>Hello friends this is</p>

<hr>

<p>a horizontal break</p>
```
<p>Hello friends this is</p>

<hr>

<p>a horizontal break</p>

### 6. `<footer>` -- creates a footer for the nearest section

* *type:* block-level
* *content:* flow content, palpable content
* *support:* all browsers
* *example:*
```
<footer>Copyright AdamKarb2015</footer>
```
<footer>Copyright AdamKarb2015</footer>

### 7. `<article>` -- Typically a self contained independent piece of writing

* *type:* block-level
* *content:* flow content, sectioning content, palpable content
* *support:* all browsers
* *example:*
```
<article>
  <h4>Read me</h4>
  <p>Lots of words</>
</article>
```
<article>
  <h4>Read me</h4>
  <p>Lots of words</p>
</article>

### 8. `<ul>` -- Creates a list of non-numbered items

* *type:* block-level
* *content:* flow content
* *support:* all browsers not HTML5
* *example:*
```
<ul>
  <li>Dog</li>
  <li>Guinea Pig</li>
</ul>
```
<ul>
  <li>Dog</li>
  <li>Guinea Pig</li>
</ul>

### 9. `<table>` -- Creates a table of inputs

* *type:* block-level
* *content:* flow content
* *support:* all browsers
* *example:*
```
<table>
  <tr>
    <td>Hamster</td>
    <td>Guinea Pig</td>
  </tr>
  <tr>
    <td>Hamster</td>
    <td>Guinea Pig</td>
  </tr>
</table>
```
<table>
  <tr>
    <td>Hamster</td>
    <td>Guinea Pig</td>
  </tr>
  <tr>
    <td>Hamster</td>
    <td>Guinea Pig</td>
  </tr>
</table>

### 10. `<blockquote>` -- Indicates an extended quotation
* *type:* block-level
* *content:* flow content, sectioning root, palpable content
* *support:* all browsers
* *example:* 
```
<blockquote cite="facebook.com/quote">
  <p>This is a quote from facebook</p>
</blockquote>
```
<blockquote cite="facebook.com/quote">
  <p>This is a quote from facebook</p>
</blockquote>

### 11. `<figure>` -- A container for content
* *type:* block-level
* *content:* flow content, sectioning content, palpable, content
* *support:* all browsers
* *example:* 

```
<figure>
  <img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="An awesome picture">
</figure>

```

<figure>
	<img src="https://developer.cdn.mozilla.net/media/img/mdn-logo-sm.png" alt="An awesome picture">
</figure>

### 12. `<li>` -- Denotes a list item 
* *type:* block-level
* *content:* flow content
* *support:* all browsers
* *example:* 

```
<ol>
  <li>cat</li>
  <li>dog</li>
</ol>  
```

<ol>
  <li>cat</li>
  <li>dog</li>
</ol>  

### 13. `<pre>` -- Represents preformatted texts
* *type:* block-level
* *content:* flow content, palpable content
* *support:* basic support all browsers
* *example:* 

```
<pre> Lots of code and stuff </pre>

```

<pre> Lots of code and stuff </pre>

### 14. `<span>` -- Allows grouping for style
* *type:* inline block
* *content:* flow content, phrasing content
* *support:* all browsers
* *example:*

```
<p>I have a <span>beautiful</span> guinea pig</p>
```

<p>I have a <span>beautiful</span> guinea pig</p>

### 15. `<em>` -- Creates epmhasized text in italics
* *type:* inline
* *content:* flow content, phrasing content, palpable content
* *support:* all browsers
* *example:* 

```
<p>I have a <em>beautiful</em> guinea pig</p>
```

<p>I have a <em>beautiful</em> guinea pig</p>

### 16. `<time>` -- Represents time
* *type:* inline
* *content:* flow content, phrasing content, palpable content
* *support:* all browsers
* *example:*

```
<p>It is <time>16:00</time></p>
```
<p>It is <time>16:00</time></p>

### 17. `<br>` -- Creates a page break
* *type:* inline
* *content:* flow content, phrasing content
* *support:* all browsers
* *example:*

``` 
<p>I have a <br> guinea pig</p>
```
<p>I have a <br> guinea pig</p>

### 18. `<a>` -- Represents a hyperlink
* *type:* inline
* *content:* flow content, interactive content
* *support:* all browsers
* *example:*

```
<a href="facebook.com">Facebook</a>

```
<a href="facebook.com">Facebook</a>

### 19. `<i>` -- Italics
* *type:* inline
* *content:* flow content
* *support:* all browsers
* *example:*

```
<p>Ted is a <i>guinea</i> pig</p>
```
<p>Ted is a <i>guinea</i> pig</p>

### 20. `<strong>` -- Creates bold characters
* *type:* inline 
* *content:* flow content, phrasing content
* *support:* all browsers
* *example:*

```
<p>Ted is a <strong>guinea</strong> pig</p>
```
<p>Ted is a <strong>guinea</strong> pig</p>