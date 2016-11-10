# gMaple-mini
#### Diptrace version by Gruvin

**2014-03-05** LeafLabs appear to have ended production of their Maple and Maple-mini products.

At the time, I was not able to find any suppliers with remaining stock of the Maple-mini. I have 
since found that SparkFun.com still still appear to make the boards and there's a bunch of cheap
almost-clones on eBay. Even though the Gerbers from Leaflabs are available somewhere, I decided 
to roll my own, using my newly preferred eCAD software, [Diptrace](http://diptrace.com) (free version).

**2014-04-14** The first gMaple-mini is built and tested working. :-)

<img src="img/first-build-1.jpg" width="320">
<img src="img/first-build-2.jpg" width="320">

*[OSH Park](https://oshpark.com/) was by far the cheapest place to get small 4-layer boards like this made. You get 
gold plated as standard, too. Did you know that even their packaging is the same funky purple? Great branding!*

This design is heavily based on the original from LeafLabs, with special care to retain the ground 
and power plains for VCC/GND and AVCC/AGND, on a four layer board, along with high quality decoupling 
capacitors, push buttons, etc. (There are cheap knock-offs on eBay without any of that, far as I can tell.)

The following are early draft version, [Diptrace](http://diptrace.com) renderings ...

<img src="img/gmaple-mini-3d.png" width="320">
<img src="img/gmaple-mini-3db.png" width="320">
<img src="img/gmaple-mini.png" width="320">

Diptrace uses VRML 2.0 (.wrl) 3D files. The USB socket, LED and push buttons are my own work, done in [Wings3D](www.wings3d.com/).

This is my first 4-layer board, done as much for the learning experience as anything else.

### Diptrace, huh?
A member of the [Particle™](https://particle.io) (formally Spark™) community put me onto it. I really like it.

2016-11-08: Diptrace is available for free, with all features and libraries, maximum 300 pins and 2 signal layers 
(unlimited power planes), for non-profit use only -- no board size limits! It runs under Windows natively and under Linux and macOS, using abottled wine installation. (I installed the Windows version on my Mac, using my existing wine instance.)

### But everyone uses Eagle! 
Not me. There's no comparion. [Diptrace](http://diptrace.com) has no board size limits (only generous 
pin count) and has a far more user friendly interface. Licensed versions are also considerably cheaper 
than Eagle, no matter how you look at it.

Eagle would cost me $700, simply because some of my boards are too big for the free version.
Example: [gruvin9x](https://github.com/gruvin/gruvin9x). No way I can justify that kind of coin.

### Open Source for the Win!
[KiCAD](http://kicad-pcb.org/) is still my favourite. I use it for most my stuff. It's fully open source and 
free, as in speach and as in beer. It's a no brainer.

### Creative Commons share-a-like CC-BY-SA 2.0 License
gMaple-mini is licensed to match the original Leaflabs design. 
