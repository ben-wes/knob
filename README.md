# knob
Pure Data (Pd) knob

Requires Pd0.53-1 or versions before Pd0.53-0 since it relies on the "infinite slider" functionality described in https://github.com/pure-data/pure-data/issues/1831 

Optional positional creation arguments are:
1. `<min_value>` (default: 0)
2. `<max_value>` (default: 1)
3. `<knob_color>` in Pd's 0..999 color syntax (default: 0 - black)
4. `<mark_color>` in Pd's 0..999 color syntax (default: 999 - white)

Possibly useful features to follow soon:
* infinite rotation (where output is only the step and not absolute value)
* messages to change stuff
* forget about this abstraction because there are better knobs around for Pd
