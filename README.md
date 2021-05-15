# Set up
Copy and Paste this code into your bookmark bar
```js
javascript:(function()%7Bfetch(%22https%3A%2F%2Fraw.githubusercontent.com%2Fseanv999%2FquizizzAutoAnswer%2Fmain%2FBundle.js%22)%0A.then((res)%20%3D%3E%20res.text()%0A.then((t)%20%3D%3E%20eval(t)))%7D)()%3B
```

# Getting answers
Once you are on your quiz run the bookmarklet or paste this code into console
Then click E and question should auto solve if its a basic MSQ, MCQ, BLANK.
```js
fetch("https://raw.githubusercontent.com/seanv999/quizizzAutoAnswer/main/Bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
