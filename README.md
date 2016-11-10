# gMaple-mini
### Diptrace version by Gruvin

**2014-03-05** LeafLabs appear to have ended production of their Maple and Maple-mini products.

At the time, I was not able to find any suppliers with remaining stock of the Maple-mini. I have 
since found that SparkFun.com still still appear to make the boards and there's a bunch of cheap
almost-clones on eBay. Even though the Gerbers from Leaflabs are available somewhere, I decided 
to roll my own, using my newly preferred eCAD software, [Diptrace](http://diptrace.com) (free version).

**2014-04-14** The first GMaple-mini is built and tested working. :-)

<img src="img/first-build-1.jpg">

<img src="img/first-build-2.jpg">

This design is heavily based on the original from LeafLabs, with special care to retain the ground 
and power plains for VCC/GND and AVCC/AGND, on a four layer board, along with high quality decoupling 
capacitors, push buttons, etc. (There are cheap knock-offs on eBay without any of that, far as I can tell.)

The following are early draft version, Diptrace renderings ...

<img src="img/gmaple-mini-3d.png">

<img src="img/gmaple-mini-3db.png">

<img src="img/gmaple-mini.png">

Diptrace uses VRML 2.0 (.wrl) 3D files. The USB socket, LED and push buttons are my own work, done in Wings3D.

This is my first 4-layer board in Diptrace, done as much for the learning curve climb, as anything. After 
all, LeafLabs say they make the Gerbers freely available. But I haven't found them (for revision two, with 
the extra diode) and I cannot get my free version of Eagle to produce Gerber files from the original CAD 
files. Boo hoo! Whatever. Never mind. :p

By far the cheapest place I could find to get small 4-layer boards like this made, was OSH Park. You get 
gold plated too, which is great. Be warned -- everything they do is in funky purple, even the delivery 
packaging. :-P I actually quite like it. Great branding, in any case.

## Diptrace, huh?

I hadn't heard of Diptrace until the day I started this project. A member of the Particle™ (formally Spark™) 
community put me onto it. At first, I was pessimistic, quite sure it would turn out to be yet another 
expensive, limited, awkward CAD attempt. But I had a personal recommendation to make it worth my while 
and boy was I pleasantly surprised. I found the software really nice to use.

Best of all, the free version has considerably fewer limitations than the every popular Eagle -- 
generous 300 pin limit, no board size limits (YAY!) two signal layers (at least two inner plane 
layers permitted) and everything else pretty much wide open -- including Gerber output, 
3D export and more. Nice.

## What about Eagle? 
Eagle is $700 minimum for me, because some of my board designs, ex. [gruvin9x](https://github.com/gruvin/gruvin9x), are simply larger 
than Eagle's free version limits. That and frankly, I strongly dislike Eagle's severely dated
user interface.

## Creative Commons License

This gMaple-mini project is licensed to match the original Maple design: Creative Commons share-a-like CC-BY-SA 2.0
