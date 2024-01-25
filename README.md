# Yankun's CSS Guide

**Cascading Style Sheets (CSS)** is the adjective, or the visuals, of a webpage. 

It is not a programming language, but a descriptive language. Have the right mindset when learning it!! It is a lot of fun!!!

[MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## CSS Basics

Everything in CSS follows the **CSS Pattern**:
```
selector {
    property: value;
}
```
For example, here is how to make all `<h1>` purple:
```
h1 {
    color: purple;
}
```
We can have two different properties as well:
```
img {
    width: 100px;
    height: 200px;
}
```
It could get fairly complex as well:
```
input[type="text"]:nth-of-type(2n){
    border:2px solid red;
}
```

### How to Include Styles?

* Inline Styles in html - DO NOT DO THIS (because you can't share them)
* Style Element -  this is also not recommended because how do you share this across html files?
* External Stylesheet - write in `.css` file and include using `<link>`

#### Link Element

The link element goes into the `<head>`:
```
<link rel=-"stylesheet" href="file.css">
```

## Colors

[The color property](https://developer.mozilla.org/en-US/docs/Web/CSS/color) changes the text color.



