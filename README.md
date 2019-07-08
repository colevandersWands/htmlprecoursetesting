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
<ul class="domTree"><li class="t1"><code>HTML</code><ul><li class="t1"><code>HEAD</code></li><li class="t1"><code>BODY</code><ul><li class="t1"><code>TABLE</code><ul><li class="t3"><code>#text</code>: <span>
  </span></li><li class="t1"><code>TBODY</code><ul><li class="t1"><code>TR</code><ul><li class="t3"><code>#text</code>: <span>
    </span></li><li class="t1"><code>TD</code><ul><li class="t3"><code>#text</code>: <span>top left</span></li></ul></li><li class="t3"><code>#text</code>: <span>
    </span></li><li class="t1"><code>TD</code><ul><li class="t3"><code>#text</code>: <span>top right</span></li></ul></li><li class="t3"><code>#text</code>: <span>
  </span></li></ul></li><li class="t3"><code>#text</code>: <span>
  </span></li><li class="t1"><code>TR</code><ul><li class="t3"><code>#text</code>: <span>
    </span></li><li class="t1"><code>TD</code><ul><li class="t3"><code>#text</code>: <span>bottom left</span></li></ul></li><li class="t3"><code>#text</code>: <span>
    </span></li><li class="t1"><code>TD</code><ul><li class="t3"><code>#text</code>: <span>bottom right</span></li></ul></li><li class="t3"><code>#text</code>: <span>
  </span></li></ul></li><li class="t3"><code>#text</code>: <span>
</span></li></ul></li></ul></li></ul></li></ul></li></ul>


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



<ul class="domTree"><li class="t10">DOCTYPE: <code>html</code></li><li class="t1"><code>HTML</code><ul><li class="t1"><code>HEAD</code></li><li class="t1"><code>BODY</code><ul><li class="t3"><code>#text</code>: <span>...</span></li></ul></li></ul></li></ul>
















---



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
