DEMO SEMI-GENERATIVE PD PATCH SET
---------------------------------
The zip contains the following files

main.pd      << the main (root) patch
clock.pd     << a timekeeping abstraction
reverb.pd    << reverb effect (uses echo.pd)
echo.pd      << delay abstraction (used in reverb)
pan.pd       << simple panning abstraction (mono in- stereo out)
outmix.pd         << ouput abstration, mixes overall out with reverb
instrument1.pd    << wave generator instrument
instrument2.pd    << wave generator instrument
instrument3.pd    << wave generator instrument
instrument4.pd    << wave generator instrument
MTOF.TXT     << conversion data
DBTORMS.TXT  << conversion data
README.txt        << This file!!


The main.pd patch references all the other patches within it.
However these patches are made as abstractions to show how you can duplicate,
re-name, modify and re-use them..

I'm sure that much of the work is lazy and unelegant
(I would use more virtual sends rather than direct inlet-outlet links,
but these links help to show the way data flows)

And much could be done to improve/extend the individual patches
(Every instrument uses the same envelope code and takes few parameters,
extra information could be passed for modulations etc).

However I hope that this example should be easy to reverse engineer
and give users an idea of how generative composition can be acheived.

The example focuses on rather simple random number generators using fixed
note scales, but there are many more advanced methods of driving generative composition.
(markov chains, cellular automata, fractal recursion, etc)
Generative signals need not just effect score based decisions, but can also influence
synthesis parameters and effects.

Anyway, have fun and I hope this helps some people to get started with pd!

tom@nullpointer.co.uk
http://www.nullpointer.co.uk

p.s. http://www.pure-data.org is a pretty good resource for further info..