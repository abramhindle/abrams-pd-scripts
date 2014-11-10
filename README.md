Abram's PD Scripts
==================

These are Abram's PD scripts.

Abram currently thinks that PD is suffering from Perl syndrome:

* The manuals are filled with examples when the examples should already be abstractions

Thus 2 useful files in this package are:

* phasor.pd -- a bang-time (sp?) phasor. This phasor allows you walk over the range of an array with ease.
  * Do you know of any already existing non-audio signal phasor? Tell abram!
* arrayjoin.pd -- join an array into a string. This was stolen from the manual, but it should come out of the box with pd.
* tablescalar.pd -- apply some function to each element in a table. It uses feedback (see sines.pdf.pd) but it allows you to multiply arrays by a scalar values

The instruments in here are:

* ctrl-midi1.pd -- an attempt to understand the BCS2000 midi controller 
* sines.pdf.pd -- Use all 32 knobs of the BCS2000 midi controller or your mouse to set the coeffecients in a sinewave.
  * this one is pretty complicated because I had to form complicated messages to send around to generate the sine table. What's great about it is that I don't use 32 sine oscillators to make it! 
  * ![sine.pd.pd](images/sines.pdf.pd "sines.pdf.pd")


LICENSE
=======

Either the same license as PD and the manuals or Apache 2.0 . It's up to you.
