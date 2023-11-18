# Neptune-4-Max---Power Supply shortfall
The Neptune 4 Max power supply issue/shortfall

When I had a number of "Neptune 4 Max operation glitches", which were random various
errors (on screen), or even just a lock up with no error reported, I decided it was
possible that these were all 'false positives' and not whart the error was reporting
at all !!  The first thing this sort of occurence can be  caused by (in electronics)
are power supply, Voltage, issues. This lead me to investigate the N4max power supply.

I had read that it is a 400W power supply - the same one used in all the other 
Neptune 4's.  That would seem a likely shortfall !!!
I also read that the N4Max has a 320W Heated Bed, so THAT immediately rang alarm bells!

You have a "400w" power supply, that needs to power a 320W Heated Bed and a 60W Hotend
AND THEN, the MCU's/board, maybe LED's, some fans...... you are right up near, at, or
over 400W !!!
But it gets worse.....
The power supplies that all these many brands of 3D Printers use, are a 'generic' type
sold under 1001 different 'brand names', but are all IDENTICAL in "every" way which shows
they come out of the same main manufacturing company.  These power supplies all come with
"manufacturer recommend - operate at only 80% of the rated value"!!!  For a 400W power
supply, that means 320W !!!  Now the N4Max is NOTABLY over that recommended limit.

The first thing you might ask, and be appalled by, is that these power supplies are sold as
"400W" by that main manufacturer, yet THEY recommend only running them at 80%!!  Why aren't
they just selling a "320W" power supply then!!??  Obviously a higher number (power, 400W)
will SELL BETTER!!

What happens with these power supplies is that they CAN supply 400W, but once you head 
over 80% (320W) they become notably less efficient and also in their voltage stability.
Ripple (noise) levels rise.... operating temperatures rise.... so you lose out in
Voltage "quality" and also lifespan.  AND.... if you run it up near the maximums that
instability can become a NOTABLE amount, which then can cause 'trauma' for digital
circuits - especially COMPUTER systems!  Crashes/lockups, or just errored operation/s.
So this "400W" power supply is ASKING for notable trouble!!!  Whether right "now", or
sooner or later.
Many users have had their N4Max power supply "blow up" - fail, die... totally.
Many users are having various errors, or just printing "shutdown"/stopping, because
the power supply really had a glitch and temporarily messed everything up (MCU crash etc).

I did Power Tests on my N4Max..... when you heat up the Bed AND the Nozzle at the same 
time, it runs around a range of 375W to 395W !!!  Just for the length of time it takes 
to get the Nozzle up to temp. (2 minutes approx?). Well over the "recommended 320W".
But note, once the Nozzle - which is the fastest and first to reach the target temperature
- the power used will drop by "40W" or so.... it is a 60W Hotend heater, but once heated
it only needs "bursts" of higher power and not too often. So you will be down in the
"330W" or so region of total power used then. Still JUST over the "320W recommended"
level.  And once the Bed reaches target, it drops right back for an ongoing "150W" sort
of region used.
Then when printing begins, more Hotend power is needed - but still not full time maximum -
and a bit more bed heating power needed, but then add more fans, and Stepper Motors running
non-stop. You are back in the "200W-250W" regions, which is fine as it is under the
"320W recommended".

BUT, I still had random glitches and lockups which shows, somewhat but not 100% for sure,
that the Power Supply is NOT providing a stable/assured, low ripple/noise output.  It COULD
be a randon unlucky quality power supply - but it is happening to MANY people.
I use these power supply types quite a lot, for many electronic devices/projects, so I
have seen them quite a lot, over a very long time - they have been around for a LONG time.
I rarely use them to anywhere near their maximum rating, not even 3/4 really, if even 1/2
of Max. So I have not seen them reach issue levels. But I also know what HAPPENS in any
power supply, as more load is demanded, and that is where a truly good power supply will
show up its merit/worth, versus a less truly capable one.
These are definitely "Chinese budget low quality' power supplies!! The 400W costs about 
US$25. A DECENT power supply of 400W would cost more like $100 or more!
You can look at PC ATX power supplies and how they run from $25 to $200 !! When you pay 
more, you will get higher quality filtering (stable voltage), higher power capable
components (reliable, low taxed, longer lifespan).

So in the end, what this means for the N4Max is that is SHOULD have a BETTER power supply!!!
The "Cheap" way to achieve this is to buy a "Cheap Chinese" power supply, of ANY of these
same "1001 brands" type, but of a HIGHER RATING..... so that you will be running it well under
their recommended level. Basically the lower the load you have, then that power supply will 
operate with much lower issues - ripple/noise much lower, components stresses much lower.
To do this you want the "600W" version of this power supply type.  It is the same case used
as for the 200W,240W,250W,280W,300W, 350W, 400W, 480W, 500W etc  so it will fit straight in
with every same connector, mounting holes, etc.  IDENTICAL.
So then you have a "600W advertised" but "Truly 480W capable" power supply - which will cope and be
stable for sure....... because you are never going to go over even 400W anyway!
The 600W version costs about US$30.....

(My old Anycubic Chiron 400x400x400 3D Printer haad a 1000W version of this no-name brand
power supply!!!  1000W !!!)

The Elegoo Neptune 4 Max having the SAME 400W power supply as the Neptune 4 or Pro etc is
just ridiculous.... a sad joke!
I have changed mine to a 600W and yet to see another glitch/issue, so far.......
But who knows what other 'not done so well' aspects of the N4Max Elegoo have done in
other areas!!?? (MCU board, or whatever)



Here is ONE Aliexpress link, but go a hunt/look for the cheapest supplier you can find!
https://www.aliexpress.com/item/1005005092593108.html?spm=a2g0o.order_list.order_list_main.4.1d1a1802THyO8s




