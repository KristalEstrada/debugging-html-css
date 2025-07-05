<aside>
 <h2>Debugging Notes </h2>
   <ul>
    <li><strong>missing lang</strong> Fixed by adding <code>lang="en"</code></li>
    <li><strong>Empty &lt;meta&gt; tag:</strong> Fixed by adding <code>charset="UTF-8"</code> and completing the viewport line.</li>
    <li><strong>Trailing slashes on &lt;link&gt; tags:</strong> Removed the <code>/</code> at the end of <code>&lt;link&gt;</code> tags for HTML5 compliance.</li>
    <li><strong>Missing alt on image:</strong> Added <code>alt="Easter Bunny Profile Image"</code> to the <code>&lt;img&gt;</code> tag for accessibility.</li>
    <li><strong>Improper nesting of tags:</strong> Moved paragraph content outside of the <code>&lt;h3&gt;</code> tag for correct structure.</li>
    <li><strong>Stray character in header:</strong> Removed extra <code>&lt;</code> symbol that appeared after the paragraph in the header.</li>
    <li><strong>Missing closing tags:</strong> Added <code>&lt;/body&gt;</code> and <code>&lt;/html&gt;</code> at the bottom of the page to properly close the document.</li>
  </ul>
</aside>

33	footer	Value Error : color #B2 is not a valid color 3 or 6 hexadecimals numbers : #B2  LOOKED FOR COLOR ON EXPECTED FROM IMAGES GRABED COLOR CODE FROM WITHIN STYLE.CSS
43	h1	Value Error : font-size Too many values or values are not recognized : 5 vw REMOVED SPACE BETWEEN 5 AND VW 
66	p	Value Error : line-height Unknown dimension 1.35me swicthed m and e around to correct 
85	.error	Value Error : color #FE27122 is not a valid color 3 or 6 hexadecimals numbers : #FE27122 error color is red removed extra two on number code 
94	a:hover	Value Error : text-decoration all is not a text-decoration value : all all is not a valid value for text decoration replaced with none
line 8 changed background coolor to white 