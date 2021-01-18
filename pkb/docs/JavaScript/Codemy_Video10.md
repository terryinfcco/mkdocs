
## Codemy Javascript Video 10

**Conditional Statements**

If Statement: if (conditional in parentheses) {Code Block to execute in curly brackets}

    <script>
        firstName = "John";
        
        if (firstName == "John){
            document.getElementById("demo").innerHTML = firstName;
        }
    </script>

Else just another code block:

    <script>
        firstName = "John";
        
        if (firstName == "John){
            document.getElementById("demo").innerHTML = firstName;
        } else {
            document.getElementById("demo").innerHTML = "Name not John";
        }
    </script>

Else if just adds more blocks:
    
    <script>
        firstName = "John";
        
        if (firstName == "John"){
            document.getElementById("demo").innerHTML = firstName;
        } else if (firstName == "Tim"){
            document.getElementById("demo").innerHTML = "Hi Tim";
        } else {
            document.getElementById("demo").innerHTML = "Name not John";
        }
    </script>

