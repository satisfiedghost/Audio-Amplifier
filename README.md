# Audio-Amplifier
A simple audio amplifier, intended to drive larger (>25Ω) headphones.

I chose Polypropylene as the material for my input capacitor, as they tend to have a lower distortion than others, at the
expense of a larger form factor. 0.47uF lowered the -3dB point to 3Hz, which should exhibit acceptable filtering once
the minimum range of human hearing is reached.

The 1000uF electrolytic on the power supply is likely overkill, but it certainly doesn't hurt to have if the headphones 
end up drawing large current spikes during loud parts of songs.

Some research told me that the OPA213PA op-amp is perfectly acceptable unless you're a true audiophile, in which case
a more expensive solution might be warranted.

The three bypass caps on each +- power supply are absolutey necessary, the amplifier will distort horribly without them.

# To Do
I want to find a nice form factor to house the board. I'm thinking a wooden box would look sleek and has the advantage of 
being largely non-conductive.
