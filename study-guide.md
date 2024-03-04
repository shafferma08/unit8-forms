<p><strong>Question 1:</strong><br>
The developers have been asked to add descriptions to all elements on the community service form. What will they use to do this?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. The <code>&lt;legend&gt;</code> element</li>
<li>B. The <code>&lt;button&gt;</code> element</li>
<li>C. The <code>&lt;label&gt;</code> element</li>
<li>D. The <code>&lt;output&gt;</code> element</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>C. The <code>&lt;label&gt;</code> element</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>&lt;label&gt;</code> element is used to define a label for an <code>&lt;input&gt;</code> element in HTML forms. Labels are typically used to provide a description of the input field, improving the usability and accessibility of the form. A <code>&lt;label&gt;</code> is associated with a specific form control through the <code>for</code> attribute, which matches the <code>id</code> of the control.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>name<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Name:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>text<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>name<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>name<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, the label “Name:” is associated with the text input field.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label">MDN Web Docs - <code>&lt;label&gt;</code></a>: Detailed documentation on the label element.</li>
<li><a href="https://www.w3schools.com/tags/tag_label.asp">W3Schools - HTML <code>&lt;label&gt;</code> Tag</a>: Tutorial and examples on using the label element.</li>
</ul>
<hr>
<p><strong>Question 2:</strong><br>
What is the purpose of the <code>&lt;select&gt;</code> element?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. It adds a caption for a group of items created by the <code>&lt;fieldset&gt;</code> element.</li>
<li>B. It creates a drop-down list of options in a form that the user may click on.</li>
<li>C. It groups elements so that related fields are placed together in a form.</li>
<li>D. It provides pre-defined options that sort and autocomplete as users type in the field.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>B. It creates a drop-down list of options in a form that the user may click on.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>&lt;select&gt;</code> element is used to create a drop-down list in HTML forms. The <code>&lt;select&gt;</code> element contains one or more <code>&lt;option&gt;</code> elements that define the options available to choose from.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>pets<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Choose a pet:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>select</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>pets<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>pets<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>dog<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Dog<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>cat<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Cat<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>hamster<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Hamster<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>parrot<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Parrot<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>spider<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Spider<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>goldfish<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Goldfish<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>option</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>select</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, a drop-down list is created with various pet options to choose from.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select">MDN Web Docs - <code>&lt;select&gt;</code></a>: Detailed documentation on the select element.</li>
<li><a href="https://www.w3schools.com/tags/tag_select.asp">W3Schools - HTML <code>&lt;select&gt;</code> Tag</a>: Tutorial and examples on using the select element.</li>
</ul>
<hr>
<p><strong>Question 3:</strong><br>
Brad created an input field using the <code>&lt;datalist&gt;</code> element to provide a pre-defined list of berries that the user can choose from when ordering a smoothie. When he renders the form, the list does not show. What is the problem?</p>
<p><strong>Given Code:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>datalist</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>berry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>raspberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>blueberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>strawberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>blackberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>datalist</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p><strong>Options:</strong></p>
<ul>
<li>A. The <code>&lt;datalist&gt;</code> element’s option attribute is missing.</li>
<li>B. The <code>&lt;input&gt;</code> element’s name attribute is missing.</li>
<li>C. The <code>&lt;input&gt;</code> element’s list attribute is missing.</li>
<li>D. The <code>&lt;option&gt;</code> element’s value attribute is missing.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>C. The <code>&lt;input&gt;</code> element’s list attribute is missing.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>&lt;datalist&gt;</code> element is used to specify a list of pre-defined options for an <code>&lt;input&gt;</code> element. The list is not displayed unless it is associated with an <code>&lt;input&gt;</code> element using the <code>list</code> attribute, which must match the <code>id</code> of the <code>&lt;datalist&gt;</code>.</p>
<p><strong>Corrected Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">list</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>berry<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>berryChoice<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>berryChoice<span class="token punctuation">"</span></span> <span class="token punctuation">/&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>datalist</span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>berry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>raspberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>blueberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>strawberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>option</span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>blackberry<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>datalist</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this corrected example, the <code>&lt;input&gt;</code> element is associated with the <code>&lt;datalist&gt;</code> by using the <code>list</code> attribute.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist">MDN Web Docs - <code>&lt;datalist&gt;</code></a>: Detailed documentation on the datalist element.</li>
<li><a href="https://www.w3schools.com/tags/tag_datalist.asp">W3Schools - HTML <code>&lt;datalist&gt;</code> Tag</a>: Tutorial and examples on using the datalist element.</li>
</ul>
<hr>
<p><strong>Question 4:</strong><br>
What is the purpose of the <code>&lt;output&gt;</code> element?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. It saves and reuses the result of a calculation performed by a script.</li>
<li>B. It specifies a list of pre-defined choices for an <code>&lt;input&gt;</code> element.</li>
<li>C. It designates the beginning of a form on a page.</li>
<li>D. It identifies a list of options from which a user can make choices.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>A. It saves and reuses the result of a calculation performed by a script.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>&lt;output&gt;</code> element is used to represent the result of a calculation or user action within a form. It can display the result of a calculation done by JavaScript.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span> <span class="token attr-name">oninput</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>result.value=parseInt(a.value)+parseInt(b.value)<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>range<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>a<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>a<span class="token punctuation">"</span></span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>50<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  + 
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>number<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>b<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>b<span class="token punctuation">"</span></span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>50<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  = 
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>output</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>result<span class="token punctuation">"</span></span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>a b<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>100<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>output</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, as the user changes the values of the input fields, the <code>&lt;output&gt;</code> element updates to show the sum of the two numbers.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/output">MDN Web Docs - <code>&lt;output&gt;</code></a>: Detailed documentation on the output element.</li>
<li><a href="https://www.w3schools.com/tags/tag_output.asp">W3Schools - HTML <code>&lt;output&gt;</code> Tag</a>: Tutorial and examples on using the output element.</li>
</ul>
<hr>
<p><strong>Question 5:</strong><br>
Marketing wants to make it easy for mobile users to provide feedback on products. The form has a comments area that is created by the <code>&lt;textarea&gt;</code> element. What can a developer do to activate this field when the users open the Product Feedback form?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. Use the <code>autofocus</code> attribute with the <code>&lt;textarea&gt;</code> element.</li>
<li>B. Use the <code>required</code> attribute with the <code>&lt;form&gt;</code> element.</li>
<li>C. Use a CSS rule to make the <code>&lt;textarea&gt;</code> bold.</li>
<li>D. Use the <code>disabled</code> attribute on all other form elements.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>A. Use the <code>autofocus</code> attribute with the <code>&lt;textarea&gt;</code> element.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>autofocus</code> attribute is a Boolean attribute that when present, automatically focuses the form control upon page load. This is useful for guiding users directly to the input field that needs to be filled out, which in this case, is the comments area for feedback.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>textarea</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>comments<span class="token punctuation">"</span></span> <span class="token attr-name">autofocus</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>textarea</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, when the Product Feedback form is loaded, the <code>textarea</code> element where users can leave their comments will automatically be focused, allowing them to start typing immediately.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea">MDN Web Docs - <code>&lt;textarea&gt;</code></a>: Detailed documentation on the textarea element.</li>
<li><a href="https://www.w3schools.com/tags/tag_textarea.asp">W3Schools - HTML <code>&lt;textarea&gt;</code> Tag</a>: Tutorial and examples on using the textarea element.</li>
</ul>
<hr>
<p><strong>Question 6:</strong><br>
The customer service team is complaining about poor user input on the new Promotional Contest form. They want the web team to fix this immediately. What option is the best choice to use for improving the quality of input from users?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. Use built-in processes to check and validate user input before the form is submitted.</li>
<li>B. Use a <code>&lt;fieldset&gt;</code> element to group elements that are related to each other.</li>
<li>C. Use the <code>placeholder</code> attribute on every input, select, and textarea fields on the form.</li>
<li>D. Use labels to provide descriptions of every input field on the Promotional Contest form.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>A. Use built-in processes to check and validate user input before the form is submitted.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
Validation processes are crucial for ensuring that the data entered by users meets the form’s requirements before submission. This could include checking for proper formats, ensuring required fields are not empty, and that entered data falls within certain constraints.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>contestForm<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Email:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">required</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>submit<span class="token punctuation">"</span></span> <span class="token attr-name">value</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Submit<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>script</span><span class="token punctuation">&gt;</span></span><span class="token script language-javascript">
  document<span class="token punctuation">.</span>contestForm<span class="token punctuation">.</span><span class="token function">addEventListener</span><span class="token punctuation">(</span><span class="token string">'submit'</span><span class="token punctuation">,</span> <span class="token keyword">function</span><span class="token punctuation">(</span>event<span class="token punctuation">)</span> <span class="token punctuation">{</span>
    <span class="token keyword">var</span> email <span class="token operator">=</span> document<span class="token punctuation">.</span>contestForm<span class="token punctuation">.</span>email<span class="token punctuation">.</span>value<span class="token punctuation">;</span>
    <span class="token keyword">if</span> <span class="token punctuation">(</span><span class="token operator">!</span>email<span class="token punctuation">.</span><span class="token function">includes</span><span class="token punctuation">(</span><span class="token string">'@'</span><span class="token punctuation">)</span><span class="token punctuation">)</span> <span class="token punctuation">{</span>
      <span class="token function">alert</span><span class="token punctuation">(</span><span class="token string">"Please enter a valid email address."</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
      event<span class="token punctuation">.</span><span class="token function">preventDefault</span><span class="token punctuation">(</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
  <span class="token punctuation">}</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
</span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>script</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, a simple client-side validation checks if the email address entered contains an ‘@’ symbol before allowing the form to be submitted.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation">MDN Web Docs - Form data validation</a>: Detailed guide on implementing form validation.</li>
<li><a href="https://www.w3schools.com/js/js_validation.asp">W3Schools - JavaScript Form Validation</a>: Tutorial on client-side form validation using JavaScript.</li>
</ul>
<hr>
<p><strong>Question 7:</strong><br>
The web team is meeting to discuss the HTML5 semantic elements. There is confusion about what their overall purpose is. What definition would help them get clarity?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. Semantic elements describe their purpose to a human reading the code.</li>
<li>B. Semantic elements will automatically validate the user’s data input.</li>
<li>C. Semantic elements are designed to work properly in previous versions of HTML.</li>
<li>D. Semantic elements purpose is to support forms in responsive web design.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>A. Semantic elements describe their purpose to a human reading the code.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
Semantic elements in HTML5 clearly describe their meaning to both the browser and the developer. They provide information about the type of content that they contain, which helps with search engine optimization, accessibility, and maintaining clean, easy-to-understand code.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>article</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>header</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>h1</span><span class="token punctuation">&gt;</span></span>Blog Post Title<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>h1</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>header</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>section</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>The content of the blog post...<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>section</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>footer</span><span class="token punctuation">&gt;</span></span>
    <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>p</span><span class="token punctuation">&gt;</span></span>Posted by the author<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>p</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>footer</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>article</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, the <code>&lt;article&gt;</code>, <code>&lt;header&gt;</code>, <code>&lt;section&gt;</code>, and <code>&lt;footer&gt;</code> elements provide clear indicators of their content to anyone reading the HTML code.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html">MDN Web Docs - Semantic HTML</a>: Explains the importance of semantics in HTML.</li>
<li><a href="https://www.w3schools.com/html/html5_semantic_elements.asp">W3Schools - HTML5 Semantic Elements</a>: Overview and examples of semantic elements in HTML5.</li>
</ul>
<hr>
<p><strong>Question 8:</strong><br>
Mindy just finished a webinar on the HTML5 web forms. She is preparing a summary of the webinar and wants to emphasize the purpose of the new semantic input types. Which of the following should she include in her summary?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. They describe to developers and browsers the type of input being asked for.</li>
<li>B. They help the user provide input that the developers are looking for.</li>
<li>C. They check and validate the input provided by the user to ensure it is correct.</li>
<li>D. They provide an autocomplete feature in textboxes and dropdown lists.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>A. They describe to developers and browsers the type of input being asked for.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
HTML5 introduced new semantic input types that provide a better description of the data to be entered. These input types help both the browser and the developer understand what kind of data is expected, and the browser can provide the appropriate keyboard on mobile devices and basic validation to assist users.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>user-email<span class="token punctuation">"</span></span> <span class="token attr-name">placeholder</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>Enter your email<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>date<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>user-birthday<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In these examples, the <code>type="email"</code> and <code>type="date"</code> input fields are semantic because they clearly define the expected input data type for email addresses and dates, respectively.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input">MDN Web Docs - <code>&lt;input&gt;</code>: The Input (Form Input) element</a>: Detailed documentation on the input element and its types.</li>
<li><a href="https://www.w3schools.com/html/html_form_input_types.asp">W3Schools - HTML5 Form Input Types</a>: Overview of new HTML5 form input types.</li>
</ul>
<hr>
<p><strong>Question 9:</strong><br>
Consider the following code:</p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>fName<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>First Name: <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>textbox<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>fName<span class="token punctuation">"</span></span><span class="token punctuation">/&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>lName<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Last Name: <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>textbox<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>lName<span class="token punctuation">"</span></span><span class="token punctuation">/&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>What is the purpose of the <code>for</code> attribute?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. It makes the form compliant with accessibility guidelines.</li>
<li>B. It binds a label element to the correct input element.</li>
<li>C. It binds the label and input elements to the form.</li>
<li>D. It makes the form usable on mobile devices.</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>B. It binds a label element to the correct input element.</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>for</code> attribute in the <code>&lt;label&gt;</code> element specifies which form element a label is bound to. The value of the <code>for</code> attribute must be the same as the value of the <code>id</code> attribute of the related input to bind them together. This enhances user accessibility by allowing users to click on the label to focus/select the input element.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Email:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>email<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>user-email<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, clicking on the “Email:” label will focus on the associated input field.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label">MDN Web Docs - <code>&lt;label&gt;</code>: The Label element</a>: Detailed documentation on the label element and the <code>for</code> attribute.</li>
<li><a href="https://www.w3schools.com/tags/att_label_for.asp">W3Schools - HTML <code>&lt;label&gt;</code> for Attribute</a>: Explanation and example of using the <code>for</code> attribute with the label element.</li>
</ul>
<hr>
<p><strong>Question 10:</strong><br>
Amy has been asked to modify a form so that a user can enter a date (without time zone). She wants to use a drop-down, date-picker calendar. Which input type will she use?</p>
<p><strong>Options:</strong></p>
<ul>
<li>A. datetime-local</li>
<li>B. time</li>
<li>C. datetime</li>
<li>D. date</li>
</ul>
<p><strong>Correct Answer:</strong></p>
<ul>
<li>D. date</li>
</ul>
<p><strong>Resource and Explanation:</strong><br>
The <code>date</code> input type creates a control that lets users easily enter a date (year, month, and day), presenting a date-picker calendar without requiring them to specify the time zone.</p>
<p><strong>Example:</strong></p>
<pre class=" language-html"><code class="prism  language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>form</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>label</span> <span class="token attr-name">for</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>appointmentDate<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>Choose a date for your appointment:<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>label</span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>input</span> <span class="token attr-name">type</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>date<span class="token punctuation">"</span></span> <span class="token attr-name">id</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>appointmentDate<span class="token punctuation">"</span></span> <span class="token attr-name">name</span><span class="token attr-value"><span class="token punctuation">=</span><span class="token punctuation">"</span>appointment-date<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>form</span><span class="token punctuation">&gt;</span></span>
</code></pre>
<p>In this example, a date-picker is presented to the user to choose a specific date for an appointment.</p>
<p><strong>Additional Resources:</strong></p>
<ul>
<li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date">MDN Web Docs - <code>&lt;input type="date"&gt;</code></a>: Detailed documentation on the date input type.</li>
<li><a href="https://www.w3schools.com/html/html_form_input_types.asp">W3Schools - HTML <code>&lt;input type="date"&gt;</code></a>: Tutorial and examples of different input types, including the date type.</li>
</ul>
<hr>

