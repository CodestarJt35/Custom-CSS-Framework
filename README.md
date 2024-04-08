# Custom CSS Framework: Beautified Framework

# Team:

**name:** Jana Tahir 

**Student Number:** 041033395

## Welcome
Welcome to my custom framework. 

In order to style your project with this theme, add this framework's CSS into your project and link it to your HTML project within the `head` tag and assign the appropriate tag to start getting it styled, and if necessary, provide the class according to this framework. 

Also, to get the Didact Gothic font used in this framework for your project, link to the Google Fonts API in your HTML file like below.

<link rel="stylesheet" type="text/css" href="styles.css" />
<link href="https://fonts.googleapis.com/css2?family=Didact+Gothic&display=swap" rel="stylesheet">

## Custom Counter
You can use this custom counter written as a web component. You can specify its starting value, min value, step value, and max value. Don't forget to add JS script code within your HTML. In the below example, the starting value is 20, min is 2, max is 50, and each step goes up/down by 2.

<custom-counter value="20" min="2" max="50" step="2"></custom-counter>

<script src="./custom-counter.js"></script>
<script>
    document.querySelector('custom-counter').addEventListener('change', (e) => {})
</script>

## Headings
These are the various headings you can use:

<h1></h1>
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6>

## Nav Bar
The nav bar looks like the nav bar shown Below:

<nav class="navbar sticky">
    <ul>
        <li><a class="title" heref="#">TITLE</a></li>
        <li><a href="#">Home</a>
            <ul class="dropdown">
                <li><a href="#">Sub-1</a></li>
                <li><a href="#">Sub-2</a></li>
                <li><a href="#">Sub-3</a></li>
            </ul>
        </li>
        <li><a href="#">Features</a>
            <ul class="dropdown">
                <li><a href="#">Sub-1</a></li>
                <li><a href="#">Sub-2</a></li>
                <li><a href="#">Sub-3</a></li>
            </ul>
        </li>
        <li><a href="#">About</a></li>
    </ul>

    <ul>
        <li><a href="#">Contact Us</a></li>
        <li><a href="#">Git</a></li>
    </ul>
</nav>
    
## Buttons
These are the various buttons you can use:

## Success Alert Dark

<button></button>
<button class="btn-alert"></button>
<button class="btn-dark"></button>

## Selectors
These are the various selector styles you can use:

### Activate?
### CheckBox
### Radio Choice 1
### Radio Choice 2

<div class="selectors">
    <label class="checkbox">
        <input type="checkbox">
        <span>Activate?</span>
    </label>

    <label class="checkbox-check">
        <input type="checkbox">
        <span>CheckBox</span>
    </label>

    <label class="radio">
        <input type="radio" name="choice">
        <span>Radio Choice 1</span>
    </label>

    <label class="radio">
        <input type="radio" name="choice">
        <span>Radio Choice 2</span>
    </label>
</div>

# Forms
These are the form stylings:

### Name
### enter name
### Email
### enter email
### Password
### enter password
### Notes
### notes

<form>
    <label>Name</label>
    <input type="text" placeholder="enter name" />
    <input type="submit">
</form>
