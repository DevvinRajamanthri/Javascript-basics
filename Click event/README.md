<h1>How to use click event</h1>

<h2>In this github you will learn how to write a click event and what you can do with it</h2>
<br>
<p>first i will write the button in html</p>
<br>
<code><pre> 
&lt button id = "example-button"&gt &lt/button&gt </pre></code>
<p>This makes the button.<p>

<br> Now i will get the element  of the button by using and store it in variable</p>

<code>let button = document.getElementById("example-button")<br></code>
<p>Then i will write the function and inside the function you can write what will happen when the button is clicked</p>
>
<pre>function onClick{<br>
    console.log('hello') <br>   
}</pre><br>

<p>Now i will write what the Eventlistener which checks if the button is clicked and if it is the eventlistener triggers the function</p><br>
<p>first i will write the variable name then i will write a dot. I will write addEventListener after the dot then write paranthisis and inside the paraenthis i will write the event as the first parameter then then function name in the second so then that will be the function that that gets trigged</p>
<pre>element.addEventListener('click',onClick)</pre>
<image src = "example1.png" width = "700" height = "500">