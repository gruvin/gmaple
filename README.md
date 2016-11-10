# gMaple-mini
### Diptrace version by Gruvin

**2014-03-05** LeafLabs appear to have ended production of their Maple and Maple-mini products.

At the time, I was not able to find any suppliers with remaining stock of the Maple-mini. I have 
since found that SparkFun.com still still appear to make the boards and there's a bunch of cheap
almost-clones on eBay. Even though the Gerbers from Leaflabs are available somewhere, I decided 
to roll my own, using my newly preferred eCAD software, [Diptrace](http://diptrace.com) (free version).

**2014-04-14** The first gMaple-mini is built and tested working. :-)

<img src="img/first-build-1.jpg" width="320">
<img src="img/first-build-2.jpg" width="320">

<blockquote><em>[OSH Park](https://oshpark.com/) was by far the cheapest place to get small 4-layer boards like this made. You get 
gold plated as standard, too. Did you know that even their packaging is the same funky purple? Great branding!</em></blockquote>

This design is heavily based on the original from LeafLabs, with special care to retain the ground 
and power plains for VCC/GND and AVCC/AGND, on a four layer board, along with high quality decoupling 
capacitors, push buttons, etc. (There are cheap knock-offs on eBay without any of that, far as I can tell.)

The following are early draft version, [Diptrace](http://diptrace.com) renderings ...

<img src="img/gmaple-mini-3d.png">
<img src="img/gmaple-mini-3db.png">
<img src="img/gmaple-mini.png">

Diptrace uses VRML 2.0 (.wrl) 3D files. The USB socket, LED and push buttons are my own work, done in Wings3D.

This is my first 4-layer board, done as much for the learning experience as anything else.

## Diptrace, huh?
A member of the [Particle™](https://particle.io) (formally Spark™) community put me onto it. I really like it.

2016-11-08: It looks as though Diptrace doesn't offer the free licence I enjoyed back in 2014? 
That appears to be $75 now.

## What about Eagle? 
There's no comparion. [Diptrace](http://diptrace.com) has no board size limits (only generous 
pin count) and has a far more professional style user iunterface, IMO. Licensed versions are 
also considerably cheaper than Eagle.

Eagle is $700 minimum for me, because some of my board are larger than Eagle's free version limits.
Example: [gruvin9x](https://github.com/gruvin/gruvin9x). No way I can justify that amount of coin,
especially for a program I frankly don't even like.


## KiCAD Still my Favourite

I still use KiCAD for most my designs. Compeltely free, open source and highly capable.

## Creative Commons License

gMaple-mini is licensed to match the original Leaflabs design: Creative Commons share-a-like CC-BY-SA 2.0
