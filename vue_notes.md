-  Directives are prefixed with v- to indicate that they are special attributes provided by Vue

```
    <div id="app">
        <p v-bind:title="message">{{mesage}}</p>

    </div>

    new Vue({
        el: "#app",
        data: {
            message: "Hello, Welcome to the word of fruits" + new Date().localString(),
            fruits = ["papaya", "Banana", "Orange"]
        }
    })
```