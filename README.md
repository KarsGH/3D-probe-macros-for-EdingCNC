Macro-3D-Probe is a macro set that allows to zero a workpiece using a 3D probe.
It is intended to be used with the EdingCNC contol software.


The routines are funtional and tested but usually need some adaptation to your own EdingCNC set-up!!!!
Check this before using them!!!


It supports zeroing:

- Z-height only, or including zero X/Y at the 3D probe tip as well, as a rough reference
 
- X/Y, and if selected Z, at each of the workpiece corners (selectable)
 
- Zero X/Y at the center of a hole or a cylinder.
 
Also there is a routine to measure the current tool length comared to the probed workpiece surface which shifts the Z-zero value accordingly. Take care: these routines use fixed value (#4999) as reference height for the toolsetter. At current the tool table is not used to offset for various tools.
 
The macro's support a probe that is shifted compared to the spindel (having it's own mounting bracket). If the probe is used in the spindel the offset values (#4981, #4982, #4983) can be set to zero.


 
 
