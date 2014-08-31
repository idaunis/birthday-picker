birthday-picker
===============

A jquery plugin for birthday. 

Dependencies

Birthday Picker requires the following libraries:

The latest Jquery, which you can download from here.
The latest Bootstrap, you can download from here.
Getting Started

Download the latest code from here

How to use Birthday Picker

Include the following css files into the header
```
<link href="http://example.com/css/bootstrap.min.css" rel="stylesheet">
```
Include the javascript files into the page
```
<script src="http://example.com/js/jquery.min.js"></script>

<script src="http://example.com/js/bootstrap.min.js"></script>

<script src="http://example.com/js/jquery-birthday-picker.js"></script>
```
HTML decoration for your images goes like this
```
<div id="birthdayPicker"></div>
```
Include the following near the end of the page or in a seperate javascript file
```
<script type="text/javascript">
    $("#birthdayPicker").birthdayPicker();
</script>
```
Initialization Options

The following are the initialization options and their default values
```
maxAge : 100

minAge : 0

maxYear : todayYear

"dateFormat" : "middleEndian"

"monthFormat" : "number"

"placeholder" : true

"defaultDate" : false

"sizeClass"	: "span1"
```
You can override any of these values during initialization.
