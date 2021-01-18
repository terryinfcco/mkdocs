## Video 4

### 4 Ways to Output to a Web Page

1. innerHTML - replace text in an existing element

```
<h1 id="demo">Hello World!</h1>
<script>
	document.getElementByID("demo").innerHTML = "I like celery"
</script>

```
 
2. Document Write

```
document.write("I really like Celery")
```

Just dumps text to the screen whereever js code is located in the html document.

Not usually used. Erases page if used after page is already loaded.

3. Window Alert

```
window.alert("I still really like celery")
```
Creates a popup on the screen

4. Console

```
console.log("Just Kidding")
```

Doesn't go on screen but to developer console.