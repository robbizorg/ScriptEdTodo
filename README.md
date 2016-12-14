# ScriptEdTodo

###A TODO App project to get you thinking about CRUD Design

Hints: Even if you don't think you're not going to have enough time to make it to the challenge, think about how you would have to structure your code to get the challenges running

  - Don't just use jQuery append stuff to your html, think about how you can use JavaScript to render a bunch of items and have control over them
  
####Minimum Requirements:

 - Can create new items!
 - Have a button that deletes all the todos
 - Have counter that tells you which order the todos were made in
 
####Challenges (aka if you finish the above, get started on these):

 - Can Edit and Delete Individual Items (If you do this, you've built a CRUD App!)
 - Hard Challenge: Display Items depending on whether or not they're completed (If you do this, I'd give you Bonus Points if I could)

####Some Useful JavaScript Hints

    var x = 5; // Declaring a variable in JavaScript
    var array = ["some", "awesome", "stuff"]; // Making an Array
    
    // What does this code do?
    var array = [“hello”, “world”, “and”, “anyone”, “else”];
    var html = [];
    for (var i = 0; i < array.length; i++) {
      var newItem = “<p>” + array[i] + “</p>”;
      html.push(newItem);
    }
    console.log(html); // What will I print?
    html = [];
    console.log(html); // How about now?
