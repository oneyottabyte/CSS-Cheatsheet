# CSS Cheatsheet 

## Common CSS Media Queries Breakpoints Cheatsheet 🔥
```css
@media only screen and (min-width: 1800px) {}
@media only screen and (min-width: 1200px) and (max-width: 1799px) {}
@media only screen and (min-width: 992px) and (max-width: 1199px) {}
@media only screen and (min-width: 768px) and (max-width: 991px) {}
@media only screen and (min-width: 481px) and (max-width: 767px) {}
@media only screen and (max-width: 480px) {}
@media only screen and (orientation: landscape) {}
@media only screen and (orientation: portrait) {
```

## Smooth scrolling Cheatsheet 🔥
```css
html{
    scroll-behavior: smooth;
}
```

## 7 Amazing CSS properties 🔥

### word-spacing
###### Similar to letter-spacing, but defines the value of spacing between indivual words.
```css
.text {
    word-spacing: 1rem;
}
```

### text-align-last
###### Alings the last line alone of a paragraph.
```css
.text {
    text-align-last: right;
}
```

### text-emphasis
###### Adds emphasis marks to text.
```css
.text {
    text-emphasis: '🔥';
}
```

### text-wrap
###### Adds emphasis marks to text.
```css
.text {
    text-wrap: balance;
}
.text {
    text-wrap: nowrap;
}
```

### pointer-events
###### Determines whether or not an element should react to pointer events.
```css
.content{
    pointer-events: auto;
}
.content{
    pointer-events: none;
}
```

### tab-size
###### Sets the size of the tab character in terms of either number of space or absolute lenght value.
```css
.content {
    tab-size: 4;
}
```

### user-select
###### Determines whether or not the user can select test from the element.
```css
p {
    user-select: none;
}
p {
    user-select: auto;
}
```