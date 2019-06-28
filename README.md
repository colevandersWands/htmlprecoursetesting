# htmlprecoursetesting

## H1

The HTML
```html
<h1>I am the title of the story.</h1>
```

DOM Tree representation
```
HTML
|- HEAD
|- BODY
   |- H1
      |- #text: I am the title of the story.
```

__live__
<h1>I am the title of the story.</h1>

---

## tables

The HTML
```html
<table>
  <tr>
    <td>top left</td>
    <td>top right</td>
  </tr>
  <tr>
    <td>bottom left</td>
    <td>bottom right</td>
  </tr>
</table>
```

DOM tree
```
HTML
|- HEAD
|- BODY
   |- TABLE
      |- #text:
      |- TBODY
      |  |- TR  
      |  |- #text:
      |  |- TD
      |  |  |- #text: top left
      |  |- #text:
      |  |- TD
      |  |  |- #text: top right
      |  |- #text:
      |- #text:
      |- TR  
      |  |- TR  
      |  |- #text:
      |  |- TD
      |  |  |- #text: bottom left
      |  |- #text:
      |  |- TD
      |  |  |- #text: bottom right
      |  |- #text:
      |- #text:
```

__live__
<table>
  <tr>
    <td>top left</td>
    <td>top right</td>
  </tr>
  <tr>
    <td>bottom left</td>
    <td>bottom right</td>
  </tr>
</table>
