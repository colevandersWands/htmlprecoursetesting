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

[dom viewer permalink](https://software.hixie.ch/utilities/js/live-dom-viewer/?%3Ctable%20id%3D%22inspect-me%22%3E%0A%20%20%3Ctr%3E%0A%20%20%20%20%3Ctd%3Etop%20left%3C%2Ftd%3E%0A%20%20%20%20%3Ctd%3Etop%20right%3C%2Ftd%3E%0A%20%20%3C%2Ftr%3E%0A%20%20%3Ctr%3E%0A%20%20%20%20%3Ctd%3Ebottom%20left%3C%2Ftd%3E%0A%20%20%20%20%3Ctd%3Ebottom%20right%3C%2Ftd%3E%0A%20%20%3C%2Ftr%3E%0A%3C%2Ftable%3E)

The HTML
```html
<table id="inspect-me">
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
<li class="t1"><code>TABLE</code>
  <ul>
    <li class="t3"><code>#text</code>: <span>
  </span></li>
    <li class="t1"><code>TBODY</code>
      <ul>
        <li class="t1"><code>TR</code>
          <ul>
            <li class="t3"><code>#text</code>: <span>
    </span></li>
            <li class="t1"><code>TD</code>
              <ul>
                <li class="t3"><code>#text</code>: <span>top left</span></li>
              </ul>
            </li>
            <li class="t3"><code>#text</code>: <span>
    </span></li>
            <li class="t1"><code>TD</code>
              <ul>
                <li class="t3"><code>#text</code>: <span>top right</span></li>
              </ul>
            </li>
            <li class="t3"><code>#text</code>: <span>
  </span></li>
          </ul>
        </li>
        <li class="t3"><code>#text</code>: <span>
  </span></li>
        <li class="t1"><code>TR</code>
          <ul>
            <li class="t3"><code>#text</code>: <span>
    </span></li>
            <li class="t1"><code>TD</code>
              <ul>
                <li class="t3"><code>#text</code>: <span>bottom left</span></li>
              </ul>
            </li>
            <li class="t3"><code>#text</code>: <span>
    </span></li>
            <li class="t1"><code>TD</code>
              <ul>
                <li class="t3"><code>#text</code>: <span>bottom right</span></li>
              </ul>
            </li>
            <li class="t3"><code>#text</code>: <span>
  </span></li>
          </ul>
        </li>
        <li class="t3"><code>#text</code>: <span>
</span></li>
      </ul>
    </li>
  </ul>

__live__
<table id = "inspect-me">
  <tr>
    <td>top left</td>
    <td>top right</td>
  </tr>
  <tr>
    <td>bottom left</td>
    <td>bottom right</td>
  </tr>
</table>












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
