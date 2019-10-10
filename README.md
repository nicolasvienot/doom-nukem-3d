# doom-nukem-3d

Samples

<div class="row">
  <div class="column">
    <img src="resources/parkour.gif" alt="Snow" style="width:100%">
  </div>
  <div class="column">
    <img src="resources/parkour.gif" alt="Forest" style="width:100%">
  </div>
  <div class="column">
    <img src="resources/parkour.gif" alt="Mountains" style="width:100%">
  </div>
</div>

<img align="left" width="415" src=resources/parkour.gif>
<img align="right" width="415" src=resources/parkour.gif>

![Parkour](resources/parkour.gif)
![Gif2](resources/gif2.gif)
![Editor2](resources/editor2.gif)

/* Three image containers (use 25% for four, and 50% for two, etc) */
.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
