# polymerlogin

* Polymer Login provides the following features:
* Displays a form containing: username input + password input + login button.
* Username has to be email and invalid email will be validated.
* Password should be of minimum to maximum length and invalid pwd will be validated

## Installation

To install this component, follow the procedure:
 ```js 
 Add dependency in bower.json

  "dependencies": {

    "polymer-login": "git+https://github.com/Polymer-Developers-Forums/polymerlogin.git"
}
```


### Import in index.html of root directory: 
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="viewport" content="width=device-width, minimum-scale=1.0, initial-scale=1.0, user-scalable=yes">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="mobile-web-app-capable" content="yes">
    <title>Polymer Project</title>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>   
     <link rel="import" href="bower_components/polymer-login-form/polymer-login.html" />    
</head>
<body>
      
</body>
</html>
```
### Examples:

```html
add the component in any HTML file
<polymer-login></polymer-login>
```
