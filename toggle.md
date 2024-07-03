# Toggle List Example

Below is an example of a toggle list created using HTML and JavaScript.

```html
<script>
  function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
      content.style.display = "block";
    } else {
      content.style.display = "none";
    }
  }
</script>

<h2 onclick="toggleContent('section1')">Section 1</h2>
<div id="section1" style="display:none;">
  <p>This is the content of section 1.</p>
</div>

<h2 onclick="toggleContent('section2')">Section 2</h2>
<div id="section2" style="display:none;">
  <p>This is the content of section 2.</p>
</div>

<h2 onclick="toggleContent('section3')">Section 3</h2>
<div id="section3" style="display:none;">
  <p>This is the content of section 3.</p>
</div>
```

# Toggle List Example

Below is an example of a toggle list created using HTML and JavaScript.

<script>
  function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
      content.style.display = "block";
    } else {
      content.style.display = "none";
    }
  }
</script>

## Section 1

<h2 onclick="toggleContent('section1')">Section 1</h2>
<div id="section1" style="display:none;">
  <p>This is the content of section 1.</p>
</div>

## Section 2

<h2 onclick="toggleContent('section2')">Section 2</h2>
<div id="section2" style="display:none;">
  <p>This is the content of section 2.</p>
</div>

## Section 3

<h2 onclick="toggleContent('section3')">Section 3</h2>
<div id="section3" style="display:none;">
  <p>This is the content of section 3.</p>
</div>
