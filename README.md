# Angular JS Binding Demo

This project shows the two-way data binding in Angular JS. The code will dynamically change the background color of web page.

### Setup

For this demo I am using Angular JS 1.6.4

```html
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.4/angular.min.js"></script>
```

### Code

```html
<body style="background: {{yourColor}};">
    <input type="text" ng-model="yourColor" />
</body>
```

### Explanation

The color hex code that you type in the input box will dynamically become the body's background color, this is because the value of your input is bound to your body via ng-model.
