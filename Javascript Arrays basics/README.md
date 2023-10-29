<h1>Javascript array basics</h1>
I will be telling you what an array is and a few things you can do with it in this github<br>
page.<br>
<h3>How to write an array</h3><br>
An array is a collection of data.<br>
To make an array you have to write a pair of brackets. Then inside the pair of brackets,
write a few values such as strings or numbers or both, separated by commas.<br>
For example,<br>
<code>
Let a = [1,2]<br>
Let b = [“hi”,”bye”]<br>
Let a = [1,2,”string”]<br>
</code>
<h3>How to update an element in a array.</h3><br>
Now I'm going to tell you how to update an element.<br> To update an element, you need to
write the array name and a pair of brackets. <br>Inside the brackets, write the index of the element
you want to update. Then, write the assignment operator and update it to the new element<br>
value.<br>
Example<br>
<code>
Let a = [1,2]<br>
a[1] = 3<br>
console.log(a)<br>
result :[1,3]<br>
</code>
Now the element specified by index is changed to the number 3.<br>
<h3>How to insert an element into an array.</h3><br>
Now I'm going to tell you how to insert an element at any index you want.<br> First, Call the
splice function on the array.<br> The first parameter is the index where you choose to insert the
element.<br> The second parameter is how many elements you will remove after the specified
index.Then write your custom element.<br>

Example of inserting a single element: <br>
<code>
Let a = [1,2,3,4]<br>
a.splice(1,0,4)<br>
console.log(a)<br>
Result:[1,4,2,3,4]<br></code>

We are using 0 because we are not removing any elements<br>

The new element got inserted into index.<br>
Example of inserting multiple elements: <br>
<code>
Let a = [1,2,3,4]<br>
a.splice(1,0,4,5)<br>
console.log(a)<br>
Result:[1,4,5,2,3,4]<br>
</code>
4 got inserted into index 1 and five into the next<br>
<h3>How to push an element to the end of an array.</h3><br>
Now im going to tell you how to push a element into the end of an array.<br>
First your going to write the array name then write a dot after. Then call the push function and<br>
inside the parentheses write what elements you want to push into the end of the array.<br>
Example:<br>
<code>
Let a = [1,2,3,4]<br>
a.push(1)<br>
console.log(a)<br>
Result:[1,2,3,4,1]<br>
</code>
<br>
1 got pushed to the end of the array<br>
<br>
<h3>How to remove an element from the back of an array.</h3><br>
Now, i’m going to tell you how to remove a element from the end of a array.<br>
First, write the array name then a period then call the pop function.<br>
Example: <br>
<code>
let a = [“hi”,”hello”,”hola”];<br>
a.pop()<br>
Result:[“hi”,”hello”];<br>
</code>
<h3>How to remove an element from an array.</h3>
First call the splice function.<br> Then write the index of the array you want to remove in the array. Then write how many elements you want to remove after the specified index.
<br>
Example:<br>
<code>
let a = [“hi”,”hello”,”hola”];<br>
a.splice(0,1)<br>
Result:[“hi”,”hello”];<br>
</code>
