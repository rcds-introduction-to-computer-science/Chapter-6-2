# Chapter-6-2
Rewrite the following code using a for loop.

```Processing
size(200, 200);
background(255);

float w = width;
while (w > 0) {
  stroke(0);
  fill(w);
  ellipse(width/2, height/2, w, w);
  w = w - 20;
}
```
