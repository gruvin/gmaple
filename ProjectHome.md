**2014-03-05** [LeafLabs](http://leaflabs.com) appear to have ended production of their Maple and Maple-mini products. :'( Well,  I guess they have their reasons.

> At the time, I was not able to find any suppliers with remaining stock of the Maple-mini. (I have since found that SparkFun.com still have/had stocks.) So, even though the Gerbers are supposed to be available somewhere, I decided to roll my own, using my newly preferred eCAD software, [Diptrace](http://www.diptrace.com) (free version).

**2014-04-14** The first GMaple-mini is built and tested working. :-)

> ![https://gmaple.googlecode.com/svn/wiki/About.attach/first-build-1.jpg](https://gmaple.googlecode.com/svn/wiki/About.attach/first-build-1.jpg)

> ![https://gmaple.googlecode.com/svn/wiki/About.attach/first-build-2.jpg](https://gmaple.googlecode.com/svn/wiki/About.attach/first-build-2.jpg)


---



This design is heavily based on the original from LeafLabs, with special care to retain the ground and power plains for VCC/GND and AVCC/AGND, on a four layer board, along with high quality decoupling capacitors, push buttons, etc. (There are cheap knock-offs on eBay without any of that, far as I can tell.)

**The following are early draft version, [Diptrace](http://www.diptrace.com) renderings** ...

> ![https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini-3d.png](https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini-3d.png)

> ![https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini-3db.png](https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini-3db.png)

> ![https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini.png](https://gmaple.googlecode.com/svn/wiki/About.attach/gmaple-mini.png)

> _Diptrace uses VRML 2.0 (.wrl) 3D files. The USB socket, LED and push buttons are my own work, done in [Wings3D](http://www.wings3d.com)._

This is my first 4-layer board in Diptrace, done as much for the learning curve climb, as anything. After all, LeafLabs say they make the Gerbers freely available. But I haven't found them (for revision two, with the extra diode) and I cannot get my free version of Eagle to produce Gerber files from the original CAD files. Boo hoo! Whatever. Never mind. :p

By far the cheapest place I could find to get small 4-layer boards like this made, was [OSH Park](http://oshpark.com). You get gold plated too, which is great. Be warned -- everything they do is in funky purple, even the delivery packaging. :-P I actually quite like it. Great branding, in any case.

# Creative Commons License #

This project is licensed to match the original Maple design: [Creative Commons share-a-like CC-BY-SA 2.0](http://creativecommons.org/licenses/by-sa/2.0/)

See the amazing, brilliant [LeafLabs](http://leaflabs.com) team website for details. (I do hope they're working on the next best thing. They've been quite quiet of late, even cancelling one of their projects.)

# So what is Diptrace? #
## An impromptu, "first impressions", review ... ##
I had not heard of [Diptrace](http://www.diptrace.com) until the day I started this project, when a member of the [Spark™ community forum](https://community.spark.io) put me onto it. At first, I was pessimistic, quite sure it would turn out to be yet another expensive, limited, awkward CAD attempt. But I had a personal recommendation to make it worth my while and boy was I pleasantly surprised. I found the software _really_ nice to use.

Best of all, the free version has considerably fewer limitations than the every popular Eagle -- generous 300 pin limit, no board size limits (YAY!) two signal layers (at least two inner plane layers permitted) and everything else pretty much wide open -- including Gerber output, 3D export and more!

I finally found an eCAD program that hits all the right spots for me, including my budget. Yay \o/ ... Definitely going to buy the standard license, at I think USD$375, which is no small sum for me to be honest. But I believe it will be money well spent, as I move up to 3+ signal layer designs, with greater confidence than KiCAD, which I've used and loved up until now.

(Eagle is $700 minimum for me, you see, because many of my boards designs are just a tiny bit bigger than their free version limits. Honestly though, call me odd, but I cannot stand Eagle's user interface. It drives me absolutely nutty. So no personal loss there. :p Just a shame there has to be yet another file format for open source CAD in the world. Such is life.)

Gruvin