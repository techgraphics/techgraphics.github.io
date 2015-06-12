---
layout: notes
title: Font Size Derping 
category: codepen 
---
<div data-height="365" data-theme-id="15936" data-slug-hash="rVwZKd" data-default-tab="css" data-user="garethtaylor777" class='codepen'><pre><code>html {
//  -webkit-text-size-adjust: 100%;
//    -ms-text-size-adjust: 100%;
font-family: &quot;Helvetica Neue&quot; Helvetica Verdana Arial sans-serif;
//  font-size: 114.2857%; // 10pt absolute???
//  font-size: 137.14285%; // 12pt absolute???
//  font-size: 150.00%; // 12pt absolute???
 font-size: 133.33%; // 12pt absolute???
  line-height: 1.0;
  background-color: #ffffff;
}
p {
//  padding:0;
  margin:0.5rem;
}

div.a, 
div.b, 
div.c, 
div.d {
  line-height: 1.1666rem;
  width: 100%;
//  height: 28rem;
  float: left;
}
div.a {
  font-family: &quot;Helvetica Neue&quot;;
  font-size: 0.8333rem;
}

div.b {
  font-family: &quot;Calibri&quot;;
  font-size: 0.8065rem;
}

div.c {
  font-family: &quot;Palatino&quot;;
  font-size: 0.8750rem;
}

div.d {
  font-family: &quot;Optima&quot;;
  font-size: 0.8001rem;
}

</code></pre>
<p>See the Pen <a href='http://codepen.io/garethtaylor777/pen/rVwZKd/'>Font size derping</a> by Gareth (<a href='http://codepen.io/garethtaylor777'>@garethtaylor777</a>) on <a href='http://codepen.io'>CodePen</a>.</p>
</div><script async src="//assets.codepen.io/assets/embed/ei.js"></script>