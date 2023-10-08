<h1>JavaScript Functions</h1>
<h2>A function is used for specific task</h2>
<p>Like sending a message to the user when a button is pressed</p>

<h2>Simple function</h2>
This is how you define a function.<br>
<code>
function testFunction() {
	<br>
    console.log('this is the test function'); 
    <br>
}</code><br>
Call this function as follows.
<br><code>testFunction();</code>
<h2>Function with parameters</h2>

<p>Define the paramiter between the paraentisis</p>
<p>When you call the function, pass parameter value within parentisis</p>
<code>
function greet(name) {

console.log('hi ' + name) <br>
}</code>
<p>To display a name, we need to call this function by using the function name which is greet. Then put the paramiter value which is "devvin". So altogether, we will write greet("devvin") and the end result will be "hi devvin".</p>

<h2>Valid function names</h2>
<p>Names can contain letters, digits, underscores, and dollar signs.</p>
<p>Names are also case sensitive so if you call a variable hi snd HI they would be two different variables.</p>

<h2>How to return a value from a function</h2>
<code>function myFunction() {<br>
 let i = "hi"<br>
 return i;<br>
}<br>

document.getElementById("demo").innerHTML = myFunction();</code>
<h2>Function as an event listener </h2>
<p>First we need to make the function name so lets do that</p>
<p>
<p>
In html you are going to write 
<br><br></p>
<code>&ltbutton id = "buttonid" &gt Button &lt/button&gt</code>
<br>
<code>&ltdiv id  = "displayid"&gt &lt/div&gt</code>
<br>
 then you are going to write in JavaScript 
 <br><br><code> 
 <code>let button = document.getELementById("buttonid")</code>
 <br>
 <code>let display = document.getELementById("displayid")</code>
 <br>
 </code>
 By doing this we are getting the button element and the display element.
 <br><br>
  Now write
   <br><code>
  button.addEventListener("click",displayMessage)
  </code>
 
<br><br><code>
function displayMessage(){
    </code>
    <p>//here you will put what happends when the button is pressed like</p>
  <code>
    display.innerHTML = "helloworld"<br></code>
    //When the button is pressed the message hello will be displayed
<br><code>}</code> </p>

<br>  

<br>
<p></p>
<p></p>
 