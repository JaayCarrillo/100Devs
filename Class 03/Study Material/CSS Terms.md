# Common CSS Terms: 
* Selectors: target elements by their element type
Ex: 
```
div {...}
```

* Properties: 
Ex: 
``` 
.house{...}
```
* Values: 
* Type Selectors: 
* Class Selectors: 
* ID Selectors: target only one unique element at a time
Ex: 
``` 
#jaaysroom{...}
```

# Referencing your CSS 
This needs to be done within your HTML file. A best practice is to reference your CSS file within your HTML file. THis is done under a single external style sheet. Which could be within your <head> element.
The reason to do this is because it allows for accessibility across an entire website where alterations can be made possible at any time. 

example: 
``` 
<head>
<link rel="stylesheet" href="main.css">
</head>
```
