# bootstrap-tag-input
A simple, easy-to-use library for creating tabs (or chips) as a multi-entry input option.  This library uses Bootstrap 5, and integrates nicely with Bootstrap code.  No jQuery needed!

## Usage

You only need the bootstrap library (and the JS and css files from this project) to make this work:
```html
<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap Tag Input -->


<!-- Basic tags input  -->
<div class="input-group">
    <span class="input-group-text">Basic tags input</span>
    <div class="tags-input form-control"></div>
</div>
```

## Options

```html
<!-- Basic tags input  -->
<div class="input-group">
    <span class="input-group-text">Basic tags input</span>
    <div class="tags-input form-control"></div>
</div>
<br>

<!-- Use custom classes to style tags with Bootstrap styles -->
<div class="input-group">
    <span class="input-group-text">Colored tags</span>
    <div class="tags-input form-control tag-bg-success"></div>
</div>
<br>

<!-- Name the hidden input field so you can find it in your code -->
<div class="input-group">
    <span class="input-group-text">Named input</span>
    <div class="tags-input form-control" data-name="myTagInput"></div>
</div>
<br>

<!-- Choose your regex to split tags by -->
<div class="input-group">
    <span class="input-group-text">Custom split regex</span>
    <div class="tags-input form-control" data-splitchars="[;']"></div>
</div>
<br>

<!-- No label -->
<div class="input-group">
    <div class="tags-input form-control tag-bg-danger"></div>
</div>
```
