Pretty Dots
==============

Originally built from scratch by Cassidy!

###The Dots

Be sure to click around the dots to mess with them. That was built from scratch, too.

Seriously though.  This small snippet of JavaScript makes each circle:

```js
con.beginPath();
con.arc(this.x, this.y, this.r, 0, Math.PI * 2, true);
con.closePath();
```

So cute.

You'll notice a `lifetime` variable in the Dot settings.
I originally made that because the Dots were going to fade out and die after a while, but that was too depressing.  So that name doesn't really mean much.
But `lifetime` does play a part in the speed/smoothness of the Dot motion.  If you mess with it, you can see for yourself.

###Hooray.

Please submit an issue if it doesn't work on your computer/device!

Enjoy! :)
