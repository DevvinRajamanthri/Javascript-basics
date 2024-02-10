<h1>Javacscript Strings</h1>
<h3>In this git page we will learn how to create, read (whole string, one char). update (whole string, just one char), delete (string, char)</h3>
<h2>What is a string</h2>
<p>A string is a series of characters inside of quotations</p>
<!-- next -->
<h2>How to create a string</h2>
<p>To create a string you need to write a variable then assign a pair of quotations to it and inside write the word or letter you want to assign to it</p>
<br>
<code>let example = "string"</code>
<!-- next -->
<h2>How to read a string</h2>
<p>to read a string you need to write a console.log or a .innerHTML statement<br>
the console.log() reads the string and puts the result in the console. But the innerHTML puts the result on the ui</p>
<br>
<code>let i = "string"<br>
console.log(i)
<br>
OR
let display = document.getElementById("Example)<br>
let i = "string"<br>
display.innerHTML = i<br>
</code>
<!-- next -->
<h2>How to read one element of the a string</h2>
<p>To read an element of a string you need to write charAt()
inside the parentheses you will write the index of the element you want to access</p>
<code>let i = "hello"
i = i.charAt(1)<br>
console.log(i)</code>
<p>the result would be "e"</p>
<!-- next -->
<h2>How to update a string</h2>
<p>To update a string you need to change the value of the string in a new variable or reassign it to itself</p>
<br>
<h4>When reassigning</h4>
<code>Let i = "string"
<br>
i = "updated_string"
</code>
<!-- next -->

<h2>How to update a word of the string</h2>
<p>To update an word use replace()</p>
<code>let i  = "replace Devvin"<br>
replace(index_of_the_word_you_want_to_replace, what_you_want_to_replace_it_with)<br>
i.replace("replace", "Hello")<br>
<p>the result will be "Hello Devvin"
<br>
<p>And not "replace Devvin"</p>

</code>
<!-- next -->

<h2>How to delete a string</h2>
<p>To delete a string remove whats inside it</p>
<br>
<code>let i = ""</code>
<!-- next -->
 
<h2>How to delete a strings element</h2>
<p>To delete a strings element use splice.</p>
<br>
<code>splice(where you wanna splice(IT HAS TO BE A NUMBER),how many characters you wanna remove after you remove the specified element(IT HAS TO BE A NUMBER),What you wanna add <br>after the specified index(IT HAS TO BE A STRING AND THERE CAN BE AS MANY AS YOU WANT))<br><br>
<code>let i = "hello"<br>
console.log(i.splice(0, 1, "j))</code>
<p>the result would be "jello"</p></code>
