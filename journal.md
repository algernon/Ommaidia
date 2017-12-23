# Annals of Ommatidia

## 2017-12-23

I've been thinking about LEDs. I definitely do not want a LED under the ball,
but perhaps they could be useful under the buttons? And while there, what about
underglow? Between the two, I think underglow would make the more sense, and it
would be the least disturbing too.

On another note, I'm more and more convinced that I'll have to experiment with a
thumb-controlled trackball.

## 2017-12-19

Started experimenting with the idea of a thumb-operated trackball, in a more
serious manner. As in, I took my Kensington Orbit, tilted it, and tried how it
feels to roll the ball with my thumb. It wasn't terribly bad. This opens up the
possibility of more experiments, and more designs.

While doing this, I was thinking about if I need a large ball, or if a smaller
one, sunken deeper into its mount would work. Something like
[this](https://na.suzohapp.com/products/trackballs/56-0100-11HL), perhaps.

## 2017-12-18

Today [this thread][gh:gaming-keypad] happened to come my way, and it gave me so
many ideas to ponder about!

 [gh:gaming-keypad]: https://geekhack.org/index.php?topic=93039.0

The look, the design, and the ergonomics of that keypad are *sweet*, and some of
the ideas I could likely adapt to a trackball. With buttons on top, and joystick
on the side, and a shape designed for grip, this almost translates 1-to-1 into a
thumb-controlled trackball.

What if I made a trackball, that was similarly designed for grip? With less
adjustability, less keys, a ball instead of a joystick, and more tilting. That
may make it impossible to have a useful palm key, unless I tilt it very high -
but I plan to do that anyway. I could have two buttons on the inner side of the
grip, for index and middle finger. Two buttons above those, same fingers, but
pressed in a slightly lesser gripping state.

This could work. Now I need to draw a sketch, and compare the feels - at least
in theory. Lots of hand gestures forthcoming that make my wife question my
sanity...

## 2017-12-08

For the past couple of days, I've been pondering about how I would mount the
ball, and this may very well end up being the hardest part. I do not have a 3D
printer, nor do I have easy access to one, so prototyping will be a bit hard.

I did find a [blog post][blog:madox:trackball] about someone else on a similar
journey, which appears to be a decent resource. Having tried to search for DIY
trackballs, most solutions were either reusing existing components, or looked
like a brick, or both.

 [blog:madox:trackball]: http://www.madox.net/blog/tag/trackball/

Having searched further, I found a [reddit
thread][reddit:trackball:diy-components], which led me to a [listing of ball
bearings][ebay:ball-bearings], a [deskthority
thread][deskthority:frictionless-trackball], lots of ideas to digest from there.

 [reddit:trackball:diy-components]: https://www.reddit.com/r/Trackballs/comments/2fsebm/suggestions_for_component_purchase_for_diy/
 [ebay:ball-bearings]: https://www.ebay.com/itm/400561352309?_trksid=p2060778.m1438.l2649&ssPageName=STRK%3AMEBIDX%3AIT
 [deskthority:frictionless-trackball]: https://deskthority.net/workshop-f7/frictionless-trackball-via-ball-transfer-units-t8286.html

While browsing Deskthority, I came across [another
thread][deskthority:custom-trackball], with a different solution for the
mounting problem. [GeekHack][geekhack:custom-ergo-trackball] also has an
interesting thread about the subject.

 [deskthority:custom-trackball]: https://deskthority.net/workshop-f7/custom-trackball-t4773.html
 [geekhack:custom-ergo-trackball]: https://geekhack.org/index.php?topic=71494.0#lastPost

Also ran across a lot of half-ready, off-the-shelf "DIY Arcade Trackball"
things, but those were all very far from what I want. I don't think I could
salvage them for some components, either. For reference, here's [one
shop][suzohapp] that sells such components. Perhaps worth considering one, after
all...

 [suzohapp]: https://na.suzohapp.com/products/trackballs/

There's also [this funny video](https://vimeo.com/69113731) of a giant
trackball. Not really useful, but hey. This is a journal, not a schematic.

## 2017-12-03

This is not how it all started. It all started with a
[picture][imgur:ltrac-wood], and then some [brain
dumping][m:ommatidia-beginning]. I put the idea aside after [writing a blog
post][a:trackball-quest] about it. But last night, when I was casually browsing
around, half asleep, I failed a saving throw as we say it. Having failed it, I
had no other choice, but to pursue the idea further, and that's how the first
sketch was born:

 ![Ommatidia first sketch](data/ommatidia-sketch-20171202.svg)

 [imgur:ltrac-wood]: https://imgur.com/a/hAOC8
 [m:ommatidia-beginning]: https://trunk.mad-scientist.club/@algernon/98969608858699528
 [a:trackball-quest]: https://asylum.madhouse-project.org/blog/2017/11/15/quest-for-the-perfect-trackball/

Pretty simple, though obviously needs a lot of work. This is just something I've
done in Inkscape in like five minutes.

But it got me thinking about the properties of the trackball. I started
imagining how I'd use it, whether the arcade thumb buttons and palm key would be
useful, or too much. Started wondering how much it would cost me to build it,
and if I can even find all the components I need.

So I went to [Adafruit][adafruit], to see if I can find anything. I should not
have. So many weird and dangerous ideas!

 [adafruit]: https://www.adafruit.com/

What if I used small [thumb joysticks](https://www.adafruit.com/product/512)
instead of the arcade buttons? They could double as scroll wheels, too. This
sounded neat first, but what if I want to scroll *and* click? Sure, I could make
the other stick into the opposite button, but operating two things with the same
thumb is not going to work well. It was a useful thought experiment,
nevertheless.

Then, I found a [scrubber knob](https://www.adafruit.com/product/2055), which is
much closer to an arcade button, can work as a button too, but I can also use it
as a scroll wheel, in addition to using the ball. So if I want to scroll +
click, I scroll with the ball, click with these. If I just want to scroll, I
just turn the knob with my thumb. This is an idea I haven't given up on yet.

But... here's the thing: [arcade buttons](https://www.adafruit.com/product/471)
look great. They just go incredibly well with what I had in mind.

I tried to search for a suitable optical sensor on Adafruit, but found none.
Thankfully, there is a [promising one][adns-9800] available elsewhere, with
sweet properties, perfect for a trackball.

 [adns-9800]: https://www.tindie.com/products/jkicklighter/adns-9800-laser-motion-sensor/

This is as far as I got - along with choosing a name, [thanks
James][m:ommatidia] for the suggestion!

 [m:ommatidia]: https://mastodon.social/@jamesnvc/99107076789456072

Oh, I also ran into a [foot switch](https://www.adafruit.com/product/423). Not
sure how that'd go with a trackball, but it is something I want to eventually
play with, too.
