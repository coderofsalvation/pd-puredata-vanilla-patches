Miscellaneous

bangs.pd - Generate a series of bangs at a given interval.
bangct.pd - Outputs a count of the number of bangs it has seen, until reset.
bangloop.pd - A looping counter [0..n) that increments when banged. Can drive a sequencer.
nrpn_in.pd - Reads (inputs) 14-bit MIDI messages in NRPN format.
nrpn_out.pd - Sends (outputs) 14-bit MIDI messages in NRPN format.
ctrl_sync.pd - Keeps a pd UI control synchronized with a MIDI control channel
hmstimer.pd - Displays time duration as HH:MM:SS as a GOP.
keyonoff.pd - Generates a 1 and 0 for a filtered/held keypress.
nrpn_sync.pd - Keeps a pd UI control synchronized with a NRPN controller channel
oscsq~.pd - Square wave oscillator, made by amplifying and then clipping a sine (osc~) wave.
tri~.pd - Nice tight triangle wave, based on phasor~.
ptrain~.pd - Pulse train. Probably very similar to pwm~ (below).
pwm~.pd - Pulse width modulation on a square wave. Probably similar to ptrain~ (above).
dline~.pd - Variable, dynamic feedback delay line. Inputs include feedback amount and delay time.
panning~.pd - Splits and pans a mono signal into stereo, based on a control input.
rndseq.pd - Randomized sequencer. You can specify the number of steps, base, and range.
mc.pd - Simple midi controller. Specify the midi "item" (man, my midi terminology is lacking) and a range, and you'll get a numeric output based on the midi input. Useful with an external midi controller.
mout~.pd - Simple mixed output to dac~ with graph on parent volume control, level display, VU meter. The first GOP patch that ever worked right.
range.pd - Does the ratio math to convert a number from a source range into a target range.
wavrec~.pd - Simple record-to-wav (start/stop/timer) GOP abstraction.
